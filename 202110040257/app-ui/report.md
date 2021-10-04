# :warning: Had some failures when running regression on cluster ge2n1 with test snapshot 2.4.0-SNAPSHOT-2021-09-30-03-17-33 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/281/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-0.nightly-2021-09-18-052905

Hub Cluster: https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com

Managed Cluster Version: 4.9.0-0.nightly-2021-09-18-052905

Managed Cluster: https://console-openshift-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110040257/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before each" hook for "Skipping cleanup resources test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if running canary" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "get the name of the managed OCP cluster" |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins... |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource git - ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test "before each" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-alert.pf-m-success`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1318:6)
    at submitSave (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1199:18)
    at createApplication (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:179:26)
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `.pf-c-alert.pf-m-success`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1318:6)
    at submitSave (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:1199:18)
    at createApplication (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:179:26)
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/01-create/02-wizard.spec.js:117:46)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible

```
AssertionError: expected 0 to be at least 3
    at validateTopology (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:640:64)
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before each" hook for "Skipping validate delete test if running canary"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before each" hook for "Skipping cleanup resources test if running canary"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before each" hook for "Skipping delete resources test if running canary"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before each" hook for "Verify first subscription can be deleted for app ui-git"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before each" hook for "get the name of the managed OCP cluster"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git

```
AssertionError: Timed out retrying after 4000ms: expected 'Git (3)' to equal 'Git (2)'
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:740:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include 'Local'
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:733:133)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test "before each" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test "before each" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
AssertionError: Timed out retrying after 4000ms: Expected to find element: `.pf-c-login__main-body`, but never found it.

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ge2n1.ocp.rhev.lab.eng.brq.redhat.com/__cypress/tests?p=cypress/support/index.js:825:6)
```

