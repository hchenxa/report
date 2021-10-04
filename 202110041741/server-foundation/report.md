# :warning: Had some failures when running regression on cluster qe1-vmware-pkt with test snapshot 2.4.0-SNAPSHOT-2021-10-02-11-10-03 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/287/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-rc.1

Hub Cluster: https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com

Managed Cluster Version: 4.9.0-rc.4

Managed Cluster: https://console-openshift-console.apps.qe4-vmware-pkt.dev02.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110041741/

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
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from apiserver |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from configmap |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from service account |
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
| :white_check_mark: | passed | Testing ManagedClusterAction when agent is lost Creating a ManagedClusterAction Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterImageRegistry add / remove imageRegistry label successfully |
| :white_check_mark: | passed | Testing ManagedClusterInfo Delete ManagedClusterInfo Automatically after ManagedCluster is deleted clusterInfo should be deleted automatically. |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should get a ManagedClusterInfo successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have a valid condition |
| :x: | failed | Testing ManagedClusterInfo Get ManagedClusterInfo should have node list reported successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid ClusterID |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid distributionInfo |
| :x: | failed | Testing ManagedClusterSet clusterClaim and clusterDeployment should be added into managedClusterSet automatically. clusterClaim and clusterDeployment should be added into managedClusterSet automatically. |
| :x: | failed | Testing ManagedClusterSet clusterdeployment clusterset should be synced with managedcluster. clusterdeployment clusterset should be synced with managedcluster automatically. |
| :x: | failed | Testing ManagedClusterSet clusterdeployment clusterset should be synced with managedcluster. update managedcluster clusterset, clusterdeployment clusterset should be synced automatically. |
| :x: | failed | Testing ManagedClusterSet it should fail when updating clusterpool and managedcluster clusterset. try to update clusterpool clusterset label, and it should fail. |
| :x: | failed | Testing ManagedClusterSet it should fail when updating clusterpool and managedcluster clusterset. try to update managedcluster clusterset label, and it should fail. |
| :x: | failed | Testing ManagedClusterSet managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted |
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
Timed out after 300.000s.
Unexpected error:
    <*errors.StatusError | 0xc0009481e0>: {
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

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from apiserver

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:37
Timed out after 300.001s.
Expected
    <bool>: false
to be true
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:89
```

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from configmap

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:99
Timed out after 300.000s.
Expected
    <bool>: false
to be true
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:129
```

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from service account

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:136
Timed out after 300.002s.
Expected
    <bool>: false
to be true
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:157
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

#### :x: Testing ManagedClusterInfo Get ManagedClusterInfo should have node list reported successfully in cluster

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterinfos_test.go:22
Timed out after 300.001s.
Unexpected error:
    <*errors.errorString | 0xc0007d1a30>: {
        s: "failed to get nodeList. found:false, err:<nil>",
    }
    failed to get nodeList. found:false, err:<nil>
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterinfos_test.go:30
```

#### :x: Testing ManagedClusterSet clusterClaim and clusterDeployment should be added into managedClusterSet automatically. clusterClaim and clusterDeployment should be added into managedClusterSet automatically.

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:251
Unexpected error:
    <*errors.StatusError | 0xc0000277c0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "clusterdeploymentvalidators.admission.hive.openshift.io": the server is currently unable to handle the request
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:270
```

#### :x: Testing ManagedClusterSet clusterdeployment clusterset should be synced with managedcluster. clusterdeployment clusterset should be synced with managedcluster automatically.

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:466
Unexpected error:
    <*errors.StatusError | 0xc00065d400>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "clusterdeploymentvalidators.admission.hive.openshift.io": the server is currently unable to handle the request
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:468
```

#### :x: Testing ManagedClusterSet clusterdeployment clusterset should be synced with managedcluster. update managedcluster clusterset, clusterdeployment clusterset should be synced automatically.

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:466
Unexpected error:
    <*errors.StatusError | 0xc000135b80>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "clusterdeploymentvalidators.admission.hive.openshift.io": the server is currently unable to handle the request
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:468
```

#### :x: Testing ManagedClusterSet it should fail when updating clusterpool and managedcluster clusterset. try to update clusterpool clusterset label, and it should fail.

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:520
Unexpected error:
    <*errors.StatusError | 0xc000814640>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "clusterdeploymentvalidators.admission.hive.openshift.io": the server is currently unable to handle the request
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:535
```

#### :x: Testing ManagedClusterSet it should fail when updating clusterpool and managedcluster clusterset. try to update managedcluster clusterset label, and it should fail.

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:520
Unexpected error:
    <*errors.StatusError | 0xc00041c280>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "clusterdeploymentvalidators.admission.hive.openshift.io": the server is currently unable to handle the request
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:535
```

#### :x: Testing ManagedClusterSet managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:369
Unexpected error:
    <*errors.StatusError | 0xc000948000>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"clusterdeploymentvalidators.admission.hive.openshift.io\": the server is currently unable to handle the request",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "clusterdeploymentvalidators.admission.hive.openshift.io": the server is currently unable to handle the request
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:388
```

#### :x: Testing ManagedClusterSet managedCluster namespace roleBinding should be created/updated automatically. managedCluster namespace roleBinding should be auto created successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:49
Unexpected error:
    <*errors.StatusError | 0xc000789220>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Operation cannot be fulfilled on managedclusters.cluster.open-cluster-management.io \"test-automation-vdg44f\": the object has been modified; please apply your changes to the latest version and try again",
            Reason: "Conflict",
            Details: {
                Name: "test-automation-vdg44f",
                Group: "cluster.open-cluster-management.io",
                Kind: "managedclusters",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 409,
        },
    }
    Operation cannot be fulfilled on managedclusters.cluster.open-cluster-management.io "test-automation-vdg44f": the object has been modified; please apply your changes to the latest version and try again
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:70
```

#### :x: Testing Pod log should get log from pod successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/log_test.go:71
Timed out after 300.001s.
Unexpected error:
    <*errors.StatusError | 0xc000579040>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server rejected our request for an unknown reason (get clusterstatuses.proxy.open-cluster-management.io qe4-vmware-pkt)",
            Reason: "BadRequest",
            Details: {
                Name: "qe4-vmware-pkt",
                Group: "proxy.open-cluster-management.io",
                Kind: "clusterstatuses",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "pods \"klusterlet-addon-appmgr-d8cff889b-95rzn\" not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 400,
        },
    }
    the server rejected our request for an unknown reason (get clusterstatuses.proxy.open-cluster-management.io qe4-vmware-pkt)
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/log_test.go:93
```

