# :warning: 2.3.0-SNAPSHOT-2021-04-29-17-47-22 had some failures when running Regression on user environment

## Job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/96/


Hub Cluster Version: v2.3.0

Hub Cluster: https://multicloud-console.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com

Managed Cluster Version: 4.7.6

Managed Cluster: https://console-openshift-console.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com

## Tests:

|Results|Test|
|---|---|
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-sample |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :x: |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :x: |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :x: | BeforeSuite |
| :x: | RHACM4K-1695: Search - verify managed cluster info in the search page Search - verify managed cluster info in the search page. |
| :x: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind application on specific namespace. |
| :x: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod and namespace open-cluster-management. |
| :x: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod on specific cluster. |
| :x: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:certpolicycontroller. |
| :x: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:iampolicycontroller. |
| :x: | RHACM4K-1696: Search - Verify search result with common filter and conditions Verify a deleted pod is recreated. |
| :x: | RHACM4K-1709: Search - Search using filters should filter by active |
| :x: | RHACM4K-1709: Search - Search using filters should filter by apigroup |
| :x: | RHACM4K-1709: Search - Search using filters should filter by apiversion |
| :x: | RHACM4K-1709: Search - Search using filters should filter by architecture |
| :x: | RHACM4K-1709: Search - Search using filters should filter by available |
| :x: | RHACM4K-1709: Search - Search using filters should filter by capacity |
| :x: | RHACM4K-1709: Search - Search using filters should filter by claimRef |
| :x: | RHACM4K-1709: Search - Search using filters should filter by cluster |
| :x: | RHACM4K-1709: Search - Search using filters should filter by clusterIP |
| :x: | RHACM4K-1709: Search - Search using filters should filter by completions |
| :x: | RHACM4K-1709: Search - Search using filters should filter by consoleURL |
| :x: | RHACM4K-1709: Search - Search using filters should filter by container |
| :x: | RHACM4K-1709: Search - Search using filters should filter by cpu |
| :x: | RHACM4K-1709: Search - Search using filters should filter by created |
| :x: | RHACM4K-1709: Search - Search using filters should filter by current |
| :x: | RHACM4K-1709: Search - Search using filters should filter by desired |
| :x: | RHACM4K-1709: Search - Search using filters should filter by hostIP |
| :x: | RHACM4K-1709: Search - Search using filters should filter by kubernetesVersion |
| :x: | RHACM4K-1709: Search - Search using filters should filter by lastSchedule |
| :x: | RHACM4K-1709: Search - Search using filters should filter by memory |
| :x: | RHACM4K-1709: Search - Search using filters should filter by nodes |
| :x: | RHACM4K-1709: Search - Search using filters should filter by osImage |
| :x: | RHACM4K-1709: Search - Search using filters should filter by parallelism |
| :x: | RHACM4K-1709: Search - Search using filters should filter by podIP |
| :x: | RHACM4K-1709: Search - Search using filters should filter by port |
| :x: | RHACM4K-1709: Search - Search using filters should filter by ready |
| :x: | RHACM4K-1709: Search - Search using filters should filter by reclaimPolicy |
| :x: | RHACM4K-1709: Search - Search using filters should filter by request |
| :x: | RHACM4K-1709: Search - Search using filters should filter by restarts |
| :x: | RHACM4K-1709: Search - Search using filters should filter by startedAt |
| :x: | RHACM4K-1709: Search - Search using filters should filter by successful |
| :x: | RHACM4K-1709: Search - Search using filters should filter by suspend |
| :x: | RHACM4K-1709: Search - Search using filters should filter by type |
| :x: | RHACM4K-1709: Search - Search using filters should filter by updated |
| :x: | RHACM4K-1709: Search - Search using filters should filter by volumeName |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :x: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in kube-system on imported cluster. |
| :x: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm on hub cluster. |
| :x: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent on hub cluster. |
| :x: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent on imported cluster. |
| :x: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent-addon on hub cluster. |
| :x: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent-addon on imported cluster. |
| :x: | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect. |
| :x: | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present. |
| :x: | Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod. |
| :x: | [P0][sev1][kui]Visual Web Terminal: Verify user path for rbash |
| :large_blue_circle: | [P1][sev1][kui]Visual Web Terminal: Verify KUI multiple tabs |
| :large_blue_circle: | [P1][sev1][kui]Visual Web Terminal: Verify kubectl |
| :large_blue_circle: | [P1][sev1][kui]Visual Web Terminal: Verify oc |
| :large_blue_circle: | [P1][sev1][kui]Visual Web Terminal: Verify supported CLIs can execute |
| :x: | [P1][sev1][kui]Visual Web Terminal: Verify user home folder permissions |
| :x: | [P2][sev1][kui]Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons |
| :x: | [P2][sev1][kui]Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons |
| :x: | [P2][sev1][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :x: | [P2][sev2][kui]Visual Web Terminal: Verify KUI getting started command |
| :x: | [P2][sev2][kui]Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons |
| :x: | [P2][sev2][kui]Visual Web Terminal: Verify commands are disabled - rbash |
| :x: | [P2][sev2][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :large_blue_circle: | [P2][sev2][kui]Visual Web Terminal: Verify product header |
| :x: | [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus |
| :large_blue_circle: | [P2][sev3][kui]Visual Web Terminal: Verify supported themes |


---

### Failed Test Details

#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:371
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:385
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:355
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:369
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:444
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:447 +0x237
reflect.Value.call(0x1309bc0, 0x15a9670, 0x13, 0x1502683, 0x4, 0xc0003e10e0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a9670, 0x13, 0xc0003e10e0, 0x0, 0x0, 0x4f542bc21d9a8, 0xc0005b0918, 0x4f542bc21d9a8)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000030180, 0xc0005b0910, 0x23dca80, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000030180, 0x16f8720, 0xc00048f3b0, 0x412f01, 0x0, 0x0, 0x0, 0xc00048f3b0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000030180, 0x16f8720, 0xc00048f3b0, 0x0, 0x0, 0x0, 0x16ecfa0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:448 +0x124
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002fbb00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002fbb00, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:433
Timed out after 60.764s.
Expected
    <string>: I0512 04:53:09.926168   11398 request.go:655] Throttling request took 1.160492661s, request: GET:https://api.ocp4-edge-bm-h27-0.qe.lab.redhat.com:6443/apis/observability.open-cluster-management.io/v1beta2?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:438
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:306
Timed out after 240.000s.
Expected
    <string>: Error from server (NotFound): customresourcedefinitions.apiextensions.k8s.io "assign.mutations.gatekeeper.sh" not found
    
to contain substring
    <string>: CREATED AT
    assign.mutations.gatekeeper.sh
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:310
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:328
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:331 +0x237
reflect.Value.call(0x1309bc0, 0x15a95c8, 0x13, 0x1502683, 0x4, 0xc0003e50b0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a95c8, 0x13, 0xc0003e50b0, 0x0, 0x0, 0x4f4ebd91ad36f, 0xc0005b07d8, 0x4f4ebd91ad36f)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000597e00, 0xc0005b07d0, 0x23dca80, 0x203000, 0xc0003e51c8)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000597e00, 0x16f8720, 0xc00048e190, 0x412f01, 0x0, 0x0, 0x0, 0xc00048e190)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000597e00, 0x16f8720, 0xc00048e190, 0x0, 0x0, 0x0, 0x16ecfa0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:332 +0x147
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002fbb00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002fbb00, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:317
Timed out after 60.846s.
Expected
    <string>: I0512 04:46:56.726627   10500 request.go:655] Throttling request took 1.124707977s, request: GET:https://api.ocp4-edge-bm-h27-0.qe.lab.redhat.com:6443/apis/metrics.k8s.io/v1beta1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:322
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:290
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:304
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:391
Timed out after 180.000s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:398
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:119
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:125
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:134
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:140
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:82
Timed out after 360.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:94
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:108
Timed out after 61.169s.
Expected
    <string>: I0512 04:29:45.140358    7634 request.go:655] Throttling request took 1.139925081s, request: GET:https://api.ocp4-edge-bm-h27-0.qe.lab.redhat.com:6443/apis/operator.openshift.io/v1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:113
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:148
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:162
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:224
Timed out after 180.000s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:229
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:195
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:209
```
                        
#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:269
Timed out after 180.000s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:274
```
                        
