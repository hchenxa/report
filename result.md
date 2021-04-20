# :warning: 2.3.0-SNAPSHOT-2021-04-17-07-15-32 had some failures from TEST on CUSTOMER

## Job URL: No Job URL


Hub Cluster Version: customer

Import Cluster Version: ClusterClaim

Hub Cluster: http://envs.canary.cicd.red-chesterfield.com/#cluster-name-ImportClusterClaim

Manual Import Cluster: http://envs.canary.cicd.red-chesterfield.com/#cluster-name-hchentest

## Tests:

|Results|Test|
|---|---|
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted |
| :large_blue_circle: | Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :large_blue_circle: | Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana-dev/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability][Stable] Checking default value of PVC and StorageClass (config/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Modifying MCO cr to enable observabilityaddon |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have endpoint-operator and metrics-collector being deployed |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should not have the expected MCO addon pods when disable observabilityaddon |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Waiting for check no metric data in grafana console |
| :large_blue_circle: | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Integration] Modifying managedcluster cr to disable observability |
| :large_blue_circle: | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Integration] Modifying managedcluster cr to enable observability |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Deleting metrics-collector deployment |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Updating metrics-collector deployment |
| :x: | Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0) |
| :x: | Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Customize the replicas for thanos query (reconcile/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have metrics which defined in custom metrics allowlist (metricslist/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have no metrics after custom metrics allowlist deleted (metricslist/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0) |
| :white_check_mark: | Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |
| :white_check_mark: | Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0) |
| :x: | RHACM4K-412 - Search: Saved searches "after all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace" |
| :x: | RHACM4K-412 - Search: Saved searches "before all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace" |
| :x: | RHACM4K-913: Search - common filter and conditions "after all" hook for "[P1][Sev1][search] should create namespace and application" |
| :x: | RHACM4K-913: Search - common filter and conditions "before all" hook for "[P1][Sev1][search] should create namespace and application" |
| :x: | Search: Linked page "after all" hook for "[P2][Sev2][search] clusters page should have link to search page" |
| :x: | Search: Linked page "before all" hook for "[P2][Sev2][search] clusters page should have link to search page" |
| :x: | Search: Overview page "after all" hook for "[P1][Sev1][search] should load the overview page" |
| :x: | Search: Overview page "before all" hook for "[P1][Sev1][search] should load the overview page" |
| :x: | Search: Search in Local Cluster "after all" hook for "[P1][Sev1][search] should load the search page" |
| :x: | Search: Search in Local Cluster "before all" hook for "[P1][Sev1][search] should load the search page" |
| :x: | Search: Search using filters [P1][Sev1][search] Search using "name" filter "after all" hook for "should suggest values" |
| :x: | Search: Search using filters [P1][Sev1][search] Search using "name" filter "before all" hook for "should suggest values" |
| :x: | Search: Verify the suggested search templates "after all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items" |
| :x: | Search: Verify the suggested search templates "before all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items" |


---

### Failed Test Details

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:115
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc000a4bba0>: {
        s: "the storage size of statefulset observability-alertmanager should have 2Gi but got {{3221225472 0} {<nil>} 3Gi BinarySI}",
    }
    the storage size of statefulset observability-alertmanager should have 2Gi but got {{3221225472 0} {<nil>} 3Gi BinarySI}
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:123
```
                        
#### :x: Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:93
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0003b0830>: {
        s: "Failed to check node selector for pod: observability-alertmanager-0",
    }
    Failed to check node selector for pod: observability-alertmanager-0
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:101
```
                        
#### :x: RHACM4K-412 - Search: Saved searches "after all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```
                        
#### :x: RHACM4K-412 - Search: Saved searches "before all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions "after all" hook for "[P1][Sev1][search] should create namespace and application"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions "before all" hook for "[P1][Sev1][search] should create namespace and application"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Linked page "after all" hook for "[P2][Sev2][search] clusters page should have link to search page"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```
                        
#### :x: Search: Linked page "before all" hook for "[P2][Sev2][search] clusters page should have link to search page"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Overview page "after all" hook for "[P1][Sev1][search] should load the overview page"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```
                        
#### :x: Search: Overview page "before all" hook for "[P1][Sev1][search] should load the overview page"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Search in Local Cluster "after all" hook for "[P1][Sev1][search] should load the search page"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```
                        
#### :x: Search: Search in Local Cluster "before all" hook for "[P1][Sev1][search] should load the search page"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Search using filters [P1][Sev1][search] Search using "name" filter "after all" hook for "should suggest values"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```
                        
#### :x: Search: Search using filters [P1][Sev1][search] Search using "name" filter "before all" hook for "should suggest values"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Verify the suggested search templates "after all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```
                        
#### :x: Search: Verify the suggested search templates "before all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
