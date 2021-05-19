# :warning: Had some failures when running regression on cluster ocp4-gcp-3 with test snapshot 2.3.0-SNAPSHOT-2021-05-19-08-58-37 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/112/


ACM Version: v2.2.3

Hub Cluster Version: "4.6.23"

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.6.23

Managed Cluster: https://console-openshift-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com

Detailed test result on S3: s3://acmqe-regression/data/202105191020

## Tests:

|Results|Test|
|---|---|
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-sample |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before each" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before each" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if not running on localhost" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before each" hook for "Skipping cleanup resources test if not running on localhost" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if not running on localhost" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before each" hook for "Verify that settings for application ui-git are properly shown in the app Editor" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test "before each" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected" |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before each" hook for "maintain their state across SPA navigation" |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before each" hook for "get the number of the managed OCP clusters" |
| :x: | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode" |
| :x: | Observability: [P1][Sev1][Observability] Cannot enable observability service successfully |
| :x: | Observability: [P1][Sev1][Observability] Cannot uninstall observability service completely |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :white_check_mark: | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
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
| :x: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :x: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :white_check_mark: | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :white_check_mark: | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "get the name of the managed OCP cluster"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before each" hook for "get the name of the managed OCP cluster"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before each" hook for "get the name of the managed OCP cluster"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if not running on localhost"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before each" hook for "Skipping cleanup resources test if not running on localhost"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if not running on localhost"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the name of the managed OCP cluster"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "get the name of the managed OCP cluster"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before each" hook for "Verify that settings for application ui-git are properly shown in the app Editor"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test "before each" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before each" hook for "maintain their state across SPA navigation"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "get the name of the managed OCP cluster"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before each" hook for "get the number of the managed OCP clusters"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode"


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:802:10)
```
                        
#### :x: Observability: [P1][Sev1][Observability] Cannot enable observability service successfully


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:95
Unexpected error:
    <*errors.StatusError | 0xc001ed4640>: {
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
    the server could not find the requested resource
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_install_test.go:132
```
                        
#### :x: Observability: [P1][Sev1][Observability] Cannot uninstall observability service completely


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:100
Unexpected error:
    <*errors.StatusError | 0xc002f8e0a0>: {
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
    the server could not find the requested resource
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_uninstall_test.go:38
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
Timed out after 180.021s.
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
                        
#### :x: e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit


```
/opt/e2e/client/canary/e2e_subscription_test.go:12
Timed out after 48.741s.
Expected success, but got an error:
    <*errors.errorString | 0xc000703110>: {
        s: "failed test on sub-004, with status failed err: failed",
    }
    failed test on sub-004, with status failed err: failed
/opt/e2e/client/canary/e2e_subscription_test.go:13
```
                        
#### :x: e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag


```
/opt/e2e/client/canary/e2e_subscription_test.go:9
Timed out after 52.708s.
Expected success, but got an error:
    <*errors.errorString | 0xc0007022b0>: {
        s: "failed test on sub-003, with status failed err: failed",
    }
    failed test on sub-003, with status failed err: failed
/opt/e2e/client/canary/e2e_subscription_test.go:10
```
                        
