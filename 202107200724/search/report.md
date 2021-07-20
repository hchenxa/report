# :warning: Had some failures when running regression on cluster ocp4-edge-bm-h29-0 with test snapshot 2.3.0-SNAPSHOT-2021-07-15-17-21-39 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/237/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.16

Hub Cluster: https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com

Managed Cluster Version: 4.7.16

Managed Cluster: https://console-openshift-console.apps.ocp4-edge-bm-h29-1.qe.lab.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107200724/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-731[P1][Sev1][observability-usa] Login: search-e2e-admin-cluster user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-731[P1][Sev1][observability-usa] Logout: search-e2e-admin-cluster user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-731[P2][Sev2][observability-usa] As an user with name search-e2e-admin-cluster with cluster-role-binding of default admin role, the user can read the Overview page. |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-919[P1][Sev1][observability-usa] Login: search-e2e-view-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-919[P1][Sev1][observability-usa] Logout: search-e2e-view-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-919[P2][Sev2][observability-usa] As an user with name search-e2e-view-ns with ns-role-binding of default view role, the user can read the Overview page. |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-920[P1][Sev1][observability-usa] Login: search-e2e-edit-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-920[P1][Sev1][observability-usa] Logout: search-e2e-edit-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-920[P2][Sev2][observability-usa] As an user with name search-e2e-edit-ns with ns-role-binding of default edit role, the user can read the Overview page. |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-921[P1][Sev1][observability-usa] Login: search-e2e-admin-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-921[P1][Sev1][observability-usa] Logout: search-e2e-admin-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-921[P2][Sev2][observability-usa] As an user with name search-e2e-admin-ns with ns-role-binding of default admin role, the user can read the Overview page. |
| :white_check_mark: | passed | RHACM4K-1695: Search - verify managed cluster info in the search page [P1][Sev1][observability-usa] Search - verify managed cluster info in the search page. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind application on specific namespace. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod and namespace open-cluster-management. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod on specific cluster. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:certpolicycontroller. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:iampolicycontroller. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Verify a deleted pod is recreated. |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by active |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apigroup |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apiversion |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by architecture |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by available |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by capacity |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by claimRef |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cluster |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by clusterIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by completions |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by consoleURL |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by container |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cpu |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by created |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by current |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by desired |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by hostIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by kubernetesVersion |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by lastSchedule |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by memory |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by nodes |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by osImage |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by parallelism |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by podIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by port |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by ready |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by reclaimPolicy |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by request |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by restarts |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by startedAt |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by successful |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by suspend |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by type |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by updated |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by volumeName |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the created last hour template & search tag in search items |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the unhealthy pods template & search tag in search items |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the workloads template & search tag in search items |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to edit the saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to find the saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to revert back the edited saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to save current search |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to share the saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should find each managed cluster has default namespace |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should find open-cluster-management-agent namespace exists |
| :white_check_mark: | passed | RHACM4K-413: Search: Linked page [P1][Sev1][observability-usa] should load the cluster page |
| :white_check_mark: | passed | RHACM4K-413: Search: Linked page [P2][Sev2][observability-usa] clusters page should have link to search page |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by combination with "next suggestion" value and "label" filter with "next suggestion" value |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by combination with "next suggestion" value and "name" filter with "next suggestion" value |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by multiple values |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by next suggestion |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should suggest values |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "label" filter should filter by next suggestion |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "label" filter should suggest values |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "name" filter should filter by next suggestion |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "name" filter should suggest values |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by master |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by multiple values |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by worker |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should suggest values |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should filter by multiple values |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should filter by next suggestion |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should suggest values |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P1][Sev1][observability-usa] should create namespace and application |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P2][Sev2][observability-usa] should find expected application and delete application |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in kube-system on imported cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on imported cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on imported cluster. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod. |
| :white_check_mark: | passed | Search: Overview page [P1][Sev1][observability-usa] should load the overview page |
| :x: | failed | Search: Overview page [P2][Sev2][observability-usa] add cloud connection action works |
| :white_check_mark: | passed | Search: Overview page [P2][Sev2][observability-usa] should have link to resource creation page |
| :white_check_mark: | passed | Search: Overview page [P2][Sev2][observability-usa] should have link to search page |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should load the search page |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that deployment resource exist |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that namespace resource exist |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for deployment |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for pod |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete deployment |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete namespace |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete pod |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should see pod logs |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should validate deployment was deleted |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should validate namespace was deleted |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should have expected count of relationships |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should scale deployment |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should verify that the deployment scaled |


---

### Failed Test Details

#### :x: Search: Overview page [P2][Sev2][observability-usa] add cloud connection action works

```
AssertionError: Timed out retrying after 10000ms: expected '/multicloud/credentials' to include 'add-connection'
    at Object.whenAddProviderConnectionAction (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/07-overview/01-overview-page.spec.js:176:68)
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/07-overview/01-overview-page.spec.js:145:28)
```

