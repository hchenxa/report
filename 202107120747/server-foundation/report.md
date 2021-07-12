# :warning: Had some failures when running regression on cluster slot-00 with test snapshot 2.3.0-SNAPSHOT-2021-07-12-03-45-43 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/225/


ACM Version: v2.3.0

Hub Cluster Version: 4.8.0-rc.1

Hub Cluster: https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.0-rc.3

Managed Cluster: https://console-openshift-console.apps.slot-04.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107120747/

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
| :x: | failed | Testing ClusterView to watch managedClusterSets should watch the managedClusterSets.clusterView successfully |
| :white_check_mark: | passed | Testing ClusterView to watch managedClusters should watch the managedClusters.clusterview successfully |
| :large_blue_circle: | skipped | Testing Lease Get Lease should get/update lease successfully in cluster |
| :white_check_mark: | passed | Testing ManagedCluster Get ManagedCluster cpu worker capacity should get a cpu_worker successfully in status of managedcluster |
| :x: | failed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction deployment should be created successfully in managedcluster |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should delete successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should get successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction Should create deleteManagedClusterAction successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction deployment should be deleted successfully in managedcluster |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should delete successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should get successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist Should create deleteManagedCusterAction successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist deployment should be deleted successfully in managedcluster |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should delete successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should get successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a DeleteManagedClusterAction when resource do not exist should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction Should create udateManagedClusterAction successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should delete successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should get successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist Should create updateManagedClusterAction successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should delete successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should get successfully |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a UpdateManagedClusterAction when resource do not exist should have a valid condition |
| :x: | failed | Testing ManagedClusterAction when agent is lost Creating a ManagedClusterAction Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterInfo Delete ManagedClusterInfo Automatically after ManagedCluster is deleted clusterInfo should be deleted automatically. |
| :x: | failed | Testing ManagedClusterInfo Get ManagedClusterInfo should get a ManagedClusterInfo successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have node list reported successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid ClusterID |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid distributionInfo |
| :white_check_mark: | passed | Testing ManagedClusterSet clusterClaim and clusterDeployment should be added into managedClusterSet automatically. clusterClaim and clusterDeployment should be added into managedClusterSet automatically. |
| :white_check_mark: | passed | Testing ManagedClusterSet managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted |
| :white_check_mark: | passed | Testing ManagedClusterSet managedCluster clusterRoleBinding should be created/updated automatically. managedCluster clusterRoleBinding should be updated successfully |
| :white_check_mark: | passed | Testing ManagedClusterSet managedCluster namespace roleBinding should be created/updated automatically. managedCluster namespace roleBinding should be auto created successfully |
| :white_check_mark: | passed | Testing ManagedClusterSet managedClusterSet admin/view clusterRole should be created/deleted automatically. managedClusterSet admin/view clusterRole should be created/deleted automatically |
| :white_check_mark: | passed | Testing ManagedClusterView if agent is lost Creating a managedClusterView Should create successfully |
| :x: | failed | Testing ManagedClusterView if agent is ok Creating a managedClusterView Should create successfully |
| :x: | failed | Testing Pod log should get log from pod successfully |
| :white_check_mark: | passed | Testing user create/update managedCluster with mangedClusterSet label should create and update the managedCluster successfully |
| :white_check_mark: | passed | Testing user create/update managedCluster without mangedClusterSet label should create and update the managedCluster successfully |
| :x: | failed | Testing webhook cert rotation should create and update the managedCluster after cert rotation successfully |


---

### Failed Test Details

#### :x: Testing ClusterClaim should sync the label to claim

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterclaim_test.go:93
Timed out after 300.001s.
Unexpected error:
    <*errors.StatusError | 0xc000640960>: {
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
    <*errors.StatusError | 0xc000302460>: {
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
    <*errors.StatusError | 0xc000460b40>: {
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

#### :x: Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction deployment should be created successfully in managedcluster

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:171
Timed out after 300.001s.
Expected
    <bool>: false
to be true
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:174
```

#### :x: Testing ManagedClusterAction when agent is lost Creating a ManagedClusterAction Should create successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:288
Unexpected error:
    <*errors.StatusError | 0xc0006d8e60>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/actions_test.go:290
```

#### :x: Testing ManagedClusterInfo Get ManagedClusterInfo should get a ManagedClusterInfo successfully in cluster

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterinfos_test.go:20
Timed out after 300.000s.
Expected
    <bool>: false
to be true
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterinfos_test.go:27
```

#### :x: Testing ManagedClusterView if agent is ok Creating a managedClusterView Should create successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/views_test.go:26
Failed to create managedclusterviews
Unexpected error:
    <*errors.StatusError | 0xc0005bf400>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/views_test.go:33
```

#### :x: Testing Pod log should get log from pod successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/log_test.go:26
Timed out after 60.000s.
Expected
    <bool>: false
to be true
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/log_test.go:49
```

#### :x: Testing webhook cert rotation should create and update the managedCluster after cert rotation successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/webhook_test.go:211
Timed out after 300.002s.
Unexpected error:
    <*errors.StatusError | 0xc00013b4a0>: {
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
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/webhook_test.go:232
```