#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:240
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:254
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:164
Timed out after 60.000s.
Expected
    <string>: Pending
to equal
    <string>: Running
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:176
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:179
Timed out after 60.000s.
Expected
    <string>: Pending/Pending
to equal
    <string>: Running/Running
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:191
```
                        
#### :x: BeforeSuite


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:95
Unexpected error:
    <*errors.StatusError | 0xc00022e6e0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "secrets \"multiclusterhub-operator-pull-secret\" not found",
            Reason: "NotFound",
            Details: {
                Name: "multiclusterhub-operator-pull-secret",
                Group: "",
                Kind: "secrets",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    secrets "multiclusterhub-operator-pull-secret" not found
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_install_test.go:53
```
                        
#### :x: RHACM4K-1695: Search - verify managed cluster info in the search page Search - verify managed cluster info in the search page.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind application on specific namespace.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod and namespace open-cluster-management.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod on specific cluster.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:certpolicycontroller.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:iampolicycontroller.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions Verify a deleted pod is recreated.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by active


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by apigroup


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by apiversion


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by architecture


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by available


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by capacity


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by claimRef


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by cluster


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by clusterIP


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by completions


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by consoleURL


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by container


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by cpu


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by created


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by current


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by desired


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by hostIP


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by kubernetesVersion


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by lastSchedule


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by memory


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by nodes


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by osImage


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by parallelism


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by podIP


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by port


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by ready


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by reclaimPolicy


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by request


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by restarts


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by startedAt


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by successful


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by suspend


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by type


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by updated


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-1709: Search - Search using filters should filter by volumeName


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:327
Expected
    <string>: I0512 03:57:21.010090    4776 request.go:655] Throttling request took 1.11772612s, request: GET:https://api.ocp4-edge-bm-h27-0.qe.lab.redhat.com:6443/apis/k8s.nginx.org/v1?timeout=32s
    error: the server doesn't have a resource type "ScanSettingBinding"
    
