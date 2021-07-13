# :warning: Had some failures when running regression on cluster ocp4-azgov-3 with test snapshot 2.3.0-SNAPSHOT-2021-07-13-04-59-11 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/232/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.16

Hub Cluster: https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com

Managed Cluster Version: 4.7.19

Managed Cluster: https://console-openshift-console.apps.dh-az4.acm-dev06.azure.devcluster.openshift.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107130709/

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
| :white_check_mark: | passed | Testing ClusterView to watch managedClusterSets should watch the managedClusterSets.clusterView successfully |
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
| :white_check_mark: | passed | Testing ManagedClusterAction when agent is lost Creating a ManagedClusterAction Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterInfo Delete ManagedClusterInfo Automatically after ManagedCluster is deleted clusterInfo should be deleted automatically. |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should get a ManagedClusterInfo successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have a valid condition |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have node list reported successfully in cluster |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid ClusterID |
| :white_check_mark: | passed | Testing ManagedClusterInfo Get ManagedClusterInfo should have valid distributionInfo |
| :x: | failed | Testing ManagedClusterSet clusterClaim and clusterDeployment should be added into managedClusterSet automatically. clusterClaim and clusterDeployment should be added into managedClusterSet automatically. |
| :x: | failed | Testing ManagedClusterSet managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted |
| :white_check_mark: | passed | Testing ManagedClusterSet managedCluster clusterRoleBinding should be created/updated automatically. managedCluster clusterRoleBinding should be updated successfully |
| :x: | failed | Testing ManagedClusterSet managedCluster namespace roleBinding should be created/updated automatically. managedCluster namespace roleBinding should be auto created successfully |
| :white_check_mark: | passed | Testing ManagedClusterSet managedClusterSet admin/view clusterRole should be created/deleted automatically. managedClusterSet admin/view clusterRole should be created/deleted automatically |
| :white_check_mark: | passed | Testing ManagedClusterView if agent is lost Creating a managedClusterView Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterView if agent is ok Creating a managedClusterView Should create successfully |
| :x: | failed | Testing Pod log should get log from pod successfully |
| :x: | failed | Testing user create/update managedCluster with mangedClusterSet label should create and update the managedCluster successfully |
| :x: | failed | Testing user create/update managedCluster without mangedClusterSet label should create and update the managedCluster successfully |
| :white_check_mark: | passed | Testing webhook cert rotation should create and update the managedCluster after cert rotation successfully |


---

### Failed Test Details

#### :x: Testing ClusterClaim should sync the label to claim

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterclaim_test.go:93
Timed out after 300.001s.
Unexpected error:
    <*errors.StatusError | 0xc0003e81e0>: {
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
    <*errors.StatusError | 0xc00028d5e0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"managedclustermutators.admission.cluster.open-cluster-management.io\": Post \"https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s\": context deadline exceeded",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"managedclustermutators.admission.cluster.open-cluster-management.io\": Post \"https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s\": context deadline exceeded",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "managedclustermutators.admission.cluster.open-cluster-management.io": Post "https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s": context deadline exceeded
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterview_test.go:100
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

#### :x: Testing ManagedClusterSet clusterClaim and clusterDeployment should be added into managedClusterSet automatically. clusterClaim and clusterDeployment should be added into managedClusterSet automatically.

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:47
Unexpected error:
    <*errors.StatusError | 0xc0003e8320>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"managedclustermutators.admission.cluster.open-cluster-management.io\": Post \"https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s\": context deadline exceeded",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"managedclustermutators.admission.cluster.open-cluster-management.io\": Post \"https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s\": context deadline exceeded",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "managedclustermutators.admission.cluster.open-cluster-management.io": Post "https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s": context deadline exceeded
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:58
```

#### :x: Testing ManagedClusterSet managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted managedCluster clusterRoleBinding and namespace roleBinding should be deleted successfully after managedClusterSet is deleted

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:47
Unexpected error:
    <*errors.StatusError | 0xc00070a280>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"managedclustermutators.admission.cluster.open-cluster-management.io\": Post \"https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s\": context deadline exceeded",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"managedclustermutators.admission.cluster.open-cluster-management.io\": Post \"https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s\": context deadline exceeded",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "managedclustermutators.admission.cluster.open-cluster-management.io": Post "https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s": context deadline exceeded
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:58
```

#### :x: Testing ManagedClusterSet managedCluster namespace roleBinding should be created/updated automatically. managedCluster namespace roleBinding should be auto created successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/clusterset_test.go:183
Timed out after 300.000s.
Unexpected error:
    <*errors.StatusError | 0xc00009cc80>: {
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
Timed out after 300.002s.
Unexpected error:
    <*errors.StatusError | 0xc0003e9220>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server rejected our request for an unknown reason (get clusterstatuses.proxy.open-cluster-management.io dh-az4)",
            Reason: "BadRequest",
            Details: {
                Name: "dh-az4",
                Group: "proxy.open-cluster-management.io",
                Kind: "clusterstatuses",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "pods \"klusterlet-5d9756f6c9-q27j6\" not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 400,
        },
    }
    the server rejected our request for an unknown reason (get clusterstatuses.proxy.open-cluster-management.io dh-az4)
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/log_test.go:93
```

#### :x: Testing user create/update managedCluster with mangedClusterSet label should create and update the managedCluster successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/webhook_test.go:116
Timed out after 301.044s.
Expected
    <*errors.errorString | 0xc0000ac370>: {
        s: "Internal error occurred: failed calling webhook \"managedclustermutators.admission.cluster.open-cluster-management.io\": Post \"https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s\": context deadline exceeded",
    }
to equal
    <*errors.errorString | 0xc0000ac730>: {
        s: "admission webhook \"ocm.validating.webhook.admission.open-cluster-management.io\" denied the request: user \"zpl226\" cannot add/remove the resource to/from ManagedClusterSet \"wrong-clusterSet\"",
    }
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/webhook_test.go:142
```

#### :x: Testing user create/update managedCluster without mangedClusterSet label should create and update the managedCluster successfully

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/webhook_test.go:54
Timed out after 302.083s.
Unexpected error:
    <*errors.StatusError | 0xc0006d61e0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "Internal error occurred: failed calling webhook \"managedclustermutators.admission.cluster.open-cluster-management.io\": Post \"https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s\": context deadline exceeded",
            Reason: "InternalError",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "",
                        Message: "failed calling webhook \"managedclustermutators.admission.cluster.open-cluster-management.io\": Post \"https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s\": context deadline exceeded",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 500,
        },
    }
    Internal error occurred: failed calling webhook "managedclustermutators.admission.cluster.open-cluster-management.io": Post "https://kubernetes.default.svc:443/apis/admission.cluster.open-cluster-management.io/v1/managedclustermutators?timeout=10s": context deadline exceeded
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/webhook_test.go:59
```

