# :warning: Had some failures when running regression on cluster ocp4-acm24-azgov-01 with test snapshot 2.4.0-SNAPSHOT-2021-09-23-08-29-45 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/340/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0

Hub Cluster: https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com

Managed Cluster Version: 4.8.13

Managed Cluster: https://console-openshift-console.apps.almng-hive-aws-101921.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110191801/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins... |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:561:6)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.channel-labels-popover-content .channel-entry`, but never found it.
    at validateSubscriptionTable (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1536:8)
    at eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:520:49)
at Array.map (<anonymous>)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:505:34)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git

```
CypressError: Timed out retrying after 4050ms: `cy.click()` failed because this element is detached from the DOM.

`<span class="pf-c-label">...</span>`

Cypress requires elements be attached in the DOM to interact with them.

The previous command that ran was:

  > `cy.find()`

This DOM element likely became detached somewhere between the previous and current command.

Common situations why this happens:
  - Your JS framework re-rendered asynchronously
  - Your app code reacted to an event firing and removed the element

You typically need to re-query for the element or add 'guards' which delay Cypress from running new commands.

https://on.cypress.io/element-has-detached-from-dom
    at $Cy.ensureAttached (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:144001:24)
    at runAllChecks (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:132602:12)
    at retryActionability (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:132679:16)
    at tryCatcher (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:148807:21)
    at whenStable (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:148845:12)
    at https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:148337:16
    at tryCatcher (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8915:18)
    at Promise._fulfill (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8859:18)
    at https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10473:46
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:744:138)
```

