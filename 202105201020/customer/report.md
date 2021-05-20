# :warning: Had some failures when running regression on cluster ocp4-az-11 with test snapshot 2.1.7-SNAPSHOT-2021-05-17-17-29-12 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/118/


ACM Version: v2.1.7

Hub Cluster Version: 4.7.3

Hub Cluster: https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.7.9

Managed Cluster: https://console-openshift-console.apps.acm-qe-217-hive-test.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202105201020/

## Tests:

|Results|Test|
|---|---|
| :white_check_mark: | Application can be created on resource git from the wizard |
| :white_check_mark: | Application can be created on resource helm from the wizard |
| :white_check_mark: | Application can be created on resource objectstore from the wizard |
| :white_check_mark: | Application channels, subscription and placementrule - should be validated - git: ui-git |
| :white_check_mark: | Application channels, subscription and placementrule - should be validated - helm: ui-helm |
| :white_check_mark: | Application channels, subscription and placementrule - should be validated - objectstore: ui-obj |
| :white_check_mark: | Application get the name of the managed OCP cluster |
| :white_check_mark: | Application resource should be validated on the target cluster |
| :white_check_mark: | Application should be validated from the advanced configuration tables - git: ui-git |
| :white_check_mark: | Application should be validated from the advanced configuration tables - helm: ui-helm |
| :white_check_mark: | Application should be validated from the advanced configuration tables - objectstore: ui-obj |
| :white_check_mark: | Application should be validated from the resource table - git: ui-git |
| :white_check_mark: | Application should be validated from the resource table - helm: ui-helm |
| :white_check_mark: | Application should be validated from the resource table - objectstore: ui-obj |
| :white_check_mark: | Application should be validated from the topology - git: ui-git |
| :white_check_mark: | Application should be validated from the topology - helm: ui-helm |
| :white_check_mark: | Application should be validated from the topology - objectstore: ui-obj |
| :white_check_mark: | Application timewindow - should be validated - git: ui-git |
| :white_check_mark: | Application timewindow - should be validated - helm: ui-helm |
| :white_check_mark: | Application timewindow - should be validated - objectstore: ui-obj |
| :white_check_mark: | Bare metal assets can be added |
| :white_check_mark: | Bare metal assets can be deleted |
| :white_check_mark: | Bare metal assets page should load |
| :white_check_mark: | Cleanup resouces delete namepsace ui-git-ns on hub cluster |
| :white_check_mark: | Cleanup resouces delete namepsace ui-helm-ns on hub cluster |
| :white_check_mark: | Cleanup resouces delete namepsace ui-obj-ns on hub cluster |
| :white_check_mark: | Cleanup resouces delete namespace ui-git-ns on target cluster |
| :white_check_mark: | Cleanup resouces delete namespace ui-helm-ns on target cluster |
| :white_check_mark: | Cleanup resouces delete namespace ui-obj-ns on target cluster |
| :x: | Cluster details page should display accordingly with the cluster status - [object Object] |
| :x: | Clusters can be created for bare-metal |
| :x: | Clusters can be created on Amazon Web Services |
| :x: | Clusters can be created on Google Cloud |
| :x: | Clusters can be created on Microsoft Azure |
| :x: | Clusters can be created on VMware vSphere |
| :x: | Clusters can be destroyed for bare-metal |
| :x: | Clusters can be destroyed on Amazon Web Services |
| :x: | Clusters can be destroyed on Google Cloud |
| :x: | Clusters can be destroyed on Microsoft Azure |
| :x: | Clusters can be destroyed on VMware vSphere |
| :white_check_mark: | Clusters page should load |
| :white_check_mark: | Delete application ui-git should be deleted from UI |
| :white_check_mark: | Delete application ui-helm should be deleted from UI |
| :white_check_mark: | Delete application ui-obj should be deleted from UI |
| :white_check_mark: | Edit application ui-git should be editable |
| :white_check_mark: | Edit application ui-git should be verified after edit |
| :white_check_mark: | Edit application ui-helm should be editable |
| :white_check_mark: | Edit application ui-helm should be verified after edit |
| :white_check_mark: | Edit application ui-obj should be editable |
| :white_check_mark: | Edit application ui-obj should be verified after edit |
| :white_check_mark: | Overview page should load |
| :white_check_mark: | Provider connection page should load |
| :white_check_mark: | Provider connection should allow adding bare metal provider connection |
| :white_check_mark: | Provider connection should allow deleting bare metal provider connection |
| :white_check_mark: | Provider connections page should load |
| :x: | Provider connections should be able to be created for Amazon Web Services |
| :x: | Provider connections should be able to be created for Google Cloud |
| :x: | Provider connections should be able to be created for Microsoft Azure |
| :x: | Provider connections should be able to be created for VMware vSphere |
| :x: | Provider connections should be able to be deleted for Amazon Web Services |
| :x: | Provider connections should be able to be deleted for Google Cloud |
| :x: | Provider connections should be able to be deleted for Microsoft Azure |
| :x: | Provider connections should be able to be deleted for VMware vSphere |
| :x: | Provider connections should be able to be edited for Amazon Web Services |
| :x: | Provider connections should be able to be edited for Google Cloud |
| :x: | Provider connections should be able to be edited for Microsoft Azure |
| :x: | Provider connections should be able to be edited for VMware vSphere |
| :white_check_mark: | Visual Web Terminal: Verify KUI getting started command |
| :white_check_mark: | Visual Web Terminal: Verify KUI multiple tabs |
| :white_check_mark: | Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons |
| :white_check_mark: | Visual Web Terminal: Verify commands are disabled - rbash |
| :white_check_mark: | Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons |
| :white_check_mark: | Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons |
| :white_check_mark: | Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | Visual Web Terminal: Verify kubectl |
| :white_check_mark: | Visual Web Terminal: Verify oc |
| :white_check_mark: | Visual Web Terminal: Verify product header |
| :white_check_mark: | Visual Web Terminal: Verify supported CLIs can execute |
| :white_check_mark: | Visual Web Terminal: Verify supported themes |
| :white_check_mark: | Visual Web Terminal: Verify user home folder permissions |


