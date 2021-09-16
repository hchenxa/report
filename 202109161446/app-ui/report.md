# :warning: Had some failures when running regression on cluster ocp49 with test snapshot 2.4.0-SNAPSHOT-2021-09-16-13-47-36 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/269/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-rc.1

Hub Cluster: https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com

Managed Cluster Version: 4.9.0-rc.1

Managed Cluster: https://console-openshift-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202109161446/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
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
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
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
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git

```
AssertionError: Timed out retrying after 300000ms: Expected to find element: `.pf-c-search-input__text-input`, but never found it.
    at Object.searchTable (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1237:8)
    at Object.rowShouldExist (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1229:10)
    at edit (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:889:25)
    at deleteFirstSubscription (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:941:3)
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git

```
AssertionError: Timed out retrying after 300000ms: Expected to find element: `.pf-c-search-input__text-input`, but never found it.
    at Object.searchTable (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1243:8)
    at Object.rowShouldExist (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1235:10)
    at edit (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:895:25)
    at addNewSubscription (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:977:3)
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:554:6)
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created

```
AssertionError: Timed out retrying after 300000ms: Expected to find element: `.pf-c-search-input__text-input`, but never found it.
    at Object.searchTable (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1264:8)
    at Object.rowShouldExist (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1256:10)
    at edit (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:916:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1035:3)
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor

```
AssertionError: Timed out retrying after 300000ms: Expected to find element: `.pf-c-search-input__text-input`, but never found it.
    at Object.searchTable (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1231:8)
    at Object.rowShouldExist (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1223:10)
    at edit (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:883:25)
    at editApplication (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:904:3)
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode

```
TypeError: "before each" hook failed: Cannot read property 'match' of undefined
TypeError: Cannot read property 'match' of undefined
    at Context.eval (https://multicloud-console.apps.ocp49.rc.inter.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

