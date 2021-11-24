# :warning: Had some failures when running regression on cluster ocp4-az-dr-1 with test snapshot v2.4.1-RC1 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/tests/job/thnguyen-e2e/29/


ACM Version: v2.4.1

Hub Cluster Version: 4.9.4

Hub Cluster: https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.9.4

Managed Cluster: https://console-openshift-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202111242105/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2553 - Add RHOCM credential in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2555 - Delete RHOCM credential in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2556 - Create discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2557 - Update discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2558 - Delete discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Error handling RHACM4K-2554 - Update RHOCM cred for invalid token |
| :white_check_mark: | passed | Discovery config - Error handling RHACM4K-3020 - No clusters discovered in case of invalid token |
| :x: | failed | Discovery config - Import a discovered cluster in UI "after all" hook for "RHACM4K-2819 - Detach discovered clusters" |
| :x: | failed | Discovery config - Import a discovered cluster in UI RHACM4K-2819 - Detach discovered clusters |
| :white_check_mark: | passed | Discovery config - Import a discovered cluster in UI RHACM4K-3019 - Import a discovered cluster kubeconfig (UI only) |
| :x: | failed | Discovery config - Import a discovered cluster in UI RHACM4K-3174 - Import a discovered cluster apitoken (UI only) |
| :white_check_mark: | passed | Discovery config - Import a discovered cluster in UI RHACM4K-7514 - Import a discovered cluster manual (UI only) |


---

### Failed Test Details

#### :x: Discovery config - Import a discovered cluster in UI "after all" hook for "RHACM4K-2819 - Detach discovered clusters"

```
CypressError: `cy.click()` failed because it requires a DOM element.

The subject received was:

  > `undefined`

The previous command that ran was:

  > `cy.contains()`

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at ensureElement (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:142062:24)
    at validateType (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:141899:16)
    at Object.ensureSubjectByType (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:141935:9)
    at pushSubjectAndValidate (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:150706:15)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:151058:18)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02_import.spec.js:154:25)
```

#### :x: Discovery config - Import a discovered cluster in UI RHACM4K-2819 - Detach discovered clusters

```
CypressError: Timed out retrying after 30050ms: `cy.click()` failed because the center of this element is hidden from view:

`<button aria-disabled="false" class="pf-c-button pf-m-link jss21" type="button" data-ouia-component-type="PF4/Button" data-ouia-safe="true" data-ouia-component-id="OUIA-Generated-Button-link-8">Detached</button>`

Fix this problem, or use `{force: true}` to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureDescendents (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:142198:24)
    at ensureDescendents (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130488:8)
    at possiblyScrollMultipleTimes (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130597:22)
    at scrollContainers (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130620:16)
    at possiblyScrollMultipleTimes (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130616:20)
    at possiblyScrollMultipleTimes (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130609:24)
    at scrollContainers (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130620:16)
    at ensureDescendentsAndScroll (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130624:14)
    at ensureElIsNotCovered (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130629:5)
    at runAllChecks (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130816:52)
    at retryActionability (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:130839:16)
    at tryCatcher (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10791:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8065:29)
    at tryFn (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:146634:21)
    at whenStable (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:146672:12)
    at https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:146164:16
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02_import.spec.js:1376:31)
```

#### :x: Discovery config - Import a discovered cluster in UI RHACM4K-3174 - Import a discovered cluster apitoken (UI only)

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody > tr`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-az-dr-1.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02_import.spec.js:902:8)
```

