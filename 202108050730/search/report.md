# :red_circle: Failed when running regression on cluster ocp4-gcp-3 with test snapshot 2.3.0-SNAPSHOT-2021-04-17-07-15-32 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/257/


ACM Version: v2.3.0

Hub Cluster Version: 4.8.2

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.2

Managed Cluster: https://console-openshift-console.apps.ocp2.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202108050730/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | RHACM4K-412 - Search: Saved searches "after all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace" |
| :x: | failed | RHACM4K-412 - Search: Saved searches "before all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace" |
| :x: | failed | RHACM4K-913: Search - common filter and conditions "after all" hook for "[P1][Sev1][search] should create namespace and application" |
| :x: | failed | RHACM4K-913: Search - common filter and conditions "before all" hook for "[P1][Sev1][search] should create namespace and application" |
| :x: | failed | Search: Linked page "after all" hook for "[P2][Sev2][search] clusters page should have link to search page" |
| :x: | failed | Search: Linked page "before all" hook for "[P2][Sev2][search] clusters page should have link to search page" |
| :x: | failed | Search: Overview page "after all" hook for "[P1][Sev1][search] should load the overview page" |
| :x: | failed | Search: Overview page "before all" hook for "[P1][Sev1][search] should load the overview page" |
| :x: | failed | Search: Search in Local Cluster "after all" hook for "[P1][Sev1][search] should load the search page" |
| :x: | failed | Search: Search in Local Cluster "before all" hook for "[P1][Sev1][search] should load the search page" |
| :x: | failed | Search: Search using filters [P1][Sev1][search] Search using "name" filter "after all" hook for "should suggest values" |
| :x: | failed | Search: Search using filters [P1][Sev1][search] Search using "name" filter "before all" hook for "should suggest values" |
| :x: | failed | Search: Verify the suggested search templates "after all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items" |
| :x: | failed | Search: Verify the suggested search templates "before all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items" |


---

### Failed Test Details

#### :x: RHACM4K-412 - Search: Saved searches "after all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace"

```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```

#### :x: RHACM4K-412 - Search: Saved searches "before all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/overview

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159135:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:158495:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159134:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8878:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2651:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:610:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1546:19)
      at Object.onceWrapper (events.js:421:28)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1220:12)
      at processTicksAndRejections (internal/process/task_queues.js:84:21)
```

#### :x: RHACM4K-913: Search - common filter and conditions "after all" hook for "[P1][Sev1][search] should create namespace and application"

```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```

#### :x: RHACM4K-913: Search - common filter and conditions "before all" hook for "[P1][Sev1][search] should create namespace and application"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/overview

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159135:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:158495:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159134:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8878:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2651:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:610:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1546:19)
      at Object.onceWrapper (events.js:421:28)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1220:12)
      at processTicksAndRejections (internal/process/task_queues.js:84:21)
```

#### :x: Search: Linked page "after all" hook for "[P2][Sev2][search] clusters page should have link to search page"

```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```

#### :x: Search: Linked page "before all" hook for "[P2][Sev2][search] clusters page should have link to search page"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/overview

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159135:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:158495:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159134:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8878:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2651:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:610:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1546:19)
      at Object.onceWrapper (events.js:421:28)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1220:12)
      at processTicksAndRejections (internal/process/task_queues.js:84:21)
```

#### :x: Search: Overview page "after all" hook for "[P1][Sev1][search] should load the overview page"

```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```

#### :x: Search: Overview page "before all" hook for "[P1][Sev1][search] should load the overview page"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/overview

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159135:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:158495:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159134:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8878:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2651:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:610:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1546:19)
      at Object.onceWrapper (events.js:421:28)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1220:12)
      at processTicksAndRejections (internal/process/task_queues.js:84:21)
```

#### :x: Search: Search in Local Cluster "after all" hook for "[P1][Sev1][search] should load the search page"

```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```

#### :x: Search: Search in Local Cluster "before all" hook for "[P1][Sev1][search] should load the search page"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/overview

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159135:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:158495:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159134:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8878:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2651:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:610:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1546:19)
      at Object.onceWrapper (events.js:421:28)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1220:12)
      at processTicksAndRejections (internal/process/task_queues.js:84:21)
```

#### :x: Search: Search using filters [P1][Sev1][search] Search using "name" filter "after all" hook for "should suggest values"

```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```

#### :x: Search: Search using filters [P1][Sev1][search] Search using "name" filter "before all" hook for "should suggest values"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/overview

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159135:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:158495:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159134:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8878:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2651:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:610:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1546:19)
      at Object.onceWrapper (events.js:421:28)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1220:12)
      at processTicksAndRejections (internal/process/task_queues.js:84:21)
```

#### :x: Search: Verify the suggested search templates "after all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items"

```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2759:43)
```

#### :x: Search: Verify the suggested search templates "before all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/overview

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159135:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:158495:12)
    at https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:159134:11
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8878:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2651:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:610:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1546:19)
      at Object.onceWrapper (events.js:421:28)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1220:12)
      at processTicksAndRejections (internal/process/task_queues.js:84:21)
```

