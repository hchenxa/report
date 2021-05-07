# :warning: 2.3.0-SNAPSHOT-2021-05-07-02-04-59 had some failures when running Regression on user environment

## Job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/81/


Hub Cluster Version: v2.3.0

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.7.9

Managed Cluster: https://console-openshift-console.apps.dhrpatel-fips-aws-hive-test.dev09.red-chesterfield.com

## Tests:

|Results|Test|
|---|---|
| :x: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
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
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
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
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :x: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector "before all" hook for "Prefill a new policy test-issue3677-cert-policy-1620357550 using the form" |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected "before all" hook for "Create the clean up policy using the YAML" |
| :x: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1620357550 using the form" |
| :x: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1620357550 using the form" |
| :x: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1620357550 using the form" |
| :x: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1620357550 using the form" |
| :x: | @extended Setup - create a certificate expiring soon "before all" hook for ""Govern risk" page can be launched." |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests "before all" hook for "Verify that CYPRESS_RBAC_PASS environment variable is defined" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table "before all" hook for "get the number of the managed OCP clusters" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Skipping validate delete test if not running on localhost" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Skipping cleanup resources test if not running on localhost" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before all" hook for "Skipping delete resources test if not running on localhost" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before all" hook for "Verify first subscription can be deleted for app ui-git" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before all" hook for "Verify that settings for application ui-git are properly shown in the app Editor" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test "before all" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before all" hook for "Verify invalid input is rejected" |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation" |
| :x: | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before all" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode" |
| :x: | GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load" |
| :x: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation "before all" hook for "Create Pod policy issue2444-1620357550-pod-policy from YAML, expecting a compliance" |
| :x: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly "before all" hook for "Access the Create policy page" |
| :x: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1620357550 using the form" |
| :x: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy test-imagemanifest-policy-1620357550 using the form" |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :x: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS "before all" hook for "Create Namespace policy to create template ns as duplicatetest" |
| :x: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table "before all" hook for "Create new policy test-policy-1-1620357550 using the form" |
| :x: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations "before all" hook for "Check that invalid policy name pattern issues an error" |
| :white_check_mark: | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :x: | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor "before all" hook for "Access the Create policy page" |
| :x: | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit" |
| :x: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates "before all" hook for "Verify YAML template for IamPolicy specification" |
| :x: | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml "before all" hook for "Create policy should fail with invalid policy name in yaml" |
| :x: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1620357550 into YAML editor" |
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
| :white_check_mark: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :white_check_mark: | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :white_check_mark: | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


---

### Failed Test Details

#### :x:  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:535
Expected
    <string>: Error from server (NotFound): namespaces "openshift-gatekeeper-operator" not found
    
to contain substring
    <string>: namespace "openshift-gatekeeper-operator" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:551
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:371
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:385
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:355
Timed out after 60.000s.
Expected
    <nil>: nil
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
reflect.Value.call(0x1309bc0, 0x15a9670, 0x13, 0x1502683, 0x4, 0xc0005e50e0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a9670, 0x13, 0xc0005e50e0, 0x0, 0x0, 0x36b469e4dcc68, 0xc00068cbe8, 0x36b469e4dcc68)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0005ba080, 0xc00068cbe0, 0x23dca80, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0005ba080, 0x16f86e0, 0xc000155630, 0x412f01, 0x0, 0x0, 0x0, 0xc000155630)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0005ba080, 0x16f86e0, 0xc000155630, 0x0, 0x0, 0x0, 0x16ecf60)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:448 +0x124
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002e39e0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002e39e0, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:494
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0006046e0>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:450
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000684fa0>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:433
Timed out after 60.000s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:438
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:306
Timed out after 240.220s.
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
reflect.Value.call(0x1309bc0, 0x15a95c8, 0x13, 0x1502683, 0x4, 0xc0005e50b0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a95c8, 0x13, 0xc0005e50b0, 0x0, 0x0, 0x36aedfabfdb0b, 0xc00068ce18, 0x36aedfabfdb0b)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0002f0f80, 0xc00068ce10, 0x23dca80, 0x203000, 0xc0005e51c8)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0002f0f80, 0x16f86e0, 0xc000232500, 0x412f01, 0x0, 0x0, 0x0, 0xc000232500)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0002f0f80, 0x16f86e0, 0xc000232500, 0x0, 0x0, 0x0, 0x16ecf60)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:332 +0x147
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002e39e0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002e39e0, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:274
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000258b40>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:317
Timed out after 60.674s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
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
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:304
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:391
Timed out after 183.330s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:398
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:66
Timed out after 30.001s.
Expected
    <*errors.StatusError | 0xc0006854a0>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:164
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000604c80>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:108
Timed out after 60.303s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
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
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:162
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:45
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000604a00>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:50
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:64
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:224
Timed out after 180.577s.
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
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:209
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:244
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:258
```
                        
#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:269
Timed out after 180.233s.
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
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:254
```
                        
