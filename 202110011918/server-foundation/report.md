# :warning: Had some failures when running regression on cluster ocp-rosa-4 with test snapshot 2.4.0-SNAPSHOT-2021-09-30-03-17-33 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/278/


ACM Version: v2.4.0

Hub Cluster Version: 4.8.11

Hub Cluster: https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com

Managed Cluster Version: v1.21.1+9807387

Managed Cluster: https://console-openshift-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110011918/

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
| :white_check_mark: | passed | Testing ClusterView to get managedClusterSets should list the managedClusterSets.clusterView successfully |
| :white_check_mark: | passed | Testing ClusterView to get managedClusters should list the managedClusters.clusterview successfully |
| :white_check_mark: | passed | Testing ClusterView to watch managedClusterSets should watch the managedClusterSets.clusterView successfully |
| :white_check_mark: | passed | Testing ClusterView to watch managedClusters should watch the managedClusters.clusterview successfully |
| :large_blue_circle: | skipped | Testing Lease Get Lease should get/update lease successfully in cluster |
| :white_check_mark: | passed | Testing ManagedCluster Get ManagedCluster cpu worker capacity should get a cpu_worker successfully in status of managedcluster |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from apiserver |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from configmap |
| :x: | failed | Testing ManagedCluster Testing Clusterca sync Get CA from service account |
| :white_check_mark: | passed | Testing ManagedClusterAction when Agent is ok Creating a CreateManagedClusterAction deployment should be created successfully in managedcluster |
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
| :white_check_mark: | passed | Testing ManagedClusterView if agent is lost Creating a managedClusterView Should create successfully |
| :white_check_mark: | passed | Testing ManagedClusterView if agent is ok Creating a managedClusterView Should create successfully |
| :white_check_mark: | passed | Testing Pod log should get log from pod successfully |
| :white_check_mark: | passed | Testing user create/update managedCluster with mangedClusterSet label should create and update the managedCluster successfully |
| :white_check_mark: | passed | Testing user create/update managedCluster without mangedClusterSet label should create and update the managedCluster successfully |
| :white_check_mark: | passed | Testing webhook cert rotation should create and update the managedCluster after cert rotation successfully |


---

### Failed Test Details

#### :x: Testing ManagedCluster Testing Clusterca sync Get CA from apiserver

```
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:37
Unexpected error:
    <*errors.StatusError | 0xc000318a00>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "admission webhook \"regular-user-validation.managed.openshift.io\" denied the request: Prevented from accessing Red Hat managed resources. This is in an effort to prevent harmful actions that may cause unintended consequences or affect the stability of the cluster. If you have any questions about this, please reach out to Red Hat support at https://access.redhat.com/support",
            Reason: "Prevented from accessing Red Hat managed resources. This is in an effort to prevent harmful actions that may cause unintended consequences or affect the stability of the cluster. If you have any questions about this, please reach out to Red Hat support at https://access.redhat.com/support",
            Details: nil,
            Code: 403,
        },
    }
    admission webhook "regular-user-validation.managed.openshift.io" denied the request: Prevented from accessing Red Hat managed resources. This is in an effort to prevent harmful actions that may cause unintended consequences or affect the stability of the cluster. If you have any questions about this, please reach out to Red Hat support at https://access.redhat.com/support
occurred
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:71
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
Timed out after 300.001s.
Expected
    <bool>: false
to be true
/go/src/github.com/open-cluster-management/multicloud-operators-foundation/test/e2e/managedcluster_test.go:157
```

