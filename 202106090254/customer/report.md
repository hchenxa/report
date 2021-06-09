# :warning: Had some failures when running regression on cluster ocp4-gcp-3 with test snapshot 2.3.0-SNAPSHOT-2021-06-01-10-24-07 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/127/


ACM Version: v2.3.0

Hub Cluster Version: 4.6.23

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.6.23

Managed Cluster: https://console-openshift-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202106090254/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :x: | failed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector "before all" hook for "Prefill a new policy test-issue3677-cert-policy-1623208184 using the form" |
| :x: | failed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1623208184 using the form" |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1623208184 using the form" |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1623208184 using the form" |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1623208184 using the form" |
| :x: | failed | @extended Setup - create a certificate expiring soon "before all" hook for ""Govern risk" page can be launched." |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests "before all" hook for "Verify that CYPRESS_RBAC_PASS environment variable is defined" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if not running on localhost" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before each" hook for "Skipping cleanup resources test if not running on localhost" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if not running on localhost" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before each" hook for "Verify that settings for application ui-git are properly shown in the app Editor" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before each" hook for "maintain their state across SPA navigation" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before each" hook for "get the number of the managed OCP clusters" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test "before each" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load" |
| :x: | failed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation "before all" hook for "Create Pod policy issue2444-1623208184-pod-policy from YAML, expecting a compliance" |
| :x: | failed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly "before all" hook for "Access the Create policy page" |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1623208184 using the form" |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy test-imagemanifest-policy-1623208184 using the form" |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :x: | failed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS "before all" hook for "Create Namespace policy to create template ns as duplicatetest" |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table "before all" hook for "Create new policy test-policy-1-1623208184 using the form" |
| :x: | failed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations "before all" hook for "Check that invalid policy name pattern issues an error" |
| :white_check_mark: | passed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :x: | failed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor "before all" hook for "Access the Create policy page" |
| :x: | failed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit" |
| :x: | failed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates "before all" hook for "Verify YAML template for IamPolicy specification" |
| :x: | failed | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml "before all" hook for "Create policy should fail with invalid policy name in yaml" |
| :x: | failed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1623208184 into YAML editor" |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-operator |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-sample |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: | passed | [P0][sev1][kui]Visual Web Terminal: Verify user path for rbash |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify KUI multiple tabs |
| :large_blue_circle: | skipped | [P1][sev1][kui]Visual Web Terminal: Verify kubectl |
| :large_blue_circle: | skipped | [P1][sev1][kui]Visual Web Terminal: Verify oc |
| :x: | failed | [P1][sev1][kui]Visual Web Terminal: Verify supported CLIs can execute |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify user home folder permissions |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify KUI getting started command |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify commands are disabled - rbash |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify product header |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus |
| :white_check_mark: | passed | [P2][sev3][kui]Visual Web Terminal: Verify supported themes |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :x: | failed | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


---

### Failed Test Details

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

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:133
Timed out after 240.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:139
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:153
Timed out after 62.135s.
Expected
    <string>: I0609 04:02:22.029229    7721 request.go:655] Throttling request took 1.043725476s, request: GET:https://api.ocp4-gcp-3.gcp.dev09.red-chesterfield.com:6443/apis/k8s.cni.cncf.io/v1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:158
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector "before all" hook for "Prefill a new policy test-issue3677-cert-policy-1623208184 using the form"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1623208184 using the form"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1623208184 using the form"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1623208184 using the form"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1623208184 using the form"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before each" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before each" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if not running on localhost"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before each" hook for "Skipping cleanup resources test if not running on localhost"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if not running on localhost"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before each" hook for "Verify that settings for application ui-git are properly shown in the app Editor"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before each" hook for "maintain their state across SPA navigation"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before each" hook for "get the number of the managed OCP clusters"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test "before each" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138220:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:137579:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138219:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8860:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1004:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation "before all" hook for "Create Pod policy issue2444-1623208184-pod-policy from YAML, expecting a compliance"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1623208184 using the form"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy test-imagemanifest-policy-1623208184 using the form"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:303
Timed out after 240.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:308
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:310
Timed out after 180.000s.
Expected
    <string>: RUNNING
to equal
    <string>: AGGREGATING
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:315
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:317
Timed out after 180.000s.
Expected
    <string>: RUNNING
to equal
    <string>: DONE
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:322
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table "before all" hook for "Create new policy test-policy-1-1623208184 using the form"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1623208184 into YAML editor"

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
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138985:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138344:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:138984:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11488:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/server-e2e.js:207:41)
      at backendRequest (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:288:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/server/lib/socket-base.js:321:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.4.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:328
Timed out after 450.000s.
Expected
    <string>: 7/6
to equal
    <string>: 7/7
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:332
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:391
Timed out after 180.000s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:398
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:224
Timed out after 180.056s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:229
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:195
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0005585a0>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "policies.policy.open-cluster-management.io \"policy-gatekeeper\" not found",
            Reason: "NotFound",
            Details: {
                Name: "policy-gatekeeper",
                Group: "policy.open-cluster-management.io",
                Kind: "policies",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:184
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000256a00>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "policies.policy.open-cluster-management.io \"policy-gatekeeper\" not found",
            Reason: "NotFound",
            Details: {
                Name: "policy-gatekeeper",
                Group: "policy.open-cluster-management.io",
                Kind: "policies",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:244
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000257720>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "policies.policy.open-cluster-management.io \"policy-gatekeeper\" not found",
            Reason: "NotFound",
            Details: {
                Name: "policy-gatekeeper",
                Group: "policy.open-cluster-management.io",
                Kind: "policies",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: [P1][sev1][kui]Visual Web Terminal: Verify supported CLIs can execute

```
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:106:16)
    at supportedClis.forEach.cli (/usr/src/app/tests/e2e/cli.test.js:40:11)
    at Array.forEach (<anonymous>)
    at Object.[P1][sev1][kui]Visual Web Terminal: Verify supported CLIs can execute (/usr/src/app/tests/e2e/cli.test.js:39:19)
```

#### :x: e2e-server [P1][Sev1][app-lifecycle] Test argocd integration

```
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:10
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:12
```

