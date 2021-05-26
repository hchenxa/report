# :warning: Had some failures when running regression on cluster ocp4-gcp-0 with test snapshot 2.0.11-SNAPSHOT-2021-05-21-21-35-58 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/120/


ACM Version: v2.0.11

Hub Cluster Version: 4.6.23

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.7.12

Managed Cluster: https://console-openshift-console.apps.acm-qe-2011-hive-test.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202105261809/

## Tests:

|Status|Results|Test|
|---|---|---|
| :large_blue_circle: | skipped | All policy page: Create, Search, Verify details of policy |
| :large_blue_circle: | skipped | All policy page: Delete test policy |
| :large_blue_circle: | skipped | All policy page: Test pagination |
| :large_blue_circle: | skipped | All policy page: Verify summary table |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add github application |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add github placement rule |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add github subscription |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add helmrepo application |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add helmrepo placement rule |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add helmrepo subscription |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add namespace application |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add namespace placement rule |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add namespace subscription |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add objectbucket application |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add objectbucket placement rule |
| :white_check_mark: | passed | Application Resources Given user logs in as sysadmin, user should be able to add objectbucket subscription |
| :large_blue_circle: | skipped | Cert policy: cert policy should show compliant |
| :large_blue_circle: | skipped | Cert policy: clean up |
| :large_blue_circle: | skipped | Cert policy: create cert policy and should show violation |
| :large_blue_circle: | skipped | Cert policy: create issuer and certificate  |
| :large_blue_circle: | skipped | Cert policy: update certificate and secret |
| :x: | failed | Cluster can be created on Amazon Web Services |
| :x: | failed | Cluster can be created on Google Cloud |
| :x: | failed | Cluster can be created on Microsoft Azure |
| :x: | failed | Cluster can be destroyed on Amazon Web Services |
| :x: | failed | Cluster can be destroyed on Google Cloud |
| :x: | failed | Cluster can be destroyed on Microsoft Azure |
| :x: | failed | Cluster can be detached |
| :x: | failed | Cluster import command can be generated |
| :large_blue_circle: | skipped | Create policy page: Updating YAML in editor |
| :large_blue_circle: | skipped | Create policy page: Verify templates |
| :large_blue_circle: | skipped | Disable policy: test policy disable + enable |
| :large_blue_circle: | skipped | IAM policy: clean up |
| :large_blue_circle: | skipped | IAM policy: create clusterrolebinding as should show violation |
| :large_blue_circle: | skipped | IAM policy: create iam-policy |
| :large_blue_circle: | skipped | IAM policy: delete clusterrolebinding as should show compliant |
| :white_check_mark: | passed | Overview page should load |
| :large_blue_circle: | skipped | Overview: Load page |
| :large_blue_circle: | skipped | Overview: Most impacted controls table |
| :large_blue_circle: | skipped | Overview: Recent activity |
| :large_blue_circle: | skipped | Overview: Run accessibility scan |
| :large_blue_circle: | skipped | Overview: Violation table |
| :large_blue_circle: | skipped | Overview: policy summary table |
| :large_blue_circle: | skipped | Policy controller: all objects of kind / does not exist |
| :large_blue_circle: | skipped | Policy controller: all objects of kind / exists |
| :large_blue_circle: | skipped | Policy controller: single object / musthave + mustnothave |
| :x: | failed | Provider connections page should load |
| :x: | failed | Provider connections should be able to be created for Amazon Web Services |
| :x: | failed | Provider connections should be able to be created for Google Cloud |
| :x: | failed | Provider connections should be able to be created for Microsoft Azure |
| :x: | failed | Provider connections should be able to be deleted for Amazon Web Services |
| :x: | failed | Provider connections should be able to be deleted for Google Cloud |
| :x: | failed | Provider connections should be able to be deleted for Microsoft Azure |
| :x: | failed | Provider connections should be abled to be edited for Amazon Web Services |
| :x: | failed | Provider connections should be abled to be edited for Google Cloud |
| :x: | failed | Provider connections should be abled to be edited for Microsoft Azure |
| :white_check_mark: | passed | Search: Edit secret as admin user |
| :white_check_mark: | passed | Search: Load page as admin user |
| :white_check_mark: | passed | Search: Load page as viewer |
| :white_check_mark: | passed | Search: Search for secret as admin user |
| :white_check_mark: | passed | Search: Viewer is not allowed to edit configmap |
| :large_blue_circle: | skipped | Security findings page: Load and run expand |
| :large_blue_circle: | skipped | Security findings page: Run Accessibility Scan |
| :large_blue_circle: | skipped | Security findings page: Test pagination |
| :large_blue_circle: | skipped | Security findings page: Verify summary table |


---

### Failed Test Details

#### :x: Cluster can be created on Amazon Web Services

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at createCluster (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/02-cluster.spec.js:133:19)
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/02-cluster.spec.js:80:34)
```

#### :x: Cluster can be created on Google Cloud

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at createCluster (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/02-cluster.spec.js:133:19)
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/02-cluster.spec.js:80:34)
```

#### :x: Cluster can be created on Microsoft Azure

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at createCluster (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/02-cluster.spec.js:133:19)
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/02-cluster.spec.js:80:34)
```

#### :x: Cluster can be destroyed on Amazon Web Services

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-destroy/cluster-destroy.spec.js:356:40)
```

#### :x: Cluster can be destroyed on Google Cloud

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-destroy/cluster-destroy.spec.js:356:40)
```

#### :x: Cluster can be destroyed on Microsoft Azure

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-destroy/cluster-destroy.spec.js:356:40)
```

#### :x: Cluster can be detached

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-destroy/import-detach.spec.js:377:40)
```

#### :x: Cluster import command can be generated

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at generateClusterImport (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-import/import.spec.js:207:19)
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/02-import/import.spec.js:85:42)
```

#### :x: Provider connections page should load

```
AssertionError: Timed out retrying: Expected <div.bx--loading.content-spinner> not to exist in the DOM, but it was continuously found.
    at Object.shouldNotExist (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:179:8)
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:118:24)
```

#### :x: Provider connections should be able to be created for Amazon Web Services

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at createConnection (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:358:36)
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:127:40)
```

#### :x: Provider connections should be able to be created for Google Cloud

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at createConnection (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:358:36)
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:127:40)
```

#### :x: Provider connections should be able to be created for Microsoft Azure

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at createConnection (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:358:36)
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:127:40)
```

#### :x: Provider connections should be able to be deleted for Amazon Web Services

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-destroy/connection-destroy.spec.js:173:40)
```

#### :x: Provider connections should be able to be deleted for Google Cloud

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-destroy/connection-destroy.spec.js:173:40)
```

#### :x: Provider connections should be able to be deleted for Microsoft Azure

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/04-destroy/connection-destroy.spec.js:173:40)
```

#### :x: Provider connections should be abled to be edited for Amazon Web Services

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:233:40)
```

#### :x: Provider connections should be abled to be edited for Google Cloud

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:233:40)
```

#### :x: Provider connections should be abled to be edited for Microsoft Azure

```
CypressError: `cy.type()` cannot accept an empty string. You need to actually type something.

https://on.cypress.io/type
    at Context.type (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:152348:17)
    at Context.<anonymous> (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:167681:21)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-gcp-0.gcp.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/01-create/01-connection.spec.js:233:40)
```

