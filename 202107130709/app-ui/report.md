# :warning: Had some failures when running regression on cluster ocp4-azgov-3 with test snapshot 2.3.0-SNAPSHOT-2021-07-13-04-59-11 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/232/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.16

Hub Cluster: https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com

Managed Cluster Version: 4.7.19

Managed Cluster: https://console-openshift-console.apps.dh-az4.acm-dev06.azure.devcluster.openshift.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107130709/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm can be created from resource type helm using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm2 can be created from resource type helm using template editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-obj can be created from resource type objectstore using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Skipping validate delete test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Skipping cleanup resources test if running canary" |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm2 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-helm is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-helm was selected |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm template editor valid after new subscription is created |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm2 are properly shown in the app Editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins... |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource git - ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource helm - ui-helm2 |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2 |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm can be created from resource type helm using template editor

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-alert.pf-m-success`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1290:6)
    at submitSave (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1171:18)
    at createApplication (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:180:26)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-obj can be created from resource type objectstore using template editor

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-alert.pf-m-success`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1290:6)
    at submitSave (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1171:18)
    at createApplication (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:180:26)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-alert.pf-m-success`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:1303:6)
    at validateSyncFunction (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:1732:20)
    at validateTopology (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:551:36)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-alert.pf-m-success`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:1303:6)
    at validateSyncFunction (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:1732:20)
    at validateTopology (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:551:36)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm

```
AssertionError: Timed out retrying after 4000ms: Expected to find content: '1 Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:613:15)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2

```
AssertionError: Timed out retrying after 4000ms: Expected to find content: 'Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:613:15)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:543:6)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` timed out after waiting `20000ms`.

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:137276:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5920:41
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Skipping validate delete test if running canary"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` timed out after waiting `20000ms`.

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:137276:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5920:41
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Skipping cleanup resources test if running canary"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` timed out after waiting `20000ms`.

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:137276:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5920:41
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-obj-ns/ui-obj']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1202:37)
    at edit (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:871:25)
    at deleteFirstSubscription (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:923:3)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-obj-ns/ui-obj']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1202:37)
    at edit (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:871:25)
    at verifyEditAfterDeleteSubscription (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:976:5)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:115:64)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git

```
CypressError: Timed out retrying after 4050ms: `cy.click()` failed because this element is not visible:

`<div class="tf--provider-card" id="git" role="button" tabindex="0" aria-label="Git" data-testid="card-git">...</div>`

This element `<div#git.tf--provider-card>` is not visible because its parent `<div.creation-view-controls-section.collapsed>` has CSS property: `overflow: hidden` and an effective width and height of: `731 x 0` pixels.

Fix this problem, or use `{force: true}` to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureVisibility (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:142412:24)
    at runAllChecks (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:131087:14)
    at retryActionability (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:131141:16)
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:147090:21)
    at whenStable (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:147128:12)
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:146620:16
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8915:18)
    at Promise._fulfill (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8859:18)
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10473:46
From Your Spec Code:
    at gitTasks (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:220:42)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:460:5)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm

```
CypressError: Timed out retrying after 4050ms: `cy.click()` failed because this element is not visible:

`<div class="tf--provider-card" id="helm" role="button" tabindex="0" aria-label="Helm" data-testid="card-helm">...</div>`

This element `<div#helm.tf--provider-card>` is not visible because its parent `<div.creation-view-controls-section.collapsed>` has CSS property: `overflow: hidden` and an effective width and height of: `731 x 0` pixels.

Fix this problem, or use `{force: true}` to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureVisibility (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:142412:24)
    at runAllChecks (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:131087:14)
    at retryActionability (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:131141:16)
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:147090:21)
    at whenStable (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:147128:12)
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:146620:16
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8915:18)
    at Promise._fulfill (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8859:18)
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10473:46
From Your Spec Code:
    at helmTasks (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:340:26)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:460:5)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-obj-ns/ui-obj']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1208:37)
    at edit (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:877:25)
    at addNewSubscription (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:959:3)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:536:6)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:536:6)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:556:6)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:142:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-obj-ns/ui-obj']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1229:37)
    at edit (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:898:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1017:3)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-obj-ns/ui-obj']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1196:37)
    at edit (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:865:25)
    at editApplication (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:886:3)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` timed out after waiting `20000ms`.

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:137276:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5920:41
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1494:107)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1494:107)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1494:107)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include 'Local'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include 'Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj

```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-obj-ns/ui-obj']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1203:37)
    at validateResourceTable (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:698:25)
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```

