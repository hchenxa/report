# :warning: 2.3.0-SNAPSHOT-2021-04-24-05-15-03 had some failures when running Regression on user environment

## Job URL: https://tests-jenkins-csb-rhacm.cloud.paas.psi.redhat.com/job/automation-sample-job-test/90/


Hub Cluster Version: v2.3.0

Hub Cluster: https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com

Managed Cluster Version: 4.7.5

Managed Cluster: https://console-openshift-console.apps.yhliu-aws1.dev09.red-chesterfield.com

## Tests:

|Results|Test|
|---|---|
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm can be created from resource type helm using template editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm2 can be created from resource type helm using template editor |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-obj can be created from resource type objectstore using template editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git-ansible channel, subscription, placement rule info from the advanced configuration tables - git: ui-git-ansible |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource helm |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2 |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2 |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055 |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible resources created on the target cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm resources created on the target cluster |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm timewindow - helm: ui-helm |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 resources created on the target cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 timewindow - helm: ui-helm2 |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj resources created on the target cluster |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj timewindow - objectstore: ui-obj |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm channels, subscription and placementrule are valid - helm: ui-helm |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm2 channels, subscription and placementrule are valid - helm: ui-helm2 |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-obj channels, subscription and placementrule are valid - objectstore: ui-obj |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if not running on localhost |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if not running on localhost |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if not running on localhost |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm2 |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-helm is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-helm was selected |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm single app page info is valid after new subscription is created |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm template editor valid after new subscription is created |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm are properly shown in the app Editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm2 are properly shown in the app Editor |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :white_check_mark: | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode |


---

### Failed Test Details

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor


```
CypressError: `cy.type()` can only accept a string or number. You passed in: `undefined`

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:134026:17)
    at Context.<anonymous> (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:150696:21)
From Your Spec Code:
    at selectMatchingLabel (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1441:39)
    at selectClusterDeployment (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1418:58)
    at gitTasks (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:279:39)
    at createGit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:407:18)
    at createApplication (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:173:5)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:117:46)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm can be created from resource type helm using template editor


```
CypressError: `cy.type()` can only accept a string or number. You passed in: `undefined`

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:134026:17)
    at Context.<anonymous> (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:150696:21)
From Your Spec Code:
    at selectMatchingLabel (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1441:39)
    at selectClusterDeployment (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1418:58)
    at helmTasks (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:377:39)
    at createHelm (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:306:18)
    at createApplication (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:177:5)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:117:46)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-obj can be created from resource type objectstore using template editor


```
CypressError: `cy.type()` can only accept a string or number. You passed in: `undefined`

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:134026:17)
    at Context.<anonymous> (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:150696:21)
From Your Spec Code:
    at selectMatchingLabel (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1441:39)
    at selectClusterDeployment (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1418:58)
    at objTasks (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:456:39)
    at createObj (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:429:18)
    at createApplication (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:175:5)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:117:46)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git


```
CypressError: `cy.exec('oc -n ui-git-ns get subscription ui-git-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:2345:13)
    at validateAdvancedTables (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:484:40)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:118:53)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git-ansible channel, subscription, placement rule info from the advanced configuration tables - git: ui-git-ansible


```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include 'Local'
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1535:107)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm


```
CypressError: `cy.exec('oc -n ui-helm-ns get subscription ui-helm-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-helm-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:2345:13)
    at validateAdvancedTables (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:484:40)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:118:53)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj


```
CypressError: `cy.exec('oc -n ui-obj-ns get subscription ui-obj-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-obj-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:2345:13)
    at validateAdvancedTables (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:484:40)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:118:53)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1244:37)
    at validateResourceTable (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:711:25)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible


```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include 'Local'
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:729:121)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1244:37)
    at validateResourceTable (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:711:25)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2


```
AssertionError: Timed out retrying after 4000ms: expected 'Local' to include 'Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:729:121)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1244:37)
    at validateResourceTable (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:711:25)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git


