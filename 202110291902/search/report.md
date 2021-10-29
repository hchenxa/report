# :warning: Had some failures when running regression on cluster ocp4-az-01 with test snapshot 2.4.0-SNAPSHOT-2021-10-29-15-11-27 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/393/


ACM Version: v2.4.0

Hub Cluster Version: 4.6.46

Hub Cluster: https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.9.0

Managed Cluster: https://console-openshift-console.apps.acmqe-24-rc-hive-ansible-az2.acm-dev06.azure.devcluster.openshift.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110291902/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-731 - verify: read action for user search-e2e-admin-cluster with admin role [P1][Sev1][observability-usa] Login: search-e2e-admin-cluster user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-731 - verify: read action for user search-e2e-admin-cluster with admin role [P1][Sev1][observability-usa] Logout: search-e2e-admin-cluster user |
| :x: | failed | RBAC users to read the Overview page RHACM4K-731 - verify: read action for user search-e2e-admin-cluster with admin role [P2][Sev2][observability-usa] As an user with name search-e2e-admin-cluster with cluster-role-binding of default admin role, the user can read the Overview page. |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-919 - verify: read action for user search-e2e-view-ns with view role [P1][Sev1][observability-usa] Login: search-e2e-view-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-919 - verify: read action for user search-e2e-view-ns with view role [P1][Sev1][observability-usa] Logout: search-e2e-view-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-919 - verify: read action for user search-e2e-view-ns with view role [P2][Sev2][observability-usa] As an user with name search-e2e-view-ns with ns-role-binding of default view role, the user can read the Overview page. |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-920 - verify: read action for user search-e2e-edit-ns with edit role [P1][Sev1][observability-usa] Login: search-e2e-edit-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-920 - verify: read action for user search-e2e-edit-ns with edit role [P1][Sev1][observability-usa] Logout: search-e2e-edit-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-920 - verify: read action for user search-e2e-edit-ns with edit role [P2][Sev2][observability-usa] As an user with name search-e2e-edit-ns with ns-role-binding of default edit role, the user can read the Overview page. |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-921 - verify: read action for user search-e2e-admin-ns with admin role [P1][Sev1][observability-usa] Login: search-e2e-admin-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-921 - verify: read action for user search-e2e-admin-ns with admin role [P1][Sev1][observability-usa] Logout: search-e2e-admin-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-921 - verify: read action for user search-e2e-admin-ns with admin role [P2][Sev2][observability-usa] As an user with name search-e2e-admin-ns with ns-role-binding of default admin role, the user can read the Overview page. |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should delete deployment |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should delete namespace |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should validate deployment was deleted |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should validate namespace was deleted |
| :white_check_mark: | passed | RHACM4K-1233: Search: Search in Local Cluster prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-1233: Search: Search in Local Cluster search resources: verify create resource in search [P2][Sev2][observability-usa] should have link to resource creation page |
| :white_check_mark: | passed | RHACM4K-1233: Search: Search in Local Cluster search resources: verify create resource in search [P2][Sev2][observability-usa] should load the search page |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: multicluster managed base [P2][Sev2][observability-usa] should be able to find the saved searches |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: multicluster managed base [P2][Sev2][observability-usa] should be able to find the saved searches after logging back in |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: multicluster managed base [P2][Sev2][observability-usa] should be able to save current search |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: multicluster managed base [P2][Sev2][observability-usa] should find each managed cluster has default namespace |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: multicluster managed base [P2][Sev2][observability-usa] should find open-cluster-management-agent namespace exists |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: multicluster managed base [P2][Sev2][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: multicluster managed base [P2][Sev2][observability-usa] should logout |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page link validation [P2][Sev2][observability-usa] should have link to application page from left nav |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page link validation [P2][Sev2][observability-usa] should have link to automation page from left nav |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page link validation [P2][Sev2][observability-usa] should have link to bare metal assets page from left nav |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page link validation [P2][Sev2][observability-usa] should have link to cluster page from left nav |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page link validation [P2][Sev2][observability-usa] should have link to credential page from left nav |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page link validation [P2][Sev2][observability-usa] should have link to governance page from left nav |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page link validation [P2][Sev2][observability-usa] should have link to resource creation page |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page link validation [P2][Sev2][observability-usa] should have link to welcome page from left nav |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page validation [P1][Sev1][observability-usa] should load the overview page |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page validation [P2][Sev2][observability-usa] add cloud connection action works |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page validation [P2][Sev2][observability-usa] should have clusters provider card |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page validation [P2][Sev2][observability-usa] should have clusters summary breakdown |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page validation [P2][Sev2][observability-usa] should have link to search page |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page UI - overview page validation [P2][Sev2][observability-usa] should have refresh options |
| :white_check_mark: | passed | RHACM4K-1419: Search: Overview page prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-1574: Search: Search in Local Cluster prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :x: | failed | RHACM4K-1574: Search: Search in Local Cluster search resources: verify edit yaml function and scale resources [P2][Sev2][observability-usa] should delete pod |
| :white_check_mark: | passed | RHACM4K-1574: Search: Search in Local Cluster search resources: verify edit yaml function and scale resources [P3][Sev3][observability-usa] should edit yaml and scale deployment |
| :white_check_mark: | passed | RHACM4K-1574: Search: Search in Local Cluster search resources: verify edit yaml function and scale resources [P3][Sev3][observability-usa] should verify that the deployment scaled |
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
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates verify: overview page link to search page [P3][Sev3][observability-usa] should load the overview page |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates verify: overview page link to search page [P3][Sev3][observability-usa] should navigate to Search page by clicking the search icon on the top right corner of the ACM console |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates verify: search page suggested search queries [P3][Sev3][observability-usa] should see the created last hour template & search tag in search items |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates verify: search page suggested search queries [P3][Sev3][observability-usa] should see the unhealthy pods template & search tag in search items |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates verify: search page suggested search queries [P3][Sev3][observability-usa] should see the workloads template & search tag in search items |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches prereq: user should log into the ACM console [P1][Sev1][observability-usa] should create namespace |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to delete the saved searches auto-test-app-1635535009538-ns-search |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to edit the saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to find the saved search |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to revert back the edited saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to save current search |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to share the saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should verify that the namespace is available |
| :white_check_mark: | passed | RHACM4K-413: Search: Linked page prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-413: Search: Linked page verify: cluster page link to search page [P1][Sev1][observability-usa] should load the cluster page |
| :white_check_mark: | passed | RHACM4K-413: Search: Linked page verify: cluster page link to search page [P2][Sev2][observability-usa] clusters page should have link to search page |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters verify: broad spectrum of search result [P1][Sev1][observability-usa] Search using "kind" filter |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters verify: broad spectrum of search result [P1][Sev1][observability-usa] Search using "label" filter |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters verify: broad spectrum of search result [P1][Sev1][observability-usa] Search using "name" filter |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters verify: broad spectrum of search result [P1][Sev1][observability-usa] Search using "role" filter |
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters verify: broad spectrum of search result [P1][Sev1][observability-usa] Search using "status" filter |
| :white_check_mark: | passed | RHACM4K-912: Search: Verify the managed cluster info in the search page prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should load the search page |
| :white_check_mark: | passed | RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should validate the endpoint version for the managed clusters are accurate |
| :white_check_mark: | passed | RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should verify endpoint pods are all in running state |
| :white_check_mark: | passed | RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should verify the yaml information is correct and there are no errors in the logs |
| :white_check_mark: | passed | RHACM4K-913: Search - Verify search results with different queries [P3][Sev3][observability-usa] should have expected count of pods in kube-system on imported cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - Verify search results with different queries [P3][Sev3][observability-usa] should have expected count of pods in ocm on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - Verify search results with different queries [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - Verify search results with different queries [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on imported cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - Verify search results with different queries [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - Verify search results with different queries [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on imported cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions prereq: create resource with oc command and log into the ACM console [P1][Sev1][observability-usa] should create namespace and application |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions prereq: create resource with oc command and log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions verify: search result with common filter and conditions [P2][Sev2][observability-usa] should find expected application and delete application |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod. |
| :white_check_mark: | passed | Search: Create resource in Local Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should create deployment resource |
| :white_check_mark: | passed | Search: Create resource in Local Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should create namespace resource |
| :white_check_mark: | passed | Search: Create resource in Local Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should log into local cluster |
| :white_check_mark: | passed | Search: Search in Local Cluster prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources: verify resource deployment pod logs [P2][Sev2][observability-usa] should see pod logs |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources: verify resource exist after creation [P1][Sev1][observability-usa] should work kind filter for deployment |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources: verify resource exist after creation [P1][Sev1][observability-usa] should work kind filter for pod |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources: verify resource exist after creation [P3][Sev3][observability-usa] should have expected count of relationships |


---

### Failed Test Details

#### :x: RBAC users to read the Overview page RHACM4K-731 - verify: read action for user search-e2e-admin-cluster with admin role [P2][Sev2][observability-usa] As an user with name search-e2e-admin-cluster with cluster-role-binding of default admin role, the user can read the Overview page.

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-expandable-section__toggle-text`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/12-rbac/01-view-overview-with-rbacuser.spec.js:234:22)
```

#### :x: RHACM4K-1574: Search: Search in Local Cluster search resources: verify edit yaml function and scale resources [P2][Sev2][observability-usa] should delete pod

```
Error: command reloaduntil exeeded timeout: 30000
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:8227:11)
```

