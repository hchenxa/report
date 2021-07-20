# :red_circle: Failed when running regression on cluster ocp4-edge-bm-h29-0 with test snapshot 2.3.0-SNAPSHOT-2021-07-15-17-21-39 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/236/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.16

Hub Cluster: https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com

Managed Cluster Version: 4.7.16

Managed Cluster: https://console-openshift-console.apps.ocp4-edge-bm-h29-1.qe.lab.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107200654/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector "before all" hook for "Prefill a new policy test-issue3677-cert-policy-1626764252 using the form" |
| :x: | failed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1626764252 using the form" |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1626764252 using the form" |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1626764252 using the form" |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1626764252 using the form" |
| :x: | failed | @extended Setup - create a certificate expiring soon "before all" hook for ""Govern risk" page can be launched." |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests "before all" hook for "Verify that CYPRESS_RBAC_PASS environment variable is defined" |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load" |
| :x: | failed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation "before all" hook for "Create Pod policy issue2444-1626764252-pod-policy from YAML, expecting a compliance" |
| :x: | failed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly "before all" hook for "Access the Create policy page" |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1626764252 using the form" |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy t-imp-1626764252 using the form" |
| :x: | failed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS "before all" hook for "Create Namespace policy to create template ns as duplicatetest" |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table "before all" hook for "Create new policy test-policy-1-1626764252 using the form" |
| :x: | failed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations "before all" hook for "Check that invalid policy name pattern issues an error" |
| :x: | failed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor "before all" hook for "Access the Create policy page" |
| :x: | failed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit" |
| :x: | failed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates "before all" hook for "Verify YAML template for IamPolicy specification" |
| :x: | failed | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml "before all" hook for "Create policy should fail with invalid policy name in yaml" |
| :x: | failed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1626764252 into YAML editor" |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal "before all" hook for "Create a subscription to install the Ansible operator" |


---

### Failed Test Details

#### :x: @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup "before all" hook for "Create the clean up policy using the YAML"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup "before all" hook for "Create the clean up policy using the YAML"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup "before all" hook for "Create the clean up policy using the YAML"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector "before all" hook for "Prefill a new policy test-issue3677-cert-policy-1626764252 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected "before all" hook for "Create the clean up policy using the YAML"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1626764252 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1626764252 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1626764252 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1626764252 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended Setup - create a certificate expiring soon "before all" hook for ""Govern risk" page can be launched."

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests "before all" hook for "Verify that CYPRESS_RBAC_PASS environment variable is defined"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation "before all" hook for "Create Pod policy issue2444-1626764252-pod-policy from YAML, expecting a compliance"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly "before all" hook for "Access the Create policy page"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1626764252 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy t-imp-1626764252 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS "before all" hook for "Create Namespace policy to create template ns as duplicatetest"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table "before all" hook for "Create new policy test-policy-1-1626764252 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations "before all" hook for "Check that invalid policy name pattern issues an error"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor "before all" hook for "Access the Create policy page"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates "before all" hook for "Verify YAML template for IamPolicy specification"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml "before all" hook for "Create policy should fail with invalid policy name in yaml"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1626764252 into YAML editor"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal "before all" hook for "Create a subscription to install the Ansible operator"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: connect ECONNREFUSED 10.0.11.123:443

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: connect ECONNREFUSED 10.0.11.123:443
      at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1146:16)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

