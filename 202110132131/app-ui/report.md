# :warning: Had some failures when running regression on cluster ocp4-awsgov-01 with test snapshot 2.4.0-SNAPSHOT-2021-10-06-20-31-30 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/328/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-rc.1

Hub Cluster: https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com

Managed Cluster Version: 4.9.0-rc.1

Managed Cluster: https://console-openshift-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110132131/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if running canary |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins... |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource git - ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before all" hook for "Skipping test for canary or smoke test mode" |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor

```
CypressError: `cy.type()` can only accept a string or number. You passed in: `undefined`

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:151569:76)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:169833:23)
From Your Spec Code:
    at selectMatchingLabel (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1433:39)
    at selectClusterDeployment (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1410:58)
    at gitTasks (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:284:39)
    at createGit (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:417:18)
    at createApplication (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:172:5)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-alert.pf-m-success`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1320:6)
    at submitSave (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1201:18)
    at createApplication (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:179:26)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:561:6)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible

```
AssertionError: expected 0 to be at least 3
    at validateTopology (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:640:64)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#edit-button-portal-id`, but never found it.
    at validateDefect7696 (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:2253:6)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:129:44)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster

```
AssertionError: Timed out retrying after 4000ms: expected '' to include 'ui-git-subscription-1'
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:330:24)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git

```
CypressError: `cy.exec('oc get subscription ui-git-subscription-1 -n ui-git-ns -o yaml')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:154241:85
    at tryCatcher (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:362:12)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git

```
CypressError: `cy.exec('oc -n ui-git-ns get subscription ui-git-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:154241:85
    at tryCatcher (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:278:13)
    at channels (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:296:3)
    at apiResources (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1232:37)
    at edit (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:891:25)
    at deleteFirstSubscription (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:943:3)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1232:37)
    at edit (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:891:25)
    at verifyEditAfterDeleteSubscription (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:996:5)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:115:64)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1238:37)
    at edit (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:897:25)
    at addNewSubscription (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:979:3)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:554:6)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected

```
CypressError: `cy.exec('oc -n ui-git-ns get subscription ui-git-subscription-3 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:154241:85
    at tryCatcher (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:2450:13)
    at verifyInsecureSkipAfterNewSubscription (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1052:38)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:125:71)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:574:6)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:142:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1259:37)
    at edit (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:918:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1037:3)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1226:37)
    at edit (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:885:25)
    at editApplication (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:906:3)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git

```
CypressError: `cy.exec('oc -n ui-git-ns get subscription ui-git-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:154241:85
    at tryCatcher (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:2433:13)
    at validateAdvancedTables (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:495:40)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:123:53)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git

```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1233:37)
    at validateResourceTable (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:716:25)
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include 'Local'
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:733:133)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before all" hook for "Skipping test for canary or smoke test mode"

```
CypressError: `cy.exec('oc adm policy add-cluster-role-to-user                                 open-cluster-management:view:undefined app-test-mngd-cluster-view|                                 oc policy add-role-to-user view app-test-mngd-cluster-view -n undefined')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Warning: User 'app-test-mngd-cluster-view' not found
Error from server (NotFound): namespaces "undefined" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:154241:85
    at tryCatcher (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1368:10)
```

