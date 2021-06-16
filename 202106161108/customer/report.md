# :warning: Had some failures when running regression on cluster ocp4-az-11 with test snapshot 2.1.8-SNAPSHOT-2021-06-15-13-55-18 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/133/


ACM Version: v2.1.8

Hub Cluster Version: 4.7.3

Hub Cluster: https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.7.12

Managed Cluster: https://console-openshift-console.apps.acm-qe-218-hive.gcp.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202106161108/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Application can be created on resource git from the wizard |
| :white_check_mark: | passed | Application can be created on resource helm from the wizard |
| :white_check_mark: | passed | Application can be created on resource objectstore from the wizard |
| :white_check_mark: | passed | Application channels, subscription and placementrule - should be validated - git: ui-git |
| :white_check_mark: | passed | Application channels, subscription and placementrule - should be validated - helm: ui-helm |
| :white_check_mark: | passed | Application channels, subscription and placementrule - should be validated - objectstore: ui-obj |
| :white_check_mark: | passed | Application get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application resource should be validated on the target cluster |
| :white_check_mark: | passed | Application should be validated from the advanced configuration tables - git: ui-git |
| :white_check_mark: | passed | Application should be validated from the advanced configuration tables - helm: ui-helm |
| :white_check_mark: | passed | Application should be validated from the advanced configuration tables - objectstore: ui-obj |
| :x: | failed | Application should be validated from the resource table - git: ui-git |
| :white_check_mark: | passed | Application should be validated from the resource table - helm: ui-helm |
| :white_check_mark: | passed | Application should be validated from the resource table - objectstore: ui-obj |
| :x: | failed | Application should be validated from the topology - git: ui-git |
| :white_check_mark: | passed | Application should be validated from the topology - helm: ui-helm |
| :white_check_mark: | passed | Application should be validated from the topology - objectstore: ui-obj |
| :white_check_mark: | passed | Application timewindow - should be validated - git: ui-git |
| :white_check_mark: | passed | Application timewindow - should be validated - helm: ui-helm |
| :white_check_mark: | passed | Application timewindow - should be validated - objectstore: ui-obj |
| :white_check_mark: | passed | Bare metal assets can be added |
| :white_check_mark: | passed | Bare metal assets can be deleted |
| :white_check_mark: | passed | Bare metal assets page should load |
| :white_check_mark: | passed | Cleanup resouces delete namepsace ui-git-ns on hub cluster |
| :white_check_mark: | passed | Cleanup resouces delete namepsace ui-helm-ns on hub cluster |
| :white_check_mark: | passed | Cleanup resouces delete namepsace ui-obj-ns on hub cluster |
| :white_check_mark: | passed | Cleanup resouces delete namespace ui-git-ns on target cluster |
| :white_check_mark: | passed | Cleanup resouces delete namespace ui-helm-ns on target cluster |
| :white_check_mark: | passed | Cleanup resouces delete namespace ui-obj-ns on target cluster |
| :x: | failed | Cluster details page should display accordingly with the cluster status - [object Object] |
| :x: | failed | Clusters can be created for bare-metal |
| :x: | failed | Clusters can be created on Amazon Web Services |
| :x: | failed | Clusters can be created on Google Cloud |
| :x: | failed | Clusters can be created on Microsoft Azure |
| :x: | failed | Clusters can be created on VMware vSphere |
| :x: | failed | Clusters can be destroyed for bare-metal |
| :x: | failed | Clusters can be destroyed on Amazon Web Services |
| :x: | failed | Clusters can be destroyed on Google Cloud |
| :x: | failed | Clusters can be destroyed on Microsoft Azure |
| :x: | failed | Clusters can be destroyed on VMware vSphere |
| :white_check_mark: | passed | Clusters page should load |
| :x: | failed | Delete application ui-git should be deleted from UI |
| :white_check_mark: | passed | Delete application ui-helm should be deleted from UI |
| :white_check_mark: | passed | Delete application ui-obj should be deleted from UI |
| :x: | failed | Edit application ui-git should be editable |
| :x: | failed | Edit application ui-git should be verified after edit |
| :white_check_mark: | passed | Edit application ui-helm should be editable |
| :white_check_mark: | passed | Edit application ui-helm should be verified after edit |
| :white_check_mark: | passed | Edit application ui-obj should be editable |
| :white_check_mark: | passed | Edit application ui-obj should be verified after edit |
| :white_check_mark: | passed | Observability: Case 01 - MCO Operator is created |
| :white_check_mark: | passed | Observability: Case 02 - Required CRDs are created |
| :x: | failed | Observability: Case 03 - All required components are deployed and running |
| :white_check_mark: | passed | Observability: Case 04 - Grafana console can be accessible |
| :white_check_mark: | passed | Observability: Case 05 - retentionResolutionRaw is modified |
| :white_check_mark: | passed | Observability: Case 06 - Managed cluster metrics shows up in Grafana console |
| :white_check_mark: | passed | Observability: Case 07 - Disable observabilityaddon |
| :white_check_mark: | passed | Observability: Case 08 - Modify availabilityConfig from High to Basic |
| :white_check_mark: | passed | Overview page should load |
| :white_check_mark: | passed | Provider connection page should load |
| :white_check_mark: | passed | Provider connection should allow adding bare metal provider connection |
| :white_check_mark: | passed | Provider connection should allow deleting bare metal provider connection |
| :white_check_mark: | passed | Provider connections page should load |
| :x: | failed | Provider connections should be able to be created for Amazon Web Services |
| :x: | failed | Provider connections should be able to be created for Google Cloud |
| :x: | failed | Provider connections should be able to be created for Microsoft Azure |
| :x: | failed | Provider connections should be able to be created for VMware vSphere |
| :x: | failed | Provider connections should be able to be deleted for Amazon Web Services |
| :x: | failed | Provider connections should be able to be deleted for Google Cloud |
| :x: | failed | Provider connections should be able to be deleted for Microsoft Azure |
| :x: | failed | Provider connections should be able to be deleted for VMware vSphere |
| :x: | failed | Provider connections should be able to be edited for Amazon Web Services |
| :x: | failed | Provider connections should be able to be edited for Google Cloud |
| :x: | failed | Provider connections should be able to be edited for Microsoft Azure |
| :x: | failed | Provider connections should be able to be edited for VMware vSphere |
| :white_check_mark: | passed | Visual Web Terminal: Verify KUI getting started command |
| :white_check_mark: | passed | Visual Web Terminal: Verify KUI multiple tabs |
| :white_check_mark: | passed | Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | Visual Web Terminal: Verify commands are disabled - rbash |
| :white_check_mark: | passed | Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons |
| :white_check_mark: | passed | Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | Visual Web Terminal: Verify kubectl |
| :white_check_mark: | passed | Visual Web Terminal: Verify oc |
| :white_check_mark: | passed | Visual Web Terminal: Verify product header |
| :white_check_mark: | passed | Visual Web Terminal: Verify supported CLIs can execute |
| :white_check_mark: | passed | Visual Web Terminal: Verify supported themes |
| :white_check_mark: | passed | Visual Web Terminal: Verify user home folder permissions |


