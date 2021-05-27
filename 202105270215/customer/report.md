# :warning: Had some failures when running regression on cluster acmqeosd with test snapshot 2.2.3-SNAPSHOT-2021-04-22-06-59-29 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/121/


ACM Version: v2.2.3

Hub Cluster Version: 4.5.30

Hub Cluster: https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com

Managed Cluster Version: v1.18.3+65bd32d

Managed Cluster: https://console-openshift-console.apps.acmqeosd.y0wn.p1.openshiftapps.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202105270215/

## Tests:

|Status|Results|Test|
|---|---|---|
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Check nonexistent URLs |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Create, Search, Verify details of policy |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Delete test policy |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Verify duplicate policy creation in different NS |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Verify summary table |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy name RegEx |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Disable policy: test policy disable + enable |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Clean up |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide admin user |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide cluster-admin user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide edit user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide view user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide view user in a group |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced admin user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced cluster-admin user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced edit user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced view user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced view user in a group |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1622081901 using the form" |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1622081901 using the form" |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1622081901 using the form" |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1622081901 using the form" |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1622081901 using the form" |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy test-imagemanifest-policy-1622081901 using the form" |
| :x: | failed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance "before all" hook for ""Govern risk" page can be launched." |


---

### Failed Test Details

#### :x: GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates

```
    at NightwatchAPI.<anonymous> (/opt/app-root/src/grc-ui/tests/page-objects/AllPolicyPage.js:335:12)
    at processTicksAndRejections (internal/process/task_queues.js:97:5)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] Disable policy: test policy disable + enable

```
    at Page.createPolicy (/opt/app-root/src/grc-ui/tests/page-objects/CommonPage.js:105:8)
    at Object.GRC UI: [P1][Sev1][policy-grc] Disable policy: test policy disable + enable (/opt/app-root/src/grc-ui/tests/e2e/disable.test.js:32:10)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup "before all" hook for "Create the clean up policy using the YAML"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup "before all" hook for "Create the clean up policy using the YAML"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup "before all" hook for "Create the clean up policy using the YAML"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide cluster-admin user

```
    at Page.logout (/opt/app-root/src/grc-ui/tests/page-objects/LoginPage.js:114:8)
    at Object.beforeEach (/opt/app-root/src/grc-ui/tests/e2e/rbac.test.js:56:15)
    at new Promise (<anonymous>)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1622081901 using the form"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1622081901 using the form"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1622081901 using the form"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1622081901 using the form"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1622081901 using the form"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy test-imagemanifest-policy-1622081901 using the form"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

#### :x: RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance "before all" hook for ""Govern risk" page can be launched."

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4134:46)
```

