# :warning: Had some failures when running regression on cluster ocp4-acm24-azgov-01 with test snapshot 2.4.0-SNAPSHOT-2021-09-23-08-29-45 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/339/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0

Hub Cluster: https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com

Managed Cluster Version: 4.9.0

Managed Cluster: https://console-openshift-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110191527/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if running canary |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins... |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:561:6)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
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
    at https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:138831:26
    at tryCatcher (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:278:13)
    at channels (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:296:3)
    at apiResources (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1230:37)
    at edit (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:889:25)
    at deleteFirstSubscription (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:941:3)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1236:37)
    at edit (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:895:25)
    at addNewSubscription (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:977:3)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:554:6)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1257:37)
    at edit (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:916:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1035:3)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1224:37)
    at edit (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:883:25)
    at editApplication (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:904:3)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins...

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git

```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id='local-cluster/ui-git-ns/ui-git']`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1231:37)
    at validateResourceTable (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:716:25)
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

