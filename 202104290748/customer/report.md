# :warning: 2.2.3-SNAPSHOT-2021-04-22-06-59-29 had some failures when running Regression on user environment

## Job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/79/


Hub Cluster Version: v2.2.3

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-2.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.7.8

Managed Cluster: https://console-openshift-console.apps.dhrpatel-2-2-3-team-hive-cluster.gcp.dev09.red-chesterfield.com

## Tests:

|Results|Test|
|---|---|
| :x: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Checking default value of PVC and StorageClass (config/g0) |
| :x: | Observability: [P1][Sev1][Observability] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Checking podAntiAffinity for all pods (reconcile/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Modifying MCO CR for reconciling (reconcile/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Modifying MCO cr to enable observabilityaddon |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Should have endpoint-operator and metrics-collector being deployed |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Should not have the expected MCO addon pods when disable observabilityaddon |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Waiting for check no metric data in grafana console |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Modifying retentionResolutionRaw (reconcile/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Revert MCO CR changes (reconcile/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should have custom alert generated (alert/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should have custom alert updated (alert/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should have metric data in grafana console (grafana/g0) |
| :large_blue_circle: | Observability: [P1][Sev1][Observability] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should have metrics which defined in custom metrics allowlist (metricslist/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should have no metrics after custom metrics allowlist deleted (metricslist/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should have the expected statefulsets (alert/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should modify the SECRET: alertmanager-config (alert/g0) |
| :large_blue_circle: | Observability: [P1][Sev1][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - Modifying managedcluster cr to disable observability |
| :large_blue_circle: | Observability: [P1][Sev1][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - Modifying managedcluster cr to enable observability |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should not set interval to values beyond scope (addon/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - Deleting metrics-collector deployment |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - Updating metrics-collector deployment |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - Updating observatorium cr (spec.rule.replicas) should be automatically reverted |
| :large_blue_circle: | Observability: [P1][Sev1][Observability] Should verify that the alerts are created (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Should delete the created configmap (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Should have the expected configmap (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Should have the expected secret (alert/g0) |
| :white_check_mark: | Observability: [P3][Sev3][Observability] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :white_check_mark: | Search: Linked page [P2][Sev2][search] clusters page should has link to search page |
| :white_check_mark: | Search: Linked page [P2][Sev2][search] overview page should has link to search page |
| :white_check_mark: | Search: Overview page [P1][Sev1][search] should load |
| :white_check_mark: | Search: Saved searches [P2][Sev2][search] should be able to find the saved searches |
| :white_check_mark: | Search: Saved searches [P2][Sev2][search] should be able to save current search |
| :white_check_mark: | Search: Saved searches [P2][Sev2][search] should find each managed cluster has default namespace |
| :white_check_mark: | Search: Saved searches [P2][Sev2][search] should find open-cluster-management-agent namespace exists |
| :white_check_mark: | Search: Search in Local Cluster [P1][Sev1][search] should create deployment from create resource UI |
| :white_check_mark: | Search: Search in Local Cluster [P1][Sev1][search] should create namespace from create resource UI |
| :white_check_mark: | Search: Search in Local Cluster [P1][Sev1][search] should load the search page |
| :white_check_mark: | Search: Search in Local Cluster [P1][Sev1][search] should not see any cluster and namespace |
| :white_check_mark: | Search: Search in Local Cluster [P1][Sev1][search] should verify that deployment resource exist |
| :white_check_mark: | Search: Search in Local Cluster [P1][Sev1][search] should verify that namespace already exist |
| :white_check_mark: | Search: Search in Local Cluster search resources [P1][Sev1][search] should work kind filter for deployment |
| :white_check_mark: | Search: Search in Local Cluster search resources [P1][Sev1][search] should work kind filter for pod |
| :white_check_mark: | Search: Search in Local Cluster search resources [P2][Sev2][search] should delete deployment |
| :white_check_mark: | Search: Search in Local Cluster search resources [P2][Sev2][search] should delete namespace |
| :white_check_mark: | Search: Search in Local Cluster search resources [P2][Sev2][search] should delete pod |
| :white_check_mark: | Search: Search in Local Cluster search resources [P2][Sev2][search] should see pod logs |
| :white_check_mark: | Search: Search in Local Cluster search resources [P2][Sev2][search] should validate deployment was deleted |
| :white_check_mark: | Search: Search in Local Cluster search resources [P2][Sev2][search] should validate namespace was deleted |
| :white_check_mark: | Search: Search in Local Cluster search resources [P3][Sev3][search] should have expected count of relationships |
| :white_check_mark: | Search: Search in Local Cluster search resources [P3][Sev3][search] should scale deployment |
| :white_check_mark: | Search: Search in Local Cluster search resources [P3][Sev3][search] should verify that the deployment scaled |
| :white_check_mark: | Search: Search in Managed Cluster [P1][Sev1][search] should create deployment from create resource UI |
| :white_check_mark: | Search: Search in Managed Cluster [P1][Sev1][search] should create namespace from create resource UI |
| :white_check_mark: | Search: Search in Managed Cluster [P1][Sev1][search] should load the search page |
| :white_check_mark: | Search: Search in Managed Cluster [P1][Sev1][search] should not see any cluster and namespace |
| :white_check_mark: | Search: Search in Managed Cluster [P1][Sev1][search] should verify that deployment resource exist |
| :white_check_mark: | Search: Search in Managed Cluster [P1][Sev1][search] should verify that namespace already exist |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P1][Sev1][search] should work kind filter for deployment |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P1][Sev1][search] should work kind filter for pod |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P2][Sev2][search] should delete deployment |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P2][Sev2][search] should delete namespace |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P2][Sev2][search] should delete pod |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P2][Sev2][search] should see pod logs |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P2][Sev2][search] should validate deployment was deleted |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P2][Sev2][search] should validate namespace was deleted |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P3][Sev3][search] should have expected count of relationships |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P3][Sev3][search] should scale deployment |
| :white_check_mark: | Search: Search in Managed Cluster search resources [P3][Sev3][search] should verify that the deployment scaled |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "kind" filter should filter by combination with "next suggestion" value and "label" filter with "next suggestion" value |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "kind" filter should filter by combination with "next suggestion" value and "name" filter with "next suggestion" value |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "kind" filter should filter by multiple values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "kind" filter should filter by next suggestion |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "kind" filter should suggest values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "label" filter should filter by next suggestion |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "label" filter should suggest values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "name" filter should filter by next suggestion |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "name" filter should suggest values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "role" filter should filter by master |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "role" filter should filter by multiple values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "role" filter should filter by worker |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "role" filter should suggest values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "status" filter should filter by multiple values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "status" filter should filter by next suggestion |
| :white_check_mark: | Search: Search using filters [P1][Sev1][search] Search using "status" filter should suggest values |
| :white_check_mark: | Search: Verify the suggested search templates [P3][Sev3][search] should see the created last hour template & search tag in search items |
| :white_check_mark: | Search: Verify the suggested search templates [P3][Sev3][search] should see the unhealthy pods template & search tag in search items |
| :white_check_mark: | Search: Verify the suggested search templates [P3][Sev3][search] should see the workloads template & search tag in search items |
| :white_check_mark: | [P0][sev1][kui]Visual Web Terminal: Verify user path for rbash |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify KUI multiple tabs |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify kubectl |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify oc |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify supported CLIs can execute |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify user home folder permissions |
| :white_check_mark: | [P2][sev1][kui]Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev1][kui]Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev1][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify KUI getting started command |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify commands are disabled - rbash |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify product header |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus |
| :white_check_mark: | [P2][sev3][kui]Visual Web Terminal: Verify supported themes |


---

### Failed Test Details

#### :x:  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:305
Expected
    <string>: Error from server (NotFound): namespaces "openshift-gatekeeper-operator" not found
    
to contain substring
    <string>: namespace "openshift-gatekeeper-operator" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:316
```
                        
#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:250
Timed out after 60.187s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:256
```
                        
#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:220
Timed out after 180.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:234
```
                        
#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:277
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:291
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:107
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0003683c0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:158
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:164
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:173
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:179
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:139
Timed out after 60.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:145
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:187
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000368500>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:123
Timed out after 180.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:137
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:86
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00045c6e0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:91
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:105
```
                        
#### :x: Observability: [P1][Sev1][Observability] Checking metrics default values on managed cluster (config/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_default_config_test.go:27
Expected
    <int64>: 60
to equal
    <int64>: 30
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_default_config_test.go:34
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:353
Expected
    <string>: Error from server (NotFound): namespaces "openshift-compliance" not found
    
to contain substring
    <string>: namespace "openshift-compliance" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:360
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:332
Expected
    <string>: error: the server doesn't have a resource type "ScanSettingBinding"
    
to contain substring
    <string>: scansettingbinding.compliance.openshift.io "e8" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:338
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:178
Timed out after 360.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:191
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:146
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00043a640>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:225
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00043b540>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:199
Timed out after 120.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:205
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:162
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:176
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:125
Timed out after 60.000s.
Expected
    <*errors.StatusError | 0xc0004de8c0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:130
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:144
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:308
Expected
    <*errors.StatusError | 0xc00043b220>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:312
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:316
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00045d7c0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:323
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0004de640>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:277
Timed out after 120.000s.
Expected
    <*errors.StatusError | 0xc00043bf40>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:261
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00043afa0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:292
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00043ac80>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:256
Timed out after 60.000s.
Expected
    <*errors.StatusError | 0xc00043b4a0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```
                        
