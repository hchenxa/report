# :warning: Had some failures when running regression on cluster ocp4-gcp-dr-1 with test snapshot 2.3.0-SNAPSHOT-2021-04-17-07-15-32 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/tests/job/thnguyen-e2e/21/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.9.5

Managed Cluster: https://console-openshift-console.apps.my-aws-sno.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202111171427/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Discovery config - Creating/Updating/Deleting discovery config in UI "after all" hook for "RHACM4K-2555 - Delete RHOCM credential in the namespace aut-disco-ns" |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2553 - Add RHOCM credential in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2556 - Create discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2557 - Update discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2558 - Delete discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Error handling RHACM4K-2554 - Update RHOCM cred for invalid token |
| :white_check_mark: | passed | Discovery config - Error handling RHACM4K-3020 - No clusters discovered in case of invalid token |
| :white_check_mark: | passed | Discovery config - Import a discovered cluster in UI RHACM4K-2819 - Detach discovered clusters |
| :white_check_mark: | passed | Discovery config - Import a discovered cluster in UI RHACM4K-3019 - Import a discovered cluster kubeconfig (UI only) |
| :x: | failed | Discovery config - Import a discovered cluster in UI RHACM4K-3174 - Import a discovered cluster apitoken (UI only) |
| :white_check_mark: | passed | Discovery config - Import a discovered cluster in UI RHACM4K-7514 - Import a discovered cluster manual (UI only) |


---

### Failed Test Details

#### :x: Discovery config - Creating/Updating/Deleting discovery config in UI "after all" hook for "RHACM4K-2555 - Delete RHOCM credential in the namespace aut-disco-ns"

```
CypressError: Timed out retrying after 30050ms: `cy.click()` failed because this element is detached from the DOM.

`<button tabindex="-1" data-ouia-component-type="PF4/DropdownItem" data-ouia-safe="true" data-ouia-component-id="OUIA-Generated-DropdownItem-2" aria-disabled="false" type="button" class="pf-c-app-launcher__menu-item">Logout</button>`

Cypress requires elements be attached in the DOM to interact with them.

The previous command that ran was:

  > `cy.should()`

This DOM element likely became detached somewhere between the previous and current command.

Common situations why this happens:
  - Your JS framework re-rendered asynchronously
  - Your app code reacted to an event firing and removed the element

You typically need to re-query for the element or add 'guards' which delay Cypress from running new commands.

https://on.cypress.io/element-has-detached-from-dom

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at $Cy.ensureAttached (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:142048:24)
    at runAllChecks (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:130762:12)
    at retryActionability (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:130839:16)
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8065:29)
    at tryFn (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:146634:21)
    at whenStable (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:146672:12)
    at https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:146164:16
    at tryCatcher (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8908:18)
    at Promise._fulfill (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8852:18)
    at https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10466:46
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01_disco.spec.js:157:27)
```

#### :x: Discovery config - Import a discovered cluster in UI RHACM4K-3174 - Import a discovered cluster apitoken (UI only)

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody > tr`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-dr-1.gcp.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02_import.spec.js:902:8)
```