#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:289
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:303
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:117
Timed out after 30.045s.
Expected
    <*errors.StatusError | 0xc000372b40>: {
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
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:164
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:170
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:179
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:185
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:133
Timed out after 120.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:139
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:209
Timed out after 30.062s.
Expected
    <*errors.StatusError | 0xc000372d20>: {
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
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:153
Timed out after 61.518s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:158
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:193
Timed out after 180.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:207
```
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:96
Timed out after 30.045s.
Expected
    <*errors.StatusError | 0xc000258dc0>: {
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
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:101
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:115
```
                        
#### :x: @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup "before all" hook for "Create the clean up policy using the YAML"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup "before all" hook for "Create the clean up policy using the YAML"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup "before all" hook for "Create the clean up policy using the YAML"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector "before all" hook for "Prefill a new policy test-issue3677-cert-policy-1620357550 using the form"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected "before all" hook for "Create the clean up policy using the YAML"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1620357550 using the form"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1620357550 using the form"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1620357550 using the form"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1620357550 using the form"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @extended Setup - create a certificate expiring soon "before all" hook for ""Govern risk" page can be launched."


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests "before all" hook for "Verify that CYPRESS_RBAC_PASS environment variable is defined"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table "before all" hook for "get the number of the managed OCP clusters"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Skipping validate delete test if not running on localhost"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Skipping cleanup resources test if not running on localhost"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before all" hook for "Skipping delete resources test if not running on localhost"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before all" hook for "Verify first subscription can be deleted for app ui-git"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before all" hook for "Verify that settings for application ui-git are properly shown in the app Editor"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test "before all" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before all" hook for "Verify invalid input is rejected"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before all" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation "before all" hook for "Create Pod policy issue2444-1620357550-pod-policy from YAML, expecting a compliance"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly "before all" hook for "Access the Create policy page"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1620357550 using the form"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy test-imagemanifest-policy-1620357550 using the form"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:144
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0007381e0>: {
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:222
Timed out after 30.017s.
Expected
    <*errors.StatusError | 0xc0001beb40>: {
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:160
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:174
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:123
Timed out after 60.000s.
Expected
    <*errors.StatusError | 0xc000259a40>: {
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:128
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:142
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:256
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0003732c0>: {
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:287
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000259860>: {
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:251
Timed out after 60.166s.
Expected
    <*errors.StatusError | 0xc000258780>: {
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
                        
#### :x: RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS "before all" hook for "Create Namespace policy to create template ns as duplicatetest"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table "before all" hook for "Create new policy test-policy-1-1620357550 using the form"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations "before all" hook for "Check that invalid policy name pattern issues an error"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor "before all" hook for "Access the Create policy page"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates "before all" hook for "Verify YAML template for IamPolicy specification"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml "before all" hook for "Create policy should fail with invalid policy name in yaml"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
#### :x: RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1620357550 into YAML editor"


```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138581:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137940:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138580:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8904:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:20695:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.onevent (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:253:20)
      at Socket._onpacket (/root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:216:22)
      at /root/.cache/Cypress/7.2.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/client.js:205:28
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```
                        
