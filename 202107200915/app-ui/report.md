# :red_circle: Failed when running regression on cluster ocp4-az-3 with test snapshot 2.3.0-SNAPSHOT-2021-07-19-17-01-34 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/239/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.13

Hub Cluster: https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.7.3

Managed Cluster: https://console-openshift-console.apps.acmqe-225-23-hive-before-upgrade.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107200915/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Skipping validate delete test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Skipping cleanup resources test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before all" hook for "Skipping delete resources test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before all" hook for "Verify first subscription can be deleted for app ui-git" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before all" hook for "Verify that settings for application ui-git are properly shown in the app Editor" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before all" hook for "Verify invalid input is rejected" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before all" hook for "get the number of the managed OCP clusters" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before all" hook for "Skipping test for canary or smoke test mode" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test "before all" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Skipping validate delete test if running canary"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Skipping cleanup resources test if running canary"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before all" hook for "Skipping delete resources test if running canary"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before all" hook for "Verify first subscription can be deleted for app ui-git"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before all" hook for "Verify that settings for application ui-git are properly shown in the app Editor"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before all" hook for "Verify invalid input is rejected"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before all" hook for "get the number of the managed OCP clusters"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before all" hook for "Skipping test for canary or smoke test mode"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test "before all" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.exec('oc get pods -n app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error in configuration: Missing or incomplete configuration info.  Please login or point to an existing, complete config file:

  1. Via the command-line flag --kubeconfig
  2. Via the KUBECONFIG e...

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:137265:26
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at installAnsibleOperator (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:616:8)
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:654:3)
```