---

### Failed Test Details

#### :x: Cluster details page should display accordingly with the cluster status - [object Object]


```
AssertionError: Timed out retrying: Expected to find element: `.table-status-text`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-validate/cluster-details.spec.js:1392:12)
```
                        
#### :x: Clusters can be created for bare-metal


```
AssertionError: Timed out retrying: Expected to find element: `.bx--inline-notification[kind="success"]`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/baremetal/03-bm-spoke-create.spec.js:911:8)
    at createClusterBareMetal (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/baremetal/03-bm-spoke-create.spec.js:448:24)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/baremetal/03-bm-spoke-create.spec.js:231:41)
```
                        
#### :x: Clusters can be created on Amazon Web Services


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at createCluster (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-cluster.spec.js:330:19)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-cluster.spec.js:222:34)
```
                        
#### :x: Clusters can be created on Google Cloud


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at createCluster (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-cluster.spec.js:330:19)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-cluster.spec.js:222:34)
```
                        
#### :x: Clusters can be created on Microsoft Azure


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at createCluster (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-cluster.spec.js:330:19)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-cluster.spec.js:222:34)
```
                        
#### :x: Clusters can be created on VMware vSphere


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at createCluster (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-cluster.spec.js:330:19)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/02-cluster.spec.js:222:34)
```
                        
#### :x: Clusters can be destroyed for bare-metal


```
AssertionError: Timed out retrying: Expected to find element: `button[data-table-action="table.actions.cluster.destroy"]`, but never found it.
    at Object.menuClickDestroy (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/baremetal/04-bm-spoke-delete.spec.js:789:15)
    at eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/baremetal/04-bm-spoke-delete.spec.js:437:27)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/baremetal/04-bm-spoke-delete.spec.js:929:7)
```
                        
#### :x: Clusters can be destroyed on Amazon Web Services


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Clusters can be destroyed on Google Cloud


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Clusters can be destroyed on Microsoft Azure


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Clusters can be destroyed on VMware vSphere


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Provider connections should be able to be created for Amazon Web Services


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at createConnection (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-connection.spec.js:583:36)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-connection.spec.js:234:40)
```
                        
#### :x: Provider connections should be able to be created for Google Cloud


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at createConnection (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-connection.spec.js:583:36)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-connection.spec.js:234:40)
```
                        
#### :x: Provider connections should be able to be created for Microsoft Azure


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at createConnection (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-connection.spec.js:583:36)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-connection.spec.js:234:40)
```
                        
#### :x: Provider connections should be able to be created for VMware vSphere


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at createConnection (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-connection.spec.js:583:36)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-connection.spec.js:234:40)
```
                        
#### :x: Provider connections should be able to be deleted for Amazon Web Services


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Provider connections should be able to be deleted for Google Cloud


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Provider connections should be able to be deleted for Microsoft Azure


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Provider connections should be able to be deleted for VMware vSphere


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Provider connections should be able to be edited for Amazon Web Services


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Provider connections should be able to be edited for Google Cloud


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Provider connections should be able to be edited for Microsoft Azure


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
#### :x: Provider connections should be able to be edited for VMware vSphere


```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:153678:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:170188:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:312:20)
```
                        
