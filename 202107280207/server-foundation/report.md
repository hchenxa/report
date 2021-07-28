# :warning: Had some failures when running regression on cluster ocp4-aws-3 with test snapshot 2.3.0-SNAPSHOT-2021-07-26-18-43-26 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/245/


ACM Version: v2.3.0

Hub Cluster Version: 4.8.2

Hub Cluster: https://multicloud-console.apps.ocp4-aws-3.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.2

Managed Cluster: https://console-openshift-console.apps.acmqe-23-ocp4-aws-3-hive-azure.acm-dev06.azure.devcluster.openshift.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107280207/

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
| :white_check_mark: | passed | Testing ClusterView to get managedClusters should list the managedClusters.clusterview successfully |
| :white_check_mark: | passed | Testing ClusterView to watch managedClusterSets should watch the managedClusterSets.clusterView successfully |
| :white_check_mark: | passed | Testing ClusterView to watch managedClusters should watch the managedClusters.clusterview successfully |
| :large_blue_circle: | skipped | Testing Lease Get Lease should get/update lease successfully in cluster |
| :white_check_mark: | passed | Testing ManagedCluster Get ManagedCluster cpu worker capacity should get a cpu_worker successfully in status of managedcluster |
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
| :white_check_mark: | passed | Testing ManagedClusterAction when agent is lost Creating a ManagedClusterAction Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterInfo Delete ManagedClusterInfo Automatically after ManagedCluster is deleted clusterInfo should be deleted automatically. |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should get a ManagedClusterInfo successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have node list reported successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid ClusterID |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid distributionInfo |
| :white_check_mark: | passed | Testing ManagedClusterSet clusterClaim and clusterDeployment should be added into managedClusterSet automatically. clusterClaim and clusterDeployment should be added into managedClusterSet automatically. |
| :white_check_mark: | passed | Testing ManagedClusterSet managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted |
| :white_check_mark: | passed | Testing ManagedClusterSet managedCluster clusterRoleBinding should be created/updated automatically. managedCluster clusterRoleBinding should be updated successfully |
| :x: | failed | Testing ManagedClusterSet managedCluster namespace roleBinding should be created/updated automatically. managedCluster namespace roleBinding should be auto created successfully |
| :white_check_mark: | passed | Testing ManagedClusterSet managedClusterSet admin/view clusterRole should be created/deleted automatically. managedClusterSet admin/view clusterRole should be created/deleted automatically |
| :white_check_mark: | passed | Testing ManagedClusterView if agent is lost Creating a managedClusterView Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterView if agent is ok Creating a managedClusterView Should create successfully |
| :x: | failed | Testing Pod log should get log from pod successfully |
| :white_check_mark: | passed | Testing user create/update managedCluster with mangedClusterSet label should create and update the managedCluster successfully |
| :white_check_mark: | passed | Testing user create/update managedCluster without mangedClusterSet label should create and update the managedCluster successfully |
| :white_check_mark: | passed | Testing webhook cert rotation should create and update the managedCluster after cert rotation successfully |


---

### Failed Test Details

#### :x: Testing ClusterClaim should sync the label to claim

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterclaim_test.go:93
Timed out after 300.001s.
Unexpected error:
    <*errors.StatusError | 0xc00028d7c0>: {
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
    <*errors.StatusError | 0xc0000c41e0>: {
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
    <*errors.StatusError | 0xc0000c4960>: {
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
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc0004ba600)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:29 +0x138
testing.tRunner(0xc0004ba600, 0x1a12a88)
	/usr/local/go/src/testing/testing.go:1194 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1239 +0x2b3
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
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc0004ba600)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:29 +0x138
testing.tRunner(0xc0004ba600, 0x1a12a88)
	/usr/local/go/src/testing/testing.go:1194 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1239 +0x2b3
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
reflect.Value.call(0x16b1e60, 0xc0007f56f0, 0x13, 0x1944793, 0x4, 0xc0005dcfc0, 0x0, 0x0, 0x16b1e60, 0x2, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x16b1e60, 0xc0007f56f0, 0x13, 0xc0005dcfc0, 0x0, 0x0, 0x3045a1e90e479, 0xc0000506d8, 0xc00004e000)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0006f8fc0, 0xc000594960, 0x26a75c0, 0x3f, 0xc0005dd080)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0006f8fc0, 0x1b51598, 0xc0007f5700, 0x410101, 0x0, 0x0, 0x0, 0xc0007f5700)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0006f8fc0, 0x1b51598, 0xc0007f5700, 0x0, 0x0, 0x0, 0x1b34878)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.5.3()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:264 +0x143
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc0004ba600)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:29 +0x138
testing.tRunner(0xc0004ba600, 0x1a12a88)
	/usr/local/go/src/testing/testing.go:1194 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1239 +0x2b3
