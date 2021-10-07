# :red_circle: Failed when running regression on cluster qe1-vmware-pkt with test snapshot 2.4.0-SNAPSHOT-2021-09-23-08-29-45 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/305/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-rc.1

Hub Cluster: https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com

Managed Cluster Version: 4.6.47

Managed Cluster: https://console-openshift-console.apps.acmqe-24-fr-pool-ftbb6.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110072006/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if running canary |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if running canary |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if running canary |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if running canary

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if running canary

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if running canary

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`

```
CypressError: "before each" hook failed: `cy.visit()` failed trying to load:

https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/multicloud/applications

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer
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
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:995:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  
```

