# :warning: Had some failures when running regression on cluster ocp49-interop with test snapshot 2.4.0-SNAPSHOT-2021-09-13-14-40-25 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/vincent-test/1/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-0.nightly-2021-09-01-193941

Hub Cluster: https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com

Managed Cluster Version: 4.9.0-0.nightly-2021-09-01-193941

Managed Cluster: https://console-openshift-console.apps.ocp49-interop.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202109141718/

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
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should delete deployment |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should delete namespace |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should validate deployment was deleted |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Local Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should validate namespace was deleted |
| :x: | failed | RHACKM4K-726: Search: Search in Managed Cluster search resource: verify delete function in search result "after all" hook for "[P2][Sev2][observability-usa] should validate namespace was deleted" |
| :x: | failed | RHACKM4K-726: Search: Search in Managed Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should delete deployment |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Managed Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should delete namespace |
| :white_check_mark: | passed | RHACKM4K-726: Search: Search in Managed Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should validate deployment was deleted |
| :white_check_mark: | passed | RHACM4K-1233: Search: Search in Local Cluster prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-1233: Search: Search in Local Cluster search resources: verify create resource in search [P2][Sev2][observability-usa] should have link to resource creation page |
| :white_check_mark: | passed | RHACM4K-1233: Search: Search in Local Cluster search resources: verify create resource in search [P2][Sev2][observability-usa] should load the search page |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: saved searches function [P2][Sev2][observability-usa] should be able to find the saved searches |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: saved searches function [P2][Sev2][observability-usa] should be able to find the saved searches after logging back in |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: saved searches function [P2][Sev2][observability-usa] should be able to save current search |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: saved searches function [P2][Sev2][observability-usa] should find each managed cluster has default namespace |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: saved searches function [P2][Sev2][observability-usa] should find open-cluster-management-agent namespace exists |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: saved searches function [P2][Sev2][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-1262 - Search: multiple managedclusters base tests verify: saved searches function [P2][Sev2][observability-usa] should logout |
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
| :white_check_mark: | passed | RHACM4K-1574: Search: Search in Local Cluster search resources: verify edit yaml function and scale resources [P2][Sev2][observability-usa] should delete pod |
| :white_check_mark: | passed | RHACM4K-1574: Search: Search in Local Cluster search resources: verify edit yaml function and scale resources [P3][Sev3][observability-usa] should edit yaml and scale deployment |
| :white_check_mark: | passed | RHACM4K-1574: Search: Search in Local Cluster search resources: verify edit yaml function and scale resources [P3][Sev3][observability-usa] should verify that the deployment scaled |
| :x: | failed | RHACM4K-1574: Search: Search in Managed Cluster search resources: verify edit yaml function and scale resources "after all" hook for "[P3][Sev3][observability-usa] should verify that the deployment scaled" |
| :x: | failed | RHACM4K-1574: Search: Search in Managed Cluster search resources: verify edit yaml function and scale resources [P2][Sev2][observability-usa] should delete pod |
| :x: | failed | RHACM4K-1574: Search: Search in Managed Cluster search resources: verify edit yaml function and scale resources [P3][Sev3][observability-usa] should edit yaml and scale deployment |
| :x: | failed | RHACM4K-1574: Search: Search in Managed Cluster search resources: verify edit yaml function and scale resources [P3][Sev3][observability-usa] should verify that the deployment scaled |
| :x: | failed | RHACM4K-1695: Search - verify managed cluster info in the search page [P1][Sev1][observability-usa] Search - verify managed cluster info in the search page. |
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
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates verify: overview page link to search page [P3][Sev3][observability-usa] should load the overview page |
| :white_check_mark: | passed | RHACM4K-411: Search: Verify the suggested search templates verify: overview page link to search page [P3][Sev3][observability-usa] should navigate to Search page by clicking the search icon on the top right corner of the ACM console |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to delete the saved search open-cluster-management-agent search |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to delete the saved searches default namespace search |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to edit the saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to find the saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to revert back the edited saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches verify: saved searches resource actions [P2][Sev2][observability-usa] should be able to share the saved searches |
| :white_check_mark: | passed | RHACM4K-413: Search: Linked page prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-413: Search: Linked page verify: cluster page link to search page [P1][Sev1][observability-usa] should load the cluster page |
| :white_check_mark: | passed | RHACM4K-413: Search: Linked page verify: cluster page link to search page [P2][Sev2][observability-usa] clusters page should have link to search page |
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
| :white_check_mark: | passed | RHACM4K-537: Search: Search using filters prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-912: Search: Verify the managed cluster info in the search page prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should load the search page |
| :white_check_mark: | passed | RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should validate the endpoint version for the managed clusters are accurate |
| :x: | failed | RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should verify endpoint pods are all in running state |
| :x: | failed | RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should verify the yaml information is correct and there are no errors in the logs |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in kube-system on imported cluster. |
| :x: | failed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on imported cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on imported cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions prereq: create resource with oc command and login [P1][Sev1][observability-usa] should create namespace and application |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions prereq: create resource with oc command and login [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions verify: search result with common filter and conditions [P2][Sev2][observability-usa] should find expected application and delete application |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod. |
| :white_check_mark: | passed | Search: Create resource in Local Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should create deployment resource |
| :white_check_mark: | passed | Search: Create resource in Local Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should create namespace resource |
| :white_check_mark: | passed | Search: Create resource in Local Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should log into local cluster |
| :white_check_mark: | passed | Search: Create resource in Managed Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should create deployment resource |
| :white_check_mark: | passed | Search: Create resource in Managed Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should create namespace resource |
| :x: | failed | Search: Create resource in Managed Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should log into managed cluster |
| :white_check_mark: | passed | Search: Search in Local Cluster prereq: user should log into the ACM console [P1][Sev1][observability-usa] should login |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources: verify resource deployment pod logs [P2][Sev2][observability-usa] should see pod logs |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources: verify resource exist after creation [P1][Sev1][observability-usa] should work kind filter for deployment |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources: verify resource exist after creation [P1][Sev1][observability-usa] should work kind filter for pod |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources: verify resource exist after creation [P3][Sev3][observability-usa] should have expected count of relationships |
| :x: | failed | Search: Search in Managed Cluster search resources: verify resource deployment pod logs "after all" hook for "[P2][Sev2][observability-usa] should see pod logs" |
| :x: | failed | Search: Search in Managed Cluster search resources: verify resource deployment pod logs [P2][Sev2][observability-usa] should see pod logs |
| :x: | failed | Search: Search in Managed Cluster search resources: verify resource exist after creation "after all" hook for "[P1][Sev1][observability-usa] should work kind filter for pod" |
| :x: | failed | Search: Search in Managed Cluster search resources: verify resource exist after creation [P1][Sev1][observability-usa] should work kind filter for deployment |
| :x: | failed | Search: Search in Managed Cluster search resources: verify resource exist after creation [P1][Sev1][observability-usa] should work kind filter for pod |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources: verify resource exist after creation [P3][Sev3][observability-usa] should have expected count of relationships |


---

### Failed Test Details

#### :x: RHACKM4K-726: Search: Search in Managed Cluster search resource: verify delete function in search result "after all" hook for "[P2][Sev2][observability-usa] should validate namespace was deleted"

```
CypressError: `cy.exec('oc login --server=https://api.undefined:6443 -u undefined -p undefined --insecure-skip-tls-verify')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
error: dial tcp: lookup api.undefined on 8.8.8.8:53: no such host - verify you have provided the correct host and port and that the server is currently running.

https://on.cypress.io/exec

Because this error occurred during a `after all` hook we are skipping the remaining tests in the current suite: `search resource: verify del...`

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:142378:26
    at tryCatcher (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Object.login (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/05-delete/01-delete-resources.spec.js:180:8)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/05-delete/01-delete-resources.spec.js:300:30)
```

#### :x: RHACKM4K-726: Search: Search in Managed Cluster search resource: verify delete function in search result [P2][Sev2][observability-usa] should delete deployment

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `tr`, but never found it.
    at Object.whenGetResourceTableRow (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/05-delete/01-delete-resources.spec.js:447:15)
    at Object.whenDeleteResourceDetailItem (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/05-delete/01-delete-resources.spec.js:453:16)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/05-delete/01-delete-resources.spec.js:305:28)
```

#### :x: RHACM4K-1574: Search: Search in Managed Cluster search resources: verify edit yaml function and scale resources "after all" hook for "[P3][Sev3][observability-usa] should verify that the deployment scaled"

```
CypressError: `cy.exec('oc login --server=https://api.undefined:6443 -u undefined -p undefined --insecure-skip-tls-verify')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
error: dial tcp: lookup api.undefined on 8.8.8.8:53: no such host - verify you have provided the correct host and port and that the server is currently running.

https://on.cypress.io/exec

Because this error occurred during a `after all` hook we are skipping the remaining tests in the current suite: `RHACM4K-1574: Search: Searc...`

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:142378:26
    at tryCatcher (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Object.login (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:180:8)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:284:28)
```

#### :x: RHACM4K-1574: Search: Search in Managed Cluster search resources: verify edit yaml function and scale resources [P2][Sev2][observability-usa] should delete pod

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `tr`, but never found it.
    at Object.whenGetResourceTableRow (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:493:15)
    at Object.whenDeleteResourceDetailItem (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:499:16)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:310:28)
```

#### :x: RHACM4K-1574: Search: Search in Managed Cluster search resources: verify edit yaml function and scale resources [P3][Sev3][observability-usa] should edit yaml and scale deployment

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `tr`, but never found it.
    at Object.whenGetResourceTableRow (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:493:15)
    at Object.whenGoToResourceDetailItemPage (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:511:16)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:317:28)
```

#### :x: RHACM4K-1574: Search: Search in Managed Cluster search resources: verify edit yaml function and scale resources [P3][Sev3][observability-usa] should verify that the deployment scaled

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `tr`, but never found it.
    at Object.whenGetResourceTableRow (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:493:15)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-edit/01-scale.spec.js:324:28)
```

#### :x: RHACM4K-1695: Search - verify managed cluster info in the search page [P1][Sev1][observability-usa] Search - verify managed cluster info in the search page.

```
TypeError: Cannot read property 'ManagedClusterJoined' of undefined
    at Object.<anonymous> (/tests/api/search.test.js:38:51)
    at processTicksAndRejections (internal/process/task_queues.js:93:5)
```

#### :x: RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should verify endpoint pods are all in running state

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `[data-label="Status"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/11-managed/01-verify-managed-cluster.spec.js:510:41)
```

#### :x: RHACM4K-912: Search: Verify the managed cluster info in the search page verify: managed cluster resource endpoint [P3][Sev3][observability-usa] should verify the yaml information is correct and there are no errors in the logs

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `[data-label="Status"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/11-managed/01-verify-managed-cluster.spec.js:510:41)
```

#### :x: RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm on hub cluster.

```
Error: expect(received).toEqual(expected) // deep equality

Expected: "53"
Received: "52"
    at Object.<anonymous> (/tests/api/search.test.js:395:36)
    at processTicksAndRejections (internal/process/task_queues.js:93:5)
```

#### :x: Search: Create resource in Managed Cluster prereq: create resource with oc command [P1][Sev1][observability-usa] should log into managed cluster

```
CypressError: `cy.exec('oc login --server=https://api.undefined:6443 -u undefined -p undefined --insecure-skip-tls-verify')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
error: dial tcp: lookup api.undefined on 8.8.8.8:53: no such host - verify you have provided the correct host and port and that the server is currently running.

https://on.cypress.io/exec
    at https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:142378:26
    at tryCatcher (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Object.login (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/05-delete/01-delete-resources.spec.js:180:8)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/05-delete/01-delete-resources.spec.js:188:23)
```

#### :x: Search: Search in Managed Cluster search resources: verify resource deployment pod logs "after all" hook for "[P2][Sev2][observability-usa] should see pod logs"

```
CypressError: `cy.exec('oc login --server=https://api.undefined:6443 -u undefined -p undefined --insecure-skip-tls-verify')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
error: dial tcp: lookup api.undefined on 8.8.8.8:53: no such host - verify you have provided the correct host and port and that the server is currently running.

https://on.cypress.io/exec

Because this error occurred during a `after all` hook we are skipping the remaining tests in the current suite: `Search: Search in Managed C...`

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:142378:26
    at tryCatcher (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Object.login (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/02-pod-logs.spec.js:180:8)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/02-pod-logs.spec.js:284:28)
```

#### :x: Search: Search in Managed Cluster search resources: verify resource deployment pod logs [P2][Sev2][observability-usa] should see pod logs

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `tr`, but never found it.
    at Object.whenGetResourceTableRow (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/02-pod-logs.spec.js:441:15)
    at Object.whenGoToResourceDetailItemPage (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/02-pod-logs.spec.js:459:16)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/02-pod-logs.spec.js:310:28)
