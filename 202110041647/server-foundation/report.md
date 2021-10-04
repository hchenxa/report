# :warning: Had some failures when running regression on cluster ocp4-aws-41 with test snapshot 2.4.0-SNAPSHOT-2021-10-02-11-10-03 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/283/


ACM Version: v2.4.0

Hub Cluster Version: 4.8.11

Hub Cluster: https://multicloud-console.apps.ocp4-aws-41.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.12

Managed Cluster: https://console-openshift-console.apps.acmqe-24-ocp-aws-41-fips-hive-gcp.gcp.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110041647/

## Tests:

|Status|Results|Test|
|---|---|---|
| :large_blue_circle: | skipped | Testing BareMetalAsset Create bma BMA should be auto created successfully |
| :large_blue_circle: | skipped | Testing BareMetalAsset Deleting a ClusterDeployment delete clusterdeployment should clean ref in bma |
| :white_check_mark: | passed | Testing ClusterClaim should get the required ClusterClaims successfully the managed cluster |
| :white_check_mark: | passed | Testing ClusterClaim should not remove the customized claim |
| :white_check_mark: | passed | Testing ClusterClaim should recreate the ClusterClaim once it is deleted |
| :white_check_mark: | passed | Testing ClusterClaim should rollback the change of the ClusterClaim once it is modified |
| :x: | failed | Testing ClusterClaim should sync the label to claim |
| :white_check_mark: | passed | Testing ClusterView to get managedClusterSets should list the managedClusterSets.clusterView successfully |
| :x: | failed | Testing ClusterView to get managedClusters should list the managedClusters.clusterview successfully |
| :white_check_mark: | passed | Testing ManagedCluster Get ManagedCluster cpu worker capacity should get a cpu_worker successfully in status of managedcluster |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from apiserver |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from configmap |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from service account |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction deployment should be created successfully in managedcluster |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should create successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should delete successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should get successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should have a valid condition |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction Should create deleteManagedClusterAction successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction deployment should be deleted successfully in managedcluster |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should delete successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should get successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist Should create deleteManagedCusterAction successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist deployment should be deleted successfully in managedcluster |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should delete successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should get successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should have a valid condition |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction Should create udateManagedClusterAction successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should delete successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should get successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist Should create updateManagedClusterAction successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should delete successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should get successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterImageRegistry add / remove imageRegistry label successfully |
| :white_check_mark: | passed | Testing ManagedClusterView if agent is lost Creating a managedClusterView Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterView if agent is ok Creating a managedClusterView Should create successfully |
| :white_check_mark: | passed | Testing user create/update managedCluster without mangedClusterSet label should create and update the managedCluster successfully |
| :white_check_mark: | passed | Testing webhook cert rotation should create and update the managedCluster after cert rotation successfully |


---

### Failed Test Details

