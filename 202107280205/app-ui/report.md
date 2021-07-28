# :warning: Had some failures when running regression on cluster slot-00 with test snapshot 2.3.0-SNAPSHOT-2021-07-26-18-43-26 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/244/


ACM Version: v2.3.0

Hub Cluster Version: 4.8.2

Hub Cluster: https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com

Managed Cluster Version: 4.7.21

Managed Cluster: https://console-openshift-console.apps.slot-04.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107280205/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm can be created from resource type helm using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm2 can be created from resource type helm using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-obj can be created from resource type objectstore using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm timewindow - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 timewindow - helm: ui-helm2 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj timewindow - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm channels, subscription and placementrule are valid - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm2 channels, subscription and placementrule are valid - helm: ui-helm2 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-obj channels, subscription and placementrule are valid - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm2 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-helm is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-helm was selected |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm2 are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins... |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource git - ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource helm - ui-helm2 |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2 |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git

```
AssertionError: Timed out retrying after 4000ms: Expected to find content: '1 Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:613:15)
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible

```
AssertionError: expected 0 to be at least 3
    at validateTopology (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:622:64)
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm

```
AssertionError: Timed out retrying after 4000ms: Expected to find content: '1 Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:613:15)
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2

```
AssertionError: Timed out retrying after 4000ms: Expected to find content: 'Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:613:15)
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: Expected to find content: '1 Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:613:15)
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote'
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1494:107)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote'
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1494:107)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote'
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1494:107)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git

```
AssertionError: Timed out retrying after 4000ms: expected 'Local' to include '1 Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include 'Local'
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm

```
AssertionError: Timed out retrying after 4000ms: expected 'Local' to include '1 Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2

```
AssertionError: Timed out retrying after 4000ms: expected 'Local' to include 'Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