---

### Failed Test Details

#### :x: Application can be created on resource git from the wizard

```
AssertionError: Timed out retrying: Expected to find element: `.bx--inline-notification[kind="success"]`, but never found it.
    at Object.shouldExist (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1935:8)
    at submitSave (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1329:24)
    at createApplication (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1153:3)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/01-create/01-wizard.spec.js:1087:44)
```

#### :x: Application should be validated from the resource table - git: ui-git

```
AssertionError: Timed out retrying: Expected to find element: `tr[data-row-name="ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui.spect.js:1799:8)
    at validateResourceTable (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui.spect.js:1517:25)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui.spect.js:1086:48)
```

#### :x: Application should be validated from the topology - git: ui-git

```
AssertionError: Timed out retrying: Expected to find element: `.toggle-subs-btn.bx--btn.bx--btn--primary`, but never found it.
    at validateSubscriptionDetails (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui.spect.js:1347:6)
    at validateTopology (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui.spect.js:1431:3)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui.spect.js:1089:43)
```

#### :x: Cluster details page should display accordingly with the cluster status - [object Object]

```
AssertionError: Timed out retrying: Expected to find element: `.table-status-text`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-validate/cluster-details.spec.js:1392:12)
```

#### :x: Clusters can be created for bare-metal

```
AssertionError: expected 'Pending' to equal 'Ready'
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/baremetal/03-bm-spoke-create.spec.js:624:34)
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
AssertionError: Timed out retrying: Expected <tr.bx--parent-row-v2.row-not-expanded> not to exist in the DOM, but it was continuously found.
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/baremetal/04-bm-spoke-delete.spec.js:655:85)
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

#### :x: Delete application ui-git should be deleted from UI

```
AssertionError: Timed out retrying: Expected to find element: `tr[data-row-name="ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/04-delete/01-delete-app.spec.js:1788:8)
    at deleteApplicationUI (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/04-delete/01-delete-app.spec.js:1521:27)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/04-delete/01-delete-app.spec.js:1081:46)
```

#### :x: Edit application ui-git should be editable

```
AssertionError: Timed out retrying: Expected to find element: `tr[data-row-name="ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-edit-application.spec.js:1791:8)
    at edit (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-edit-application.spec.js:1651:25)
    at editApplication (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-edit-application.spec.js:1667:3)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-edit-application.spec.js:1081:42)
```

#### :x: Edit application ui-git should be verified after edit

```
AssertionError: Timed out retrying: Expected to find element: `tr[data-row-name="ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-edit-application.spec.js:1791:8)
    at edit (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-edit-application.spec.js:1651:25)
    at verifyEdit (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-edit-application.spec.js:1724:5)
    at Context.eval (https://multicloud-console.apps.ocp4-az-11.az.dev06.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-edit-application.spec.js:1084:37)
```

#### :x: Observability: Case 03 - All required components are deployed and running

```
/go/src/github.com/open-cluster-management/observability-e2e-test/observability_test.go:65
Unexpected error:
    <*errors.errorString | 0xc000116080>: {
        s: "failed to get s3 BUCKET env",
    }
    failed to get s3 BUCKET env
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/observability_test.go:68
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

