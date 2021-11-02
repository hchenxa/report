# :warning: Had some failures when running regression on cluster ocp-edge-e25-h13-0 with test snapshot 2.4.0-SNAPSHOT-2021-11-01-21-39-01 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/410/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.4

Hub Cluster: https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com

Managed Cluster Version: 4.9.4

Managed Cluster: https://console-openshift-console.apps.ocp-edge-e25-h13-1.qe.lab.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202111021937/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "Verify application ui-helm can be created from resource type helm using template editor" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-obj can be created from resource type objectstore using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before each" hook for "Verify application ui-git content from the single application topology - git: ui-git" |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if running canary" |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if running canary |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the number of the managed OCP clusters" |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "Verify insecureSkipVerify option in new channel for app ui-git was selected" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before each" hook for "Verify that settings for application ui-git are properly shown in the app Editor" |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins... |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource git - ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before each" hook for "get the number of the managed OCP clusters" |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or BVT test mode |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "Verify application ui-helm can be created from resource type helm using template editor"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor

```
AssertionError: Timed out retrying after 50000ms: Expected to find element: `#githubBranch`, but never found it.
    at gitTasks (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:233:6)
    at createGit (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:417:18)
    at createApplication (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:172:5)
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor

```
AssertionError: Timed out retrying after 50000ms: Expected to find element: `#githubBranch`, but never found it.
    at gitTasks (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:233:6)
    at createGit (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:417:18)
    at createApplication (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:172:5)
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before each" hook for "Verify application ui-git content from the single application topology - git: ui-git"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if running canary"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if running canary"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the number of the managed OCP clusters"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "Verify insecureSkipVerify option in new channel for app ui-git was selected"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1259:37)
    at edit (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:918:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1037:3)
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before each" hook for "Verify that settings for application ui-git are properly shown in the app Editor"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
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
    at https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:154241:85
    at tryCatcher (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:11329:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:2435:13)
    at validateAdvancedTables (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:495:40)
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:123:53)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before each" hook for "get the number of the managed OCP clusters"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

