# :warning: Had some failures when running regression on cluster ocp4-gcp-2 with test snapshot 2.2.6-SNAPSHOT-2021-07-24-01-04-04 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/254/


ACM Version: v2.2.6

Hub Cluster Version: 4.7.21

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-2.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.2

Managed Cluster: https://console-openshift-console.apps.acmqe-22-ocp4-gcp-2-aws-hive.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202108050148/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | RHACM4K-1695: Search - verify managed cluster info in the search page Search - verify managed cluster info in the search page. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind application on specific namespace. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod and namespace open-cluster-management. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod on specific cluster. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:certpolicycontroller. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:iampolicycontroller. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Verify a deleted pod is recreated. |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by active |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by apigroup |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by apiversion |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by architecture |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by available |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by capacity |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by claimRef |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by cluster |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by clusterIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by completions |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by consoleURL |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by container |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by cpu |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by created |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by current |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by desired |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by hostIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by kubernetesVersion |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by lastSchedule |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by memory |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by nodes |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by osImage |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by parallelism |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by podIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by port |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by ready |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by reclaimPolicy |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by request |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by restarts |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by startedAt |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by successful |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by suspend |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by type |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by updated |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by volumeName |
| :white_check_mark: | passed | Search API: Validate autocomplete [P3][Sev3][observability-usa][PLACEHOLDER] This test not yet implemented. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod. |
| :white_check_mark: | passed | Search: Linked page [P2][Sev2][observability-usa] clusters page should has link to search page |
| :white_check_mark: | passed | Search: Linked page [P2][Sev2][observability-usa] overview page should has link to search page |
| :white_check_mark: | passed | Search: Overview page [P1][Sev1][observability-usa] should load |
| :white_check_mark: | passed | Search: Saved searches [P2][Sev2][observability-usa] should be able to find the saved searches |
| :white_check_mark: | passed | Search: Saved searches [P2][Sev2][observability-usa] should be able to save current search |
| :white_check_mark: | passed | Search: Saved searches [P2][Sev2][observability-usa] should find each managed cluster has default namespace |
| :white_check_mark: | passed | Search: Saved searches [P2][Sev2][observability-usa] should find open-cluster-management-agent namespace exists |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should create deployment from create resource UI |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should create namespace from create resource UI |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should load the search page |
| :x: | failed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should not see any cluster and namespace |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that deployment resource exist |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that namespace already exist |
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
| :white_check_mark: | passed | Search: Search in Managed Cluster [P1][Sev1][observability-usa] should create deployment from create resource UI |
| :white_check_mark: | passed | Search: Search in Managed Cluster [P1][Sev1][observability-usa] should create namespace from create resource UI |
| :white_check_mark: | passed | Search: Search in Managed Cluster [P1][Sev1][observability-usa] should load the search page |
| :white_check_mark: | passed | Search: Search in Managed Cluster [P1][Sev1][observability-usa] should not see any cluster and namespace |
| :white_check_mark: | passed | Search: Search in Managed Cluster [P1][Sev1][observability-usa] should verify that deployment resource exist |
| :white_check_mark: | passed | Search: Search in Managed Cluster [P1][Sev1][observability-usa] should verify that namespace already exist |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P1][Sev1][observability-usa] should work kind filter for deployment |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P1][Sev1][observability-usa] should work kind filter for pod |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P2][Sev2][observability-usa] should delete deployment |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P2][Sev2][observability-usa] should delete namespace |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P2][Sev2][observability-usa] should delete pod |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P2][Sev2][observability-usa] should see pod logs |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P2][Sev2][observability-usa] should validate deployment was deleted |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P2][Sev2][observability-usa] should validate namespace was deleted |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P3][Sev3][observability-usa] should have expected count of relationships |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P3][Sev3][observability-usa] should scale deployment |
| :white_check_mark: | passed | Search: Search in Managed Cluster search resources [P3][Sev3][observability-usa] should verify that the deployment scaled |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by combination with "next suggestion" value and "label" filter with "next suggestion" value |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by combination with "next suggestion" value and "name" filter with "next suggestion" value |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by multiple values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by next suggestion |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should suggest values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "label" filter should filter by next suggestion |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "label" filter should suggest values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "name" filter should filter by next suggestion |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "name" filter should suggest values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by master |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by multiple values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by worker |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should suggest values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should filter by multiple values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should filter by next suggestion |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should suggest values |
| :white_check_mark: | passed | Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the created last hour template & search tag in search items |
| :white_check_mark: | passed | Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the unhealthy pods template & search tag in search items |
| :white_check_mark: | passed | Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the workloads template & search tag in search items |


---

### Failed Test Details

#### :x: Search: Search in Local Cluster [P1][Sev1][observability-usa] should not see any cluster and namespace

```
AssertionError: Timed out retrying: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.ocp4-gcp-2.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1625:21)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.ocp4-gcp-2.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1646:17)
    at Object.whenFilterByCluster (https://multicloud-console.apps.ocp4-gcp-2.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1653:15)
    at Object.whenFilterByClusterAndNamespace (https://multicloud-console.apps.ocp4-gcp-2.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1656:15)
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-2.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1084:25)
```