```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:555:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible


```
AssertionError: expected 0 to be at least 3
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:633:64)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm


```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:555:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2


```
AssertionError: Timed out retrying after 4000ms: Expected to find content: 'Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:624:15)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj


```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:555:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055


```
AssertionError: Timed out retrying after 20000ms: expected '<div#edit-button-portal-id>' to be 'visible'

This element `<div#edit-button-portal-id>` is not visible because it has an effective width and height of: `0 x 0` pixels.
    at validateDefect7696 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:2222:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:129:44)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster


```
AssertionError: Timed out retrying after 4000ms: expected '' to include 'ui-git-subscription-1'
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:290:24)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git


```
CypressError: `cy.exec('oc get subscription ui-git-subscription-1 -n ui-git-ns -o yaml')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:322:12)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm resources created on the target cluster


```
AssertionError: Timed out retrying after 4000ms: expected '' to include 'ui-helm-subscription-1'
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:290:24)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm timewindow - helm: ui-helm


```
CypressError: `cy.exec('oc get subscription ui-helm-subscription-1 -n ui-helm-ns -o yaml')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-helm-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:322:12)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj resources created on the target cluster


```
AssertionError: Timed out retrying after 4000ms: expected '' to include 'ui-obj-subscription-1'
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:290:24)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj timewindow - objectstore: ui-obj


```
CypressError: `cy.exec('oc get subscription ui-obj-subscription-1 -n ui-obj-ns -o yaml')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-obj-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:322:12)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git


```
CypressError: `cy.exec('oc -n ui-git-ns get subscription ui-git-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:238:13)
    at channels (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:256:3)
    at apiResources (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm channels, subscription and placementrule are valid - helm: ui-helm


```
CypressError: `cy.exec('oc -n ui-helm-ns get subscription ui-helm-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-helm-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:238:13)
    at channels (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:256:3)
    at apiResources (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-obj channels, subscription and placementrule are valid - objectstore: ui-obj


```
CypressError: `cy.exec('oc -n ui-obj-ns get subscription ui-obj-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-obj-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:238:13)
    at channels (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:256:3)
    at apiResources (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1243:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:921:25)
    at deleteFirstSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:973:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1243:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:921:25)
    at deleteFirstSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:973:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1243:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:921:25)
    at deleteFirstSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:973:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1243:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:921:25)
    at verifyEditAfterDeleteSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1023:5)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:115:64)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-helm is valid after first subscription is deleted and selecting new placement rule, defect #7359


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1243:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:921:25)
    at verifyEditAfterDeleteSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1023:5)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:115:64)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1243:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:921:25)
    at verifyEditAfterDeleteSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1023:5)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:115:64)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1249:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:927:25)
    at addNewSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1006:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1249:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:927:25)
    at addNewSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1006:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1249:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:927:25)
    at addNewSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1006:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted


```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:548:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted


```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:548:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted


```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:548:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected


```
CypressError: `cy.exec('oc -n ui-git-ns get subscription ui-git-subscription-3 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:2367:13)
    at verifyInsecureSkipAfterNewSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1079:38)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:125:71)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-helm was selected


```
CypressError: `cy.exec('oc -n ui-helm-ns get subscription ui-helm-subscription-3 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-helm-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:2367:13)
    at verifyInsecureSkipAfterNewSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1079:38)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:125:71)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created


```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:568:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:142:47)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1270:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:948:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1064:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm single app page info is valid after new subscription is created


```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:568:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:142:47)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm template editor valid after new subscription is created


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1270:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:948:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1064:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created


```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:568:6)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:142:47)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1270:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:948:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1064:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1237:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:915:25)
    at editApplication (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:936:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm are properly shown in the app Editor


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1237:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:915:25)
    at editApplication (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:936:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor


```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1237:37)
    at edit (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:915:25)
    at editApplication (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:936:3)
    at Context.eval (https://multicloud-console.apps.yhliu-aws1.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```
                        
