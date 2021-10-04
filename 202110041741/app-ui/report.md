# :red_circle: Failed when running regression on cluster qe1-vmware-pkt with test snapshot 2.4.0-SNAPSHOT-2021-10-02-11-10-03 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/287/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-rc.1

Hub Cluster: https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com

Managed Cluster Version: 4.9.0-rc.4

Managed Cluster: https://console-openshift-console.apps.qe4-vmware-pkt.dev02.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110041741/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before each" hook for "Skipping cleanup resources test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before each" hook for "Verify that settings for application ui-git are properly shown in the app Editor" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before each" hook for "maintain their state across SPA navigation" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before each" hook for "get the number of the managed OCP clusters" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping test for canary or smoke test mode" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test "before each" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if running canary"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before each" hook for "Skipping cleanup resources test if running canary"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if running canary"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping test for canary or smoke test mode"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

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

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156031:82
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:155390:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:156030:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:1088:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:607:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (internal/streams/readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

