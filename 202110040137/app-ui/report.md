# :red_circle: Failed when running regression on cluster ge2n1 with test snapshot 2.4.0-SNAPSHOT-2021-10-01-04-31-02 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/280/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-0.nightly-2021-09-18-052905

Hub Cluster: https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com

Managed Cluster Version: 4.9.0-0.nightly-2021-09-18-052905

Managed Cluster: https://console-openshift-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110040137/

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
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if running canary"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before each" hook for "Skipping cleanup resources test if running canary"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if running canary"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before each" hook for "Verify that settings for application ui-git are properly shown in the app Editor"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before each" hook for "maintain their state across SPA navigation"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table "before each" hook for "get the number of the managed OCP clusters"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping test for canary or smoke test mode"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test "before each" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__header`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:846:10)
```