```

#### :x: Search: Search in Managed Cluster search resources: verify resource exist after creation "after all" hook for "[P1][Sev1][observability-usa] should work kind filter for pod"

```
CypressError: `cy.exec('oc login --server=https://api.undefined:6443 -u undefined -p undefined --insecure-skip-tls-verify')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
error: dial tcp: lookup api.undefined on 8.8.8.8:53: no such host - verify you have provided the correct host and port and that the server is currently running.

https://on.cypress.io/exec

Because this error occurred during a `after all` hook we are skipping the remaining tests in the current suite: `Search: Search in Managed C...`

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:142378:26
    at tryCatcher (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Object.login (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/01-search.spec.js:180:8)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/01-search.spec.js:282:28)
```

#### :x: Search: Search in Managed Cluster search resources: verify resource exist after creation [P1][Sev1][observability-usa] should work kind filter for deployment

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `tr`, but never found it.
    at Object.whenGetResourceTableRow (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/01-search.spec.js:449:15)
    at Object.shouldFindResourceDetailItem (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/01-search.spec.js:582:16)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/01-search.spec.js:317:28)
```

#### :x: Search: Search in Managed Cluster search resources: verify resource exist after creation [P1][Sev1][observability-usa] should work kind filter for pod

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `tr`, but never found it.
    at Object.whenGetResourceTableRow (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/01-search.spec.js:449:15)
    at Object.shouldFindResourceDetailItem (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/01-search.spec.js:582:16)
    at Context.eval (https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-search/01-search.spec.js:322:28)
```

