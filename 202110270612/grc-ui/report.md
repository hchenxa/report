# :warning: Had some failures when running regression on cluster ocp4-az-01 with test snapshot 2.3.0-SNAPSHOT-2021-04-17-07-15-32 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/364/


ACM Version: v2.4.0

Hub Cluster Version: 4.6.46

Hub Cluster: https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.8.11

Managed Cluster: https://console-openshift-console.apps.acmqe-24-rc-hive-aws.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110270612/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-certificate-1635315274 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-issuer-1635315274 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-certificate-1635315274 |
| :x: | failed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1635315274 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-certificate-1635315274 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-issuer-1635315274 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1635315274 status to become available |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1635315274 status to become available |
| :x: | failed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup "before all" hook for "Create the clean up policy using the YAML" |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1635315274 status becomes available |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1635315274 is not present |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Delete created policy policy-certificatepolicy-rhacm4k-1205-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1635315274 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1635315274 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1635315274 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1635315274 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Check created policy policy-certificatepolicy-1635315274 is not present |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Check enabled policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Create certificate policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Delete created policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Edit policy policy-certificatepolicy-1635315274 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Validate disable of the policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Validate enable of the policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Validate violations/status of created policy policy-certificatepolicy-1635315274 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Validate violations/status of created policy policy-certificatepolicy-1635315274 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Verify all information about the created certificate policy policy-certificatepolicy-1635315274 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Wait for certificate policy policy-certificatepolicy-1635315274 status to become available |
| :x: | failed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector "before all" hook for "Prefill a new policy test-issue3677-cert-policy-1635315274 using the form" |
| :x: | failed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected "before all" hook for "Create the clean up policy using the YAML" |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1635315274 using the form" |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1635315274 using the form" |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1635315274 using the form" |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1635315274 using the form" |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1635315274 is not present |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create certificate policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Delete created policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1635315274 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1635315274 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1635315274 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1635315274 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1635315274 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Wait for certificate policy policy-certificatepolicy-1635315274 status to become available |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon "Govern risk" page can be launched. |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-certificate-1635315274 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-issuer-1635315274 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-certificate-1635315274 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-issuer-1635315274 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-certificate-1635315274 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-issuer-1635315274 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1635315274 status to become available |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1635315274 status to become available |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests "before all" hook for "Verify that CYPRESS_RBAC_PASS environment variable is defined" |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load" |
| :x: | failed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster "before all" hook for "Creates the policy using the YAML" |
| :x: | failed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation "before all" hook for "Create Pod policy issue2444-1635315274-pod-policy from YAML, expecting a compliance" |
| :x: | failed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly "before all" hook for "Access the Create policy page" |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1635315274 using the form" |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy t-imp-1635315274 using the form" |
| :x: | failed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS "before all" hook for "Create Namespace policy to create template ns as duplicatetest" |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1635315274 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1635315274 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1635315274 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1635315274 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1635315274 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1635315274 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1635315274 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1635315274 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1635315274 status to become available |
| :x: | failed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations "before all" hook for "Check that invalid policy name pattern issues an error" |
| :x: | failed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor "before all" hook for "Access the Create policy page" |
| :x: | failed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit" |
| :x: | failed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates "before all" hook for "Verify YAML template for IamPolicy specification" |
| :x: | failed | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml "before all" hook for "Create policy should fail with invalid policy name in yaml" |
| :x: | failed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1635315274 into YAML editor" |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy policy-create-credential-1635315274 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy policy-create-subscription-1635315274 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy to-automate-1635315274 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create a subscription to install the Ansible operator |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create the credential policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Creates the policy to automate using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-create-credential-1635315274 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-create-subscription-1635315274 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-delete-subscription-1635315274 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy to-automate-1635315274 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Enforce policy-create-credential-1635315274 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Enforce policy-delete-subscription-1635315274 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Prompts the user to install the ansible operator |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Skips install prompt if the ansible operator is installed |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "manual" automation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "run once" automation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a disabled automation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verifies successful job history with mock |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-create-credential-1635315274 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-create-subscription-1635315274 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-delete-subscription-1635315274 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy to-automate-1635315274 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-credential-1635315274 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-credential-1635315274 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-subscription-1635315274 status to become available |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-delete-subscription-1635315274 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-delete-subscription-1635315274 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for to-automate-1635315274 status to become available |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal verifies sidebar credentials after creation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal verifies sidebar credentials not existing |


---

### Failed Test Details

#### :x: @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1635315274

```
AssertionError: Timed out retrying after 30000ms: Expected <div#remove-resource-modal.pf-c-modal-box.pf-m-warning.pf-m-md> not to exist in the DOM, but it was continuously found.
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12653:31)
```

#### :x: @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup "before all" hook for "Create the clean up policy using the YAML"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11646:12)
```

#### :x: @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup "before all" hook for "Create the clean up policy using the YAML"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup "before all" hook for "Create the clean up policy using the YAML"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector "before all" hook for "Prefill a new policy test-issue3677-cert-policy-1635315274 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

This http request was redirected '1' time to:

  - 301: https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies/

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected "before all" hook for "Create the clean up policy using the YAML"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance "before all" hook for "Create new policy test-pod-security-policy-1635315274 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1635315274 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1635315274 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1635315274 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests "before all" hook for "Verify that CYPRESS_RBAC_PASS environment variable is defined"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster "before all" hook for "Creates the policy using the YAML"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

This http request was redirected '1' time to:

  - 301: https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies/

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation "before all" hook for "Create Pod policy issue2444-1635315274-pod-policy from YAML, expecting a compliance"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly "before all" hook for "Access the Create policy page"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance "before all" hook for "Create new policy test-pod-policy-1635315274 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

This http request was redirected '1' time to:

  - 301: https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies/

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance "before all" hook for "Create new policy t-imp-1635315274 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS "before all" hook for "Create Namespace policy to create template ns as duplicatetest"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations "before all" hook for "Check that invalid policy name pattern issues an error"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor "before all" hook for "Access the Create policy page"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11646:12)
```

#### :x: RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates "before all" hook for "Verify YAML template for IamPolicy specification"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml "before all" hook for "Create policy should fail with invalid policy name in yaml"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

#### :x: RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1635315274 into YAML editor"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/multicloud/policies

The response we received from your web server was:

  > 502: Bad Gateway

This was considered a failure because the status code was not `2xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144021:25
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:143396:12)
    at https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:13
    at tryCatcher (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:13212:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11147:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11204:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11249:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:11325:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7919:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7912:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7928:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:7798:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11637:6)
```

