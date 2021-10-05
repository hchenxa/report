# :warning: Had some failures when running regression on cluster ocp-rosa-4 with test snapshot 2.4.0-SNAPSHOT-2021-10-02-11-10-03 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/295/


ACM Version: v2.4.0

Hub Cluster Version: 4.8.11

Hub Cluster: https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com

Managed Cluster Version: v1.21.1+9807387

Managed Cluster: https://console-openshift-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110042210/

## Tests:

|Status|Results|Test|
|---|---|---|
| :large_blue_circle: | skipped | Testing BareMetalAsset Create bma BMA should be auto created successfully |
| :large_blue_circle: | skipped | Testing BareMetalAsset Deleting a ClusterDeployment delete clusterdeployment should clean ref in bma |
| :white_check_mark: | passed | Testing ClusterClaim should get the required ClusterClaims successfully the managed cluster |
| :white_check_mark: | passed | Testing ClusterClaim should not remove the customized claim |
| :white_check_mark: | passed | Testing ClusterClaim should recreate the ClusterClaim once it is deleted |
| :white_check_mark: | passed | Testing ClusterClaim should rollback the change of the ClusterClaim once it is modified |
| :white_check_mark: | passed | Testing ClusterClaim should sync the label to claim |
| :x: | failed | Testing ClusterView to get managedClusterSets should list the managedClusterSets.clusterView successfully |
| :x: | failed | Testing ClusterView to get managedClusters should list the managedClusters.clusterview successfully |
| :x: | failed | Testing ClusterView to watch managedClusterSets should watch the managedClusterSets.clusterView successfully |
| :x: | failed | Testing ClusterView to watch managedClusters should watch the managedClusters.clusterview successfully |
| :large_blue_circle: | skipped | Testing Lease Get Lease should get/update lease successfully in cluster |
| :white_check_mark: | passed | Testing ManagedCluster Get ManagedCluster cpu worker capacity should get a cpu_worker successfully in status of managedcluster |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from apiserver |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from configmap |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from service account |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction deployment should be created successfully in managedcluster |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should create successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should delete successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should get successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should have a valid condition |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction Should create deleteManagedClusterAction successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction deployment should be deleted successfully in managedcluster |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should delete successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should get successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should have a valid condition |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist Should create deleteManagedCusterAction successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist deployment should be deleted successfully in managedcluster |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should delete successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should get successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should have a valid condition |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction Should create udateManagedClusterAction successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should delete successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should get successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should have a valid condition |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist Should create updateManagedClusterAction successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should delete successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should get successfully |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterAction when agent is lost Creating a ManagedClusterAction Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterImageRegistry add / remove imageRegistry label successfully |
| :white_check_mark: | passed | Testing ManagedClusterInfo Delete ManagedClusterInfo Automatically after ManagedCluster is deleted clusterInfo should be deleted automatically. |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should get a ManagedClusterInfo successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have node list reported successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid ClusterID |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid distributionInfo |
| :white_check_mark: | passed | Testing ManagedClusterSet clusterClaim and clusterDeployment should be added into managedClusterSet automatically. clusterClaim and clusterDeployment should be added into managedClusterSet automatically. |
| :white_check_mark: | passed | Testing ManagedClusterSet clusterdeployment clusterset should be synced with managedcluster. clusterdeployment clusterset should be synced with managedcluster automatically. |
| :white_check_mark: | passed | Testing ManagedClusterSet clusterdeployment clusterset should be synced with managedcluster. update managedcluster clusterset, clusterdeployment clusterset should be synced automatically. |
| :white_check_mark: | passed | Testing ManagedClusterSet it should fail when updating clusterpool and managedcluster clusterset. try to update clusterpool clusterset label, and it should fail. |
| :white_check_mark: | passed | Testing ManagedClusterSet it should fail when updating clusterpool and managedcluster clusterset. try to update managedcluster clusterset label, and it should fail. |
| :white_check_mark: | passed | Testing ManagedClusterSet managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted |
| :white_check_mark: | passed | Testing ManagedClusterSet managedCluster clusterRoleBinding should be created/updated automatically. managedCluster clusterRoleBinding should be updated successfully |
| :white_check_mark: | passed | Testing ManagedClusterSet managedCluster namespace roleBinding should be created/updated automatically. managedCluster namespace roleBinding should be auto created successfully |
| :white_check_mark: | passed | Testing ManagedClusterSet managedClusterSet admin/view clusterRole should be created/deleted automatically. managedClusterSet admin/view clusterRole should be created/deleted automatically |
| :x: | failed | Testing ManagedClusterView if agent is lost Creating a managedClusterView Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterView if agent is ok Creating a managedClusterView Should create successfully |
| :white_check_mark: | passed | Testing Pod log should get log from pod successfully |
| :white_check_mark: | passed | Testing user create/update managedCluster with mangedClusterSet label should create and update the managedCluster successfully |
| :white_check_mark: | passed | Testing user create/update managedCluster without mangedClusterSet label should create and update the managedCluster successfully |
| :white_check_mark: | passed | Testing webhook cert rotation should create and update the managedCluster after cert rotation successfully |