```

#### :x: Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction Should create udateManagedClusterAction successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:184
Failed to create managedclusteractions
Unexpected error:
    <*errors.StatusError | 0xc0003e6460>: {
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
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc0004ba600)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:29 +0x138
testing.tRunner(0xc0004ba600, 0x1a12a88)
	/usr/local/go/src/testing/testing.go:1194 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1239 +0x2b3
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
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc0004ba600)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:29 +0x138
testing.tRunner(0xc0004ba600, 0x1a12a88)
	/usr/local/go/src/testing/testing.go:1194 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1239 +0x2b3
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
reflect.Value.call(0x16b1e60, 0xc0006a04c0, 0x13, 0x1944793, 0x4, 0xc0005dcfc0, 0x0, 0x0, 0x16b1e60, 0x2, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x16b1e60, 0xc0006a04c0, 0x13, 0xc0005dcfc0, 0x0, 0x0, 0x3045a1d6ca98a, 0xc000052ed8, 0xc000050800)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000294840, 0xc00014e5a0, 0x26a75c0, 0x40fa9b, 0xc0005dd080)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000294840, 0x1b51598, 0xc0006a04d0, 0x410101, 0x0, 0x0, 0x0, 0xc0006a04d0)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000294840, 0x1b51598, 0xc0006a04d0, 0x0, 0x0, 0x0, 0x1b34878)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.glob..func1.4.3()
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:219 +0x143
github.com/open-cluster-management/multicloud-operators-foundation/test/e2e.TestE2E(0xc0004ba600)
	/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/e2e_suite_test.go:29 +0x138
testing.tRunner(0xc0004ba600, 0x1a12a88)
	/usr/local/go/src/testing/testing.go:1194 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1239 +0x2b3
```

#### :x: Testing ManagedClusterSet managedCluster namespace roleBinding should be created/updated automatically. managedCluster namespace roleBinding should be auto created successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:183
Timed out after 300.000s.
Unexpected error:
    <*errors.StatusError | 0xc0003e7a40>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "rolebindings.rbac.authorization.k8s.io \"open-cluster-management:managedclusterset:admin\" not found",
            Reason: "NotFound",
            Details: {
                Name: "open-cluster-management:managedclusterset:admin",
                Group: "rbac.authorization.k8s.io",
                Kind: "rolebindings",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    rolebindings.rbac.authorization.k8s.io "open-cluster-management:managedclusterset:admin" not found
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:188
```

#### :x: Testing Pod log should get log from pod successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/log_test.go:71
Timed out after 300.001s.
Unexpected error:
    <*errors.StatusError | 0xc00055ec80>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server rejected our request for an unknown reason (get clusterstatuses.proxy.open-cluster-management.io acmqe-23-ocp4-aws-3-hive-azure)",
            Reason: "BadRequest",
            Details: {
                Name: "acmqe-23-ocp4-aws-3-hive-azure",
                Group: "proxy.open-cluster-management.io",
                Kind: "clusterstatuses",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "pods \"klusterlet-6ccc9c9c5d-2k5mj\" not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 400,
        },
    }
    the server rejected our request for an unknown reason (get clusterstatuses.proxy.open-cluster-management.io acmqe-23-ocp4-aws-3-hive-azure)
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/log_test.go:93
```