to contain substring
    <string>: scansettingbinding.compliance.openshift.io "e8" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:333
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:176
Timed out after 360.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:188
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:196
Timed out after 120.011s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:202
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:303
Expected
    <*errors.StatusError | 0xc0001d23c0>: {
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
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:307
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:311
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00046e5a0>: {
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
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:318
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00037c3c0>: {
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
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:272
Timed out after 120.000s.
Expected
    <*errors.StatusError | 0xc00026f7c0>: {
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
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions should have expected count of pods in kube-system on imported cluster.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm on hub cluster.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent on hub cluster.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent on imported cluster.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent-addon on hub cluster.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent-addon on imported cluster.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod.


```
Error: getaddrinfo ENOTFOUND search-api-automation-open-cluster-management.apps.ocp4-edge-bm-h27-0.qe.lab.redhat.com
    at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:66:26)
```
                        
#### :x: [P0][sev1][kui]Visual Web Terminal: Verify user path for rbash


```
    at Page.clear (/usr/src/app/tests/page-objects/KUI.js:240:8)
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:91:23)
    at Object.[P0][sev1][kui]Visual Web Terminal: Verify user path for rbash (/usr/src/app/tests/e2e/cli.test.js:29:9)
```
                        
#### :x: [P1][sev1][kui]Visual Web Terminal: Verify user home folder permissions


```
    at Page.clear (/usr/src/app/tests/page-objects/KUI.js:240:8)
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:91:23)
    at Object.[P1][sev1][kui]Visual Web Terminal: Verify user home folder permissions (/usr/src/app/tests/e2e/securityHomeFolder.test.js:20:9)
```
                        
#### :x: [P2][sev1][kui]Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons


```
    at Page.clear (/usr/src/app/tests/page-objects/KUI.js:240:8)
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:91:23)
    at coreSupportRoutes.forEach.command (/usr/src/app/tests/e2e/securityDisabledCoreCommands1.test.js:23:11)
    at Array.forEach (<anonymous>)
    at Object.[P2][sev1][kui]Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons (/usr/src/app/tests/e2e/securityDisabledCoreCommands1.test.js:22:23)
```
                        
#### :x: [P2][sev1][kui]Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons


```
    at Page.clear (/usr/src/app/tests/page-objects/KUI.js:240:8)
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:91:23)
    at coreSupportRoutes.forEach.command (/usr/src/app/tests/e2e/securityDisabledCoreCommands2.test.js:23:11)
    at Array.forEach (<anonymous>)
    at Object.[P2][sev1][kui]Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons (/usr/src/app/tests/e2e/securityDisabledCoreCommands2.test.js:22:23)
```
                        
#### :x: [P2][sev1][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons


```
    at Page.clear (/usr/src/app/tests/page-objects/KUI.js:240:8)
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:91:23)
    at k8sRoutes.forEach.command (/usr/src/app/tests/e2e/securityDisabledK8sCommands3.test.js:22:11)
    at Array.forEach (<anonymous>)
    at Object.[P2][sev1][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons (/usr/src/app/tests/e2e/securityDisabledK8sCommands3.test.js:21:15)
```
                        
#### :x: [P2][sev2][kui]Visual Web Terminal: Verify KUI getting started command


```
    at Page.clear (/usr/src/app/tests/page-objects/KUI.js:240:8)
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:91:23)
    at Object.[P2][sev2][kui]Visual Web Terminal: Verify KUI getting started command (/usr/src/app/tests/e2e/main.test.js:29:9)
```
                        
#### :x: [P2][sev2][kui]Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons


```
    at Page.clear (/usr/src/app/tests/page-objects/KUI.js:240:8)
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:91:23)
    at bashLikeRoutes.forEach.command (/usr/src/app/tests/e2e/securityDisabledBashLikeCommands.test.js:22:11)
    at Array.forEach (<anonymous>)
    at Object.[P2][sev2][kui]Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons (/usr/src/app/tests/e2e/securityDisabledBashLikeCommands.test.js:21:20)
```
                        
#### :x: [P2][sev2][kui]Visual Web Terminal: Verify commands are disabled - rbash


```
    at Page.clear (/usr/src/app/tests/page-objects/KUI.js:240:8)
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:91:23)
    at commands.forEach.command (/usr/src/app/tests/e2e/securityRemovedCommands8.test.js:23:11)
    at Array.forEach (<anonymous>)
    at Object.[P2][sev2][kui]Visual Web Terminal: Verify commands are disabled - rbash (/usr/src/app/tests/e2e/securityRemovedCommands8.test.js:22:14)
```
                        
#### :x: [P2][sev2][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons


```
    at Page.clear (/usr/src/app/tests/page-objects/KUI.js:240:8)
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:91:23)
    at k8sRoutes.forEach.command (/usr/src/app/tests/e2e/securityDisabledK8sCommands2.test.js:22:11)
    at Array.forEach (<anonymous>)
    at Object.[P2][sev2][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons (/usr/src/app/tests/e2e/securityDisabledK8sCommands2.test.js:21:15)
```
                        
#### :x: [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus


```
    at Page.clear (/usr/src/app/tests/page-objects/Prometheus.js:115:10)
    at Page.queryMetric (/usr/src/app/tests/page-objects/Prometheus.js:92:30)
    at Object.[P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus (/usr/src/app/tests/e2e/verifyMetricsInPrometheus.test.js:22:18)
```
                        
