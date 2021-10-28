# :warning: Had some failures when running regression on cluster ocp4-az-01 with test snapshot 2.4.0-SNAPSHOT-2021-10-25-23-58-51 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/376/


ACM Version: v2.4.0

Hub Cluster Version: 4.6.46

Hub Cluster: https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.9.0

Managed Cluster: https://console-openshift-console.apps.acmqe-24-rc-hive-ansible-azure.acm-dev06.azure.devcluster.openshift.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110280410/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm can be created from resource type helm using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm2 can be created from resource type helm using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-obj can be created from resource type objectstore using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm timewindow - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 timewindow - helm: ui-helm2 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj timewindow - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm channels, subscription and placementrule are valid - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm2 channels, subscription and placementrule are valid - helm: ui-helm2 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-obj channels, subscription and placementrule are valid - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if running canary |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm2 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-helm is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-helm was selected |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm2 are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins... |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource git - ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource helm - ui-helm2 |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2 |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or BVT test mode |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-alert.pf-m-success`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1321:6)
    at submitSave (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1201:18)
    at createApplication (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:179:26)
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-alert.pf-m-success`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1321:6)
    at submitSave (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1201:18)
    at createApplication (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:179:26)
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible

```
AssertionError: expected 0 to be at least 3
    at validateTopology (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:640:64)
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: Expected to find content: '1 Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:631:15)
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git

```
AssertionError: Timed out retrying after 20000ms: Expected [ <div.creation-view-controls-delete-button>, 1 more... ] not to exist in the DOM, but it was continuously found.
    at deleteFirstSubscription (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:957:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359

```
AssertionError: Timed out retrying after 4000ms: Too many elements found. Found '3', expected '1'.
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:999:48)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git

```
CypressError: Timed out retrying after 4000ms: `cy.trigger()` failed because this element is not visible:

`<div class="tf--provider-card" id="git" role="button" tabindex="0" aria-label="Git" data-testid="card-git">...</div>`

This element `<div#git.tf--provider-card>` is not visible because its parent `<div.creation-view-controls-section.collapsed>` has CSS property: `overflow: hidden` and an effective width and height of: `731 x 0` pixels.

Fix this problem, or use `{force: true}` to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureVisibility (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:160494:85)
    at runAllChecks (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:147840:14)
    at retryActionability (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:147894:16)
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10486:29)
    at tryFn (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:165305:61)
    at whenStable (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:165344:14)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:164831:18
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11329:18)
    at Promise._fulfill (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11273:18)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:12887:46
From Your Spec Code:
    at gitTasks (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:219:42)
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:478:5)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted

```
AssertionError: Timed out retrying after 25000ms: Expected to find element: `g[type="ui-git-subscription-2"]`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:585:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created

```
AssertionError: Timed out retrying after 4000ms: expected 'https://github.com/open-cluster-management/app-ui-e2e-private-gitBranch:mainPath:helloworld' to include 'https://github.com/fxiang1/app-samples.gitBranch:mainPath:mortgagepod'
    at validateSubscriptionDetails (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1888:25)
    at validateTopology (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:583:43)
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:142:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created

```
AssertionError: Timed out retrying after 4000ms: Too many elements found. Found '3', expected '2'.
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1042:46)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote'
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1533:107)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git

```
AssertionError: Timed out retrying after 4000ms: expected 'Git (3)' to equal 'Git (2)'
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:740:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:733:133)
```