#### :x: Testing ClusterClaim should sync the label to claim

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterclaim_test.go:93
Timed out after 300.001s.
Unexpected error:
    <*errors.StatusError | 0xc0002f3b80>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "clusterclaims.cluster.open-cluster-management.io \"test\" not found",
            Reason: "NotFound",
            Details: {
                Name: "test",
                Group: "cluster.open-cluster-management.io",
                Kind: "clusterclaims",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    clusterclaims.cluster.open-cluster-management.io "test" not found
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterclaim_test.go:103
```

#### :x: Testing ClusterView to get managedClusters should list the managedClusters.clusterview successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:82
Unexpected error:
    <*errors.StatusError | 0xc000624e60>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Unauthorized",
            Reason: "Unauthorized",
            Details: nil,
            Code: 401,
        },
    }
    Unauthorized
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:89
```

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from apiserver

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:37
Unexpected error:
    <*errors.errorString | 0xc000786120>: {
        s: "unexpected error when reading response body. Please retry. Original error: read tcp 10.0.118.36:37332->52.9.180.53:6443: read: connection reset by peer",
    }
    unexpected error when reading response body. Please retry. Original error: read tcp 10.0.118.36:37332->52.9.180.53:6443: read: connection reset by peer
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:75
```

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from configmap

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:99
Unexpected error:
    <*errors.errorString | 0xc00058b070>: {
        s: "unexpected error when reading response body. Please retry. Original error: read tcp 10.0.118.36:57382->54.219.213.166:6443: read: connection reset by peer",
    }
    unexpected error when reading response body. Please retry. Original error: read tcp 10.0.118.36:57382->54.219.213.166:6443: read: connection reset by peer
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:118
```

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from service account

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:136
Timed out after 300.000s.
Expected
    <bool>: false
to be true
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:157
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction deployment should be created successfully in managedcluster

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:171
Timed out after 300.000s.
Error: Unexpected non-nil/non-zero extra argument at index 1:
	<*errors.StatusError>: &errors.StatusError{ErrStatus:v1.Status{TypeMeta:v1.TypeMeta{Kind:"Status", APIVersion:"v1"}, ListMeta:v1.ListMeta{SelfLink:"", ResourceVersion:"", Continue:"", RemainingItemCount:(*int64)(nil)}, Status:"Failure", Message:"Unauthorized", Reason:"Unauthorized", Details:(*v1.StatusDetails)(nil), Code:401}}
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:174
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should delete successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:177
Unexpected error:
    <*errors.StatusError | 0xc0002f3220>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Unauthorized",
            Reason: "Unauthorized",
            Details: nil,
            Code: 401,
        },
    }
    Unauthorized
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:179
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction Should create deleteManagedClusterAction successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:229
Failed to create managedclusteractions
Unexpected error:
    <*errors.StatusError | 0xc0002f3ae0>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Unauthorized",
            Reason: "Unauthorized",
            Details: nil,
            Code: 401,
        },
    }
    Unauthorized
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:238
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction deployment should be deleted successfully in managedcluster

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:267
Timed out after 300.000s.
Error: Unexpected non-nil/non-zero extra argument at index 1:
	<*errors.StatusError>: &errors.StatusError{ErrStatus:v1.Status{TypeMeta:v1.TypeMeta{Kind:"Status", APIVersion:"v1"}, ListMeta:v1.ListMeta{SelfLink:"", ResourceVersion:"", Continue:"", RemainingItemCount:(*int64)(nil)}, Status:"Failure", Message:"Unauthorized", Reason:"Unauthorized", Details:(*v1.StatusDetails)(nil), Code:401}}
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:270
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should delete successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:273
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.5.5()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:274 +0x76
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000001b00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000001b00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should get successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:241
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.5.2()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:242 +0x82
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000001b00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000001b00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should have a valid condition

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:247
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.5.3.1(0x0, 0x0, 0x0, 0x0)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:249 +0x79
reflect.Value.call(0x21282e0, 0xc0006b4410, 0x13, 0x2414025, 0x4, 0xc000848f68, 0x0, 0x0, 0x21282e0, 0x2, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x21282e0, 0xc0006b4410, 0x13, 0xc000848f68, 0x0, 0x0, 0xc000060800, 0xc0000506d8, 0xc00004e000)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000a02980, 0xc0000b0820, 0x354d020, 0xc193fb, 0xc000849028)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000a02980, 0x2668218, 0xc0006b4430, 0xc19b01, 0x0, 0x0, 0x0, 0xc0006b4430)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000a02980, 0x2668218, 0xc0006b4430, 0x0, 0x0, 0x0, 0x2647d70)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.5.3()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:264 +0x143
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000001b00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000001b00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction Should create udateManagedClusterAction successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:184
Failed to create managedclusteractions
Unexpected error:
    <*errors.StatusError | 0xc0000c40a0>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Unauthorized",
            Reason: "Unauthorized",
            Details: nil,
            Code: 401,
        },
    }
    Unauthorized
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:193
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should delete successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:222
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.4.4()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:223 +0x76
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000001b00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000001b00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should get successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:196
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.4.2()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:197 +0x82
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000001b00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000001b00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should have a valid condition

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:202
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.4.3.1(0x0, 0x0, 0x0, 0x0)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:204 +0x79
reflect.Value.call(0x21282e0, 0xc00064be80, 0x13, 0x2414025, 0x4, 0xc000848f68, 0x0, 0x0, 0x21282e0, 0x2, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x21282e0, 0xc00064be80, 0x13, 0xc000848f68, 0x0, 0x0, 0xc000061c00, 0xc000052ed8, 0xc000050800)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0005c7480, 0xc000502eb0, 0x354d020, 0xc193fb, 0xc000849028)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0005c7480, 0x2668218, 0xc00064be90, 0xc19b01, 0x0, 0x0, 0x0, 0xc00064be90)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0005c7480, 0x2668218, 0xc00064be90, 0x0, 0x0, 0x0, 0x2647d70)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.4.3()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:219 +0x143
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000001b00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000001b00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