---

### Failed Test Details

#### :x: Testing ClusterView to get managedClusterSets should list the managedClusterSets.clusterView successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:298
Unexpected error:
    <*errors.StatusError | 0xc00026d540>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:305
```

#### :x: Testing ClusterView to get managedClusters should list the managedClusters.clusterview successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:82
Unexpected error:
    <*errors.StatusError | 0xc00078bd60>: {
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

#### :x: Testing ClusterView to watch managedClusterSets should watch the managedClusterSets.clusterView successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:432
Unexpected error:
    <*errors.StatusError | 0xc0005481e0>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:439
```

#### :x: Testing ClusterView to watch managedClusters should watch the managedClusters.clusterview successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:218
Unexpected error:
    <*errors.StatusError | 0xc00026c6e0>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:225
```

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from apiserver

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:37
Unexpected error:
    <*errors.StatusError | 0xc000548f00>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "secrets \"fake-server-secret\" already exists",
            Reason: "AlreadyExists",
            Details: {
                Name: "fake-server-secret",
                Group: "",
                Kind: "secrets",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 409,
        },
    }
    secrets "fake-server-secret" already exists
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:45
```

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from configmap

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:99
Unexpected error:
    <*errors.errorString | 0xc0003151f0>: {
        s: "unexpected error when reading response body. Please retry. Original error: read tcp 10.0.11.123:50688->44.198.203.242:6443: read: connection reset by peer",
    }
    unexpected error when reading response body. Please retry. Original error: read tcp 10.0.11.123:50688->44.198.203.242:6443: read: connection reset by peer
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:118
```

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from service account

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:136
Unexpected error:
    <*errors.StatusError | 0xc0005494a0>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:142
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction deployment should be created successfully in managedcluster

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:171
Timed out after 300.001s.
Error: Unexpected non-nil/non-zero extra argument at index 1:
	<*errors.StatusError>: &errors.StatusError{ErrStatus:v1.Status{TypeMeta:v1.TypeMeta{Kind:"Status", APIVersion:"v1"}, ListMeta:v1.ListMeta{SelfLink:"", ResourceVersion:"", Continue:"", RemainingItemCount:(*int64)(nil)}, Status:"Failure", Message:"Unauthorized", Reason:"Unauthorized", Details:(*v1.StatusDetails)(nil), Code:401}}
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:174
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should create successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:133
Failed to create managedclusteractions
Unexpected error:
    <*errors.StatusError | 0xc0003e0e60>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:142
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should delete successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:177
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.3.5()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:178 +0x76
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should get successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:145
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.3.2()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:146 +0x82
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should have a valid condition

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:151
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.3.3.1(0x0, 0x0, 0x0, 0x0)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:153 +0x79
reflect.Value.call(0x21282e0, 0xc000315740, 0x13, 0x2414025, 0x4, 0xc000a06f68, 0x0, 0x0, 0x21282e0, 0x2, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x21282e0, 0xc000315740, 0x13, 0xc000a06f68, 0x0, 0x0, 0xc000500000, 0xc00004e6d8, 0xc00004c000)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0007a5080, 0xc000281c20, 0x354d020, 0xc193fb, 0xc000a07028)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0007a5080, 0x2668218, 0xc000315750, 0xc19b01, 0x0, 0x0, 0x0, 0xc000315750)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0007a5080, 0x2668218, 0xc000315750, 0x0, 0x0, 0x0, 0x2647d70)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.3.3()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:168 +0x143
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction Should create deleteManagedClusterAction successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:229
Failed to create managedclusteractions
Unexpected error:
    <*errors.StatusError | 0xc00066e640>: {
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
Timed out after 300.001s.
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
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
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
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
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
reflect.Value.call(0x21282e0, 0xc00077d830, 0x13, 0x2414025, 0x4, 0xc000a06f68, 0x0, 0x0, 0x21282e0, 0x2, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x21282e0, 0xc00077d830, 0x13, 0xc000a06f68, 0x0, 0x0, 0xc000090400, 0xc000055ed8, 0xc000053800)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc00043b9c0, 0xc00063fa40, 0x354d020, 0xc193fb, 0xc000a07028)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc00043b9c0, 0x2668218, 0xc00077d840, 0xc19b01, 0x0, 0x0, 0x0, 0xc00077d840)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc00043b9c0, 0x2668218, 0xc00077d840, 0x0, 0x0, 0x0, 0x2647d70)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.5.3()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:264 +0x143
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist Should create deleteManagedCusterAction successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:82
Failed to create managedclusteractions
Unexpected error:
    <*errors.StatusError | 0xc0005e2a00>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:91
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist deployment should be deleted successfully in managedcluster

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:120
Timed out after 300.000s.
Error: Unexpected non-nil/non-zero extra argument at index 1:
	<*errors.StatusError>: &errors.StatusError{ErrStatus:v1.Status{TypeMeta:v1.TypeMeta{Kind:"Status", APIVersion:"v1"}, ListMeta:v1.ListMeta{SelfLink:"", ResourceVersion:"", Continue:"", RemainingItemCount:(*int64)(nil)}, Status:"Failure", Message:"Unauthorized", Reason:"Unauthorized", Details:(*v1.StatusDetails)(nil), Code:401}}
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:123
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should delete successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:126
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.2.5()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:127 +0x76
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should get successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:94
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.2.2()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:95 +0x82
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should have a valid condition

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:100
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.2.3.1(0x0, 0x0, 0x0, 0x0)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:102 +0x79
reflect.Value.call(0x21282e0, 0xc0002b5360, 0x13, 0x2414025, 0x4, 0xc000a06f68, 0x0, 0x0, 0x21282e0, 0x2, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x21282e0, 0xc0002b5360, 0x13, 0xc000a06f68, 0x0, 0x0, 0xc000090000, 0xc00004e6d8, 0xc00004c000)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0008ee540, 0xc000906820, 0x354d020, 0xc193fb, 0xc000a07028)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0008ee540, 0x2668218, 0xc0002b5370, 0xc19b01, 0x0, 0x0, 0x0, 0xc0002b5370)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0008ee540, 0x2668218, 0xc0002b5370, 0x0, 0x0, 0x0, 0x2647d70)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.2.3()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:117 +0x143
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction Should create udateManagedClusterAction successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:184
Failed to create managedclusteractions
Unexpected error:
    <*errors.StatusError | 0xc0000e4d20>: {
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
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
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
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
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
reflect.Value.call(0x21282e0, 0xc0002b54d0, 0x13, 0x2414025, 0x4, 0xc000a06f68, 0x0, 0x0, 0x21282e0, 0x2, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x21282e0, 0xc0002b54d0, 0x13, 0xc000a06f68, 0x0, 0x0, 0xc00005ec00, 0xc000050ed8, 0xc00004e800)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0007a5700, 0xc0000eea00, 0x354d020, 0xc193fb, 0xc000a07028)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0007a5700, 0x2668218, 0xc0002b54e0, 0xc19b01, 0x0, 0x0, 0x0, 0xc0002b54e0)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0007a5700, 0x2668218, 0xc0002b54e0, 0x0, 0x0, 0x0, 0x2647d70)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.4.3()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:219 +0x143
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist Should create updateManagedClusterAction successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:37
Failed to create managedclusteractions
Unexpected error:
    <*errors.StatusError | 0xc0003e1220>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:46
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should delete successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:75
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.1.4()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:76 +0x76
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should get successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:49
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.1.2()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:50 +0x82
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should have a valid condition

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:55
Test Panicked
/usr/local/go/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
k8s.io/apimachinery/pkg/apis/meta/v1/unstructured.(*Unstructured).GetName(...)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured/unstructured.go:246
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.1.3.1(0x0, 0x0, 0x0, 0x0)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:57 +0x79
reflect.Value.call(0x21282e0, 0xc000984510, 0x13, 0x2414025, 0x4, 0xc000a06f68, 0x0, 0x0, 0x21282e0, 0x2, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x21282e0, 0xc000984510, 0x13, 0xc000a06f68, 0x0, 0x0, 0xc000090400, 0xc0000536d8, 0xc000051000)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc00007d600, 0xc0007f05a0, 0x354d020, 0xc193fb, 0xc000a07028)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc00007d600, 0x2668218, 0xc000984530, 0xc19b01, 0x0, 0x0, 0x0, 0xc000984530)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc00007d600, 0x2668218, 0xc000984530, 0x0, 0x0, 0x0, 0x2647d70)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.1.3()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:72 +0x143
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc000092f00)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:32 +0x138
testing.tRunner(0xc000092f00, 0x24f47b0)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Testing ManagedClusterView if agent is lost Creating a managedClusterView Should create successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/views_test.go:70
Unexpected error:
    <*errors.StatusError | 0xc00078b720>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/views_test.go:72
```

