# :warning: Had some failures when running regression on cluster acm-hub-47 with test snapshot 2.3.0-SNAPSHOT-2021-06-01-10-24-07 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/131/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.8

Hub Cluster: https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com

Managed Cluster Version: 4.7.12

Managed Cluster: https://console-openshift-console.apps.acm-spoke-47.mon01.ibm-power-acm.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202106160305/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: | failed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: | failed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :x: | failed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-certificate-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-issuer-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-certificate-1623812844 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1623812844 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-certificate-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-issuer-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1623812844 status to become available |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Check that policy role-binding-cleanup-policy-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Delete policy role-binding-cleanup-policy-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Verify that policy role-binding-cleanup-policy-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Wait for role-binding-cleanup-policy-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Check that policy role-specification-cleanup-policy-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Delete policy role-specification-cleanup-policy-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Verify that policy role-specification-cleanup-policy-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Wait for role-specification-cleanup-policy-1623812844 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Check that policy scc-cleanup-policy-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Delete policy scc-cleanup-policy-1623812844 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Verify that policy scc-cleanup-policy-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Wait for scc-cleanup-policy-1623812844 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Check that policy test-issue3677-cert-policy-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Create a customized policy |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Delete policy test-issue3677-cert-policy-1623812844 |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Deleted policy test-issue3677-cert-policy-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Prefill a new policy test-issue3677-cert-policy-1623812844 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Replace namespaceSelector value with "no-such-namespace" |
| :x: | failed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1623812844 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Wait for policy test-issue3677-cert-policy-1623812844 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1623812844-create-cert-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1623812844-create-cert-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1623812844-create-issuer-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1623812844-create-issuer-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1623812844-create-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1623812844-create-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1623812844-delete-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1623812844-delete-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1623812844-create-cert-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1623812844-create-cert-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1623812844-create-issuer-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1623812844-create-issuer-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1623812844-create-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1623812844-create-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1623812844-delete-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1623812844-delete-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Remove cert policy issue7520-1623812844-cert-policy |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1623812844-create-cert-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1623812844-create-cert-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1623812844-create-issuer-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1623812844-create-issuer-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1623812844-create-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1623812844-create-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1623812844-delete-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1623812844-delete-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1623812844-create-cert-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1623812844-create-cert-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1623812844-create-issuer-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1623812844-create-issuer-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1623812844-create-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1623812844-create-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1623812844-delete-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1623812844-delete-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show compliance again |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected create certPolicy issue7520-1623812844-cert-policy, expecting a compliance |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster acm-spoke-47 violations |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster acm-spoke-48 violations |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster local-cluster violations |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1623812844 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1623812844 is not present in the policy listing |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1623812844 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1623812844 details at the detailed page |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1623812844 violations at the Status - Clusters page |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1623812844 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1623812844 cluster acm-spoke-47 template test-iam-policy-1623812844-limit-clusteradmin |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1623812844 cluster acm-spoke-48 template test-iam-policy-1623812844-limit-clusteradmin |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1623812844 cluster local-cluster template test-iam-policy-1623812844-limit-clusteradmin |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for cluster violation status to become available |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1623812844 status to become available |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster acm-spoke-47 violations |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster acm-spoke-48 violations |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster local-cluster violations |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1623812844 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1623812844 is not present in the policy listing |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1623812844 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1623812844 details at the detailed page |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1623812844 violations at the Status - Clusters page |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1623812844 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1623812844 cluster acm-spoke-47 template test-pod-security-policy-1623812844-restricted-psp |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1623812844 cluster acm-spoke-48 template test-pod-security-policy-1623812844-restricted-psp |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1623812844 cluster local-cluster template test-pod-security-policy-1623812844-restricted-psp |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for cluster violation status to become available |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1623812844 status to become available |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster acm-spoke-47 violations |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster acm-spoke-48 violations |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster local-cluster violations |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check disabled policy test-role-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that enforced policy test-role-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that policy test-role-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Create new policy test-role-policy-1623812844 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Deleted policy test-role-policy-1623812844 is not present in the policy listing |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Disable policy test-role-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enable policy test-role-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enforce policy test-role-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Policy test-role-policy-1623812844 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1623812844 details at the detailed page |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1623812844 violations at the Status - Clusters page |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1623812844 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1623812844 cluster acm-spoke-47 template test-role-policy-1623812844-deployments-role |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1623812844 cluster acm-spoke-48 template test-role-policy-1623812844-deployments-role |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1623812844 cluster local-cluster template test-role-policy-1623812844-deployments-role |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for cluster violation status to become available |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1623812844 status to become available |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster acm-spoke-47 violations |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster acm-spoke-48 violations |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster local-cluster violations |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check disabled policy test-role-binding-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that enforced policy test-role-binding-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that policy test-role-binding-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Create new policy test-role-binding-policy-1623812844 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Deleted policy test-role-binding-policy-1623812844 is not present in the policy listing |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Disable policy test-role-binding-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enable policy test-role-binding-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enforce policy test-role-binding-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Policy test-role-binding-policy-1623812844 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1623812844 details at the detailed page |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1623812844 violations at the Status - Clusters page |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1623812844 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1623812844 cluster acm-spoke-47 template test-role-binding-policy-1623812844-operatoruser-rolebinding |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1623812844 cluster acm-spoke-48 template test-role-binding-policy-1623812844-operatoruser-rolebinding |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1623812844 cluster local-cluster template test-role-binding-policy-1623812844-operatoruser-rolebinding |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for cluster violation status to become available |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for policy test-role-binding-policy-1623812844 status to become available |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster acm-spoke-47 violations |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster acm-spoke-48 violations |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster local-cluster violations |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check disabled policy test-security-context-constraints-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that enforced policy test-security-context-constraints-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that policy test-security-context-constraints-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Create new policy test-security-context-constraints-policy-1623812844 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Deleted policy test-security-context-constraints-policy-1623812844 is not present in the policy listing |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Disable policy test-security-context-constraints-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enable policy test-security-context-constraints-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enforce policy test-security-context-constraints-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Policy test-security-context-constraints-policy-1623812844 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1623812844 details at the detailed page |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1623812844 violations at the Status - Clusters page |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1623812844 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1623812844 cluster acm-spoke-47 template test-security-context-constraints-policy-1623812844-restricted-scc |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1623812844 cluster acm-spoke-48 template test-security-context-constraints-policy-1623812844-restricted-scc |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1623812844 cluster local-cluster template test-security-context-constraints-policy-1623812844-restricted-scc |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for cluster violation status to become available |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for policy test-security-context-constraints-policy-1623812844 status to become available |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster acm-spoke-47 violations |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster acm-spoke-48 violations |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster local-cluster violations |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1623812844 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1623812844 is not present in the policy listing |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1623812844 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1623812844 details at the detailed page |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1623812844 violations at the Status - Clusters page |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1623812844 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1623812844 cluster acm-spoke-47 template test-namespace-policy-1623812844-prod-ns |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1623812844 cluster acm-spoke-48 template test-namespace-policy-1623812844-prod-ns |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1623812844 cluster local-cluster template test-namespace-policy-1623812844-prod-ns |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for cluster violation status to become available |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1623812844 status to become available |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster acm-spoke-47 violations |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster acm-spoke-48 violations |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster local-cluster violations |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1623812844 is present in the policy listing |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1623812844 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1623812844 is not present in the policy listing |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1623812844 |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1623812844 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1623812844 details at the detailed page |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1623812844 violations at the Status - Clusters page |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1623812844 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1623812844 cluster acm-spoke-47 template test-limitrange-policy-1623812844-container-mem-limit-range |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1623812844 cluster acm-spoke-48 template test-limitrange-policy-1623812844-container-mem-limit-range |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1623812844 cluster local-cluster template test-limitrange-policy-1623812844-container-mem-limit-range |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for cluster violation status to become available |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1623812844 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1623812844 is not present |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1623812844 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create certificate policy policy-certificatepolicy-1623812844 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1623812844 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-1623812844 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1623812844 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1623812844 |
| :x: | failed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1623812844 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1623812844 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1623812844 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Wait for certificate policy policy-certificatepolicy-1623812844 status to become available |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1623812844 status becomes available |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1623812844 is not present |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1623812844 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1623812844 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1623812844 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-rhacm4k-1205-1623812844 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1623812844 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1623812844 |
| :x: | failed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1623812844 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1623812844 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1623812844 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon "Govern risk" page can be launched. |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-certificate-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-issuer-1623812844 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-certificate-1623812844 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-issuer-1623812844 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-certificate-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-issuer-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1623812844 status to become available |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1623812844 status to become available |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy Status page as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1623812844-e2e-rbac-test-1 policy edit page as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Create policies used for the testing |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login again as kubeadmin |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-admin-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-admin-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-cluster-admin-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-cluster-admin-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-edit-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-edit-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-group-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-group-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-view-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-view-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-admin-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-admin-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-cluster-admin-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-cluster-admin-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-edit-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-edit-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-group-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-group-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-view-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-view-ns user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Remove test policies |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Verify that CYPRESS_RBAC_PASS environment variable is defined |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1623812844 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1623812844 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1623812844 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1623812844 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1623812844 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1623812844 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1623812844 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P1][Sev1][policy-grc] should load |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should not show perspective switcher on kube >1.2 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should open left navigation |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should show perspective switcher on kube 1.2 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Create page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Info page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Search page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to User page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Applications page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Clusters page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to GRC page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Home page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to KUI |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Overview page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to credentials page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page validate links on Welcome page |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Create Pod policy issue2444-1623812844-pod-policy from YAML, expecting a compliance |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Delete Pod policy issue2444-1623812844-pod-policy |
| :x: | failed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Check Specifications CertificatePolicy,EtcdEncryption |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Category PR.DS Data Security has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Controls PR.DS-1 Data-at-rest,PR.DS-2 Data-in-transit have been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Specifications CertificatePolicy,EtcdEncryption are selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Standard NIST-CSF has been pre-selected |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster acm-spoke-47 violations |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster acm-spoke-48 violations |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster local-cluster violations |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1623812844 |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1623812844 |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1623812844 is present in the policy listing |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1623812844 is present in the policy listing |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1623812844 using the form |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1623812844 is not present in the policy listing |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1623812844 |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1623812844 |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1623812844 |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1623812844 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1623812844 details at the detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1623812844 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1623812844 violations at the Status - Templates page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1623812844 cluster acm-spoke-47 template test-pod-policy-1623812844-nginx-pod |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1623812844 cluster acm-spoke-48 template test-pod-policy-1623812844-nginx-pod |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1623812844 cluster local-cluster template test-pod-policy-1623812844-nginx-pod |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for cluster violation status to become available |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1623812844 status to become available |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster acm-spoke-47 violations |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster acm-spoke-48 violations |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster local-cluster violations |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy test-imagemanifest-policy-1623812844 |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy test-imagemanifest-policy-1623812844 |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy test-imagemanifest-policy-1623812844 is present in the policy listing |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy test-imagemanifest-policy-1623812844 is present in the policy listing |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy test-imagemanifest-policy-1623812844 using the form |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy test-imagemanifest-policy-1623812844 is not present in the policy listing |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy test-imagemanifest-policy-1623812844 |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy test-imagemanifest-policy-1623812844 |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy test-imagemanifest-policy-1623812844 |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy test-imagemanifest-policy-1623812844 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1623812844 details at the detailed page |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1623812844 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1623812844 violations at the Status - Templates page |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster acm-spoke-47 template test-imagemanifest-policy-1623812844-image-vulnerability |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster acm-spoke-47 template test-imagemanifest-policy-1623812844-image-vulnerability-sub |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster acm-spoke-48 template test-imagemanifest-policy-1623812844-image-vulnerability |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster acm-spoke-48 template test-imagemanifest-policy-1623812844-image-vulnerability-sub |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster local-cluster template test-imagemanifest-policy-1623812844-image-vulnerability |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster local-cluster template test-imagemanifest-policy-1623812844-image-vulnerability-sub |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for cluster violation status to become available |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy test-imagemanifest-policy-1623812844 status to become available |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :x: | failed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Namespace policy to create template ns as duplicatetest |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with default as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with duplicatetest as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Delete created policies |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1623812844 using the form |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1623812844 using the form |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1623812844 using the form |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1623812844 can be deleted in the policy listing |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1623812844 can be deleted in the policy listing |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1623812844 can be deleted in the policy listing |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1623812844 status to become available |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1623812844 status to become available |
| :x: | failed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1623812844 status to become available |
| :x: | failed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check long but valid policy name pattern |
| :x: | failed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check that invalid policy name pattern issues an error |
| :x: | failed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check warning about a policy with a duplicate name |
| :x: | failed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Cleanup: delete previously created policy |
| :white_check_mark: | passed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Check form is updated when whole policy YAML is pasted into YAML editor |
| :x: | failed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Individual YAML updates are reflected in a form |
| :white_check_mark: | passed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Create policy for the URL visit |
| :white_check_mark: | passed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Delete the policy |
| :white_check_mark: | passed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Verify URLs for Namespace and policy that do exist |
| :white_check_mark: | passed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Verify URLs for Namespace and policy that dont exist |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for CertificatePolicy specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for ComplianceOperator specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for EtcdEncryption specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for GatekeeperOperator specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for IamPolicy specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for ImageManifestVulnPolicy specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for LimitRange specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for Namespace specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for Pod specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for PodSecurityPolicy specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for Role specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for RoleBinding specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for SecurityContextConstraints specification |
| :white_check_mark: | passed | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml Create policy should fail with invalid indentation in yaml |
| :white_check_mark: | passed | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml Create policy should fail with invalid policy name in yaml |
| :white_check_mark: | passed | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml Create policy should fail with missing namespace in yaml |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-gatekeeper-1623812844 into YAML editor |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-limitrange-1623812844 into YAML editor |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-gatekeeper-1623812844 to an Enforced state and then back to Inform |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-limitrange-1623812844 to an Enforced state and then back to Inform |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Verify that YAML editor content matches the template |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-operator |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-sample |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |


---

### Failed Test Details

#### :x:  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:535
Expected
    <string>: Error from server (NotFound): namespaces "openshift-gatekeeper-operator" not found
    
to contain substring
    <string>: namespace "openshift-gatekeeper-operator" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:551
```

#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:416
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:430
```

#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:400
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:414
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:488
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.7.4.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:491 +0x245
reflect.Value.call(0x135fb00, 0x15eb268, 0x13, 0x1543f68, 0x4, 0xc0007190e0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eb268, 0x13, 0xc0007190e0, 0x0, 0x0, 0xfbdd3043e881c, 0xc000312e68, 0xfbdd3043e881c)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0005144c0, 0xc000312e60, 0x2216b00, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0005144c0, 0x16efae0, 0xc00056fa40, 0x414301, 0x0, 0x0, 0x0, 0xc00056fa40)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0005144c0, 0x16efae0, 0xc00056fa40, 0x0, 0x0, 0x0, 0x16e54a0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:492 +0x124
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000330f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000330f00, 0x15eabb8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:494
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0007112c0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:477
Timed out after 60.000s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:482
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:351
Timed out after 240.098s.
Expected
    <string>: Error from server (NotFound): customresourcedefinitions.apiextensions.k8s.io "assign.mutations.gatekeeper.sh" not found
    
to contain substring
    <string>: CREATED AT
    assign.mutations.gatekeeper.sh
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:355
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:373
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.4.6.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:376 +0x245
reflect.Value.call(0x135fb00, 0x15eb1c0, 0x13, 0x1543f68, 0x4, 0xc0007190b0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eb1c0, 0x13, 0xc0007190b0, 0x0, 0x0, 0xfbd79fdfe663b, 0xc00041d408, 0xfbd79fdfe663b)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0004748c0, 0xc00041d400, 0x2216b00, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0004748c0, 0x16efae0, 0xc000592110, 0x414301, 0x0, 0x0, 0x0, 0xc000592110)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0004748c0, 0x16efae0, 0xc000592110, 0x0, 0x0, 0x0, 0x16e54a0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:377 +0x147
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000330f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000330f00, 0x15eabb8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:319
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0004714a0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:362
Timed out after 60.431s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:367
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:335
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:349
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:436
Timed out after 180.000s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:443
```

#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:269
Timed out after 180.059s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:274
```

#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:240
Timed out after 180.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:254
```

#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:289
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:303
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:117
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000682f00>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:164
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:170
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:179
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:185
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:133
Timed out after 240.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:139
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:209
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000683400>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:153
Timed out after 60.925s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:158
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:193
Timed out after 180.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:207
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:96
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000711680>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:101
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:115
```

#### :x: @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13021:31)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster acm-spoke-47 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster acm-spoke-48 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1623812844 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12611:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11745:63)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12551:8)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1623812844 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#policy-status-templates`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:4358:12)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1623812844 cluster acm-spoke-47 template test-iam-policy-1623812844-limit-clusteradmin

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1623812844 cluster acm-spoke-48 template test-iam-policy-1623812844-limit-clusteradmin

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1623812844 cluster local-cluster template test-iam-policy-1623812844-limit-clusteradmin

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for cluster violation status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#grc-cluster-view`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:4331:14)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster acm-spoke-47 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster acm-spoke-48 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1623812844 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12611:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11745:63)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12551:8)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1623812844 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#policy-status-templates`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:4358:12)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1623812844 cluster acm-spoke-47 template test-pod-security-policy-1623812844-restricted-psp

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1623812844 cluster acm-spoke-48 template test-pod-security-policy-1623812844-restricted-psp

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1623812844 cluster local-cluster template test-pod-security-policy-1623812844-restricted-psp

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for cluster violation status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#grc-cluster-view`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:4331:14)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster acm-spoke-47 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster acm-spoke-48 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check disabled policy test-role-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that enforced policy test-role-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that policy test-role-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Create new policy test-role-policy-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Disable policy test-role-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enable policy test-role-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enforce policy test-role-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Policy test-role-policy-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1623812844 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12611:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11745:63)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12551:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1623812844 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#policy-status-templates`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:4358:12)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1623812844 cluster acm-spoke-47 template test-role-policy-1623812844-deployments-role

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1623812844 cluster acm-spoke-48 template test-role-policy-1623812844-deployments-role

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1623812844 cluster local-cluster template test-role-policy-1623812844-deployments-role

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for cluster violation status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#grc-cluster-view`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:4331:14)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster acm-spoke-47 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster acm-spoke-48 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check disabled policy test-role-binding-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that enforced policy test-role-binding-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that policy test-role-binding-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Create new policy test-role-binding-policy-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Disable policy test-role-binding-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enable policy test-role-binding-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enforce policy test-role-binding-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Policy test-role-binding-policy-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1623812844 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12611:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11745:63)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12551:8)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1623812844 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#policy-status-templates`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:4358:12)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1623812844 cluster acm-spoke-47 template test-role-binding-policy-1623812844-operatoruser-rolebinding

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1623812844 cluster acm-spoke-48 template test-role-binding-policy-1623812844-operatoruser-rolebinding

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1623812844 cluster local-cluster template test-role-binding-policy-1623812844-operatoruser-rolebinding

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for cluster violation status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#grc-cluster-view`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:4331:14)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for policy test-role-binding-policy-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster acm-spoke-47 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster acm-spoke-48 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check disabled policy test-security-context-constraints-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that enforced policy test-security-context-constraints-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that policy test-security-context-constraints-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Create new policy test-security-context-constraints-policy-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Disable policy test-security-context-constraints-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enable policy test-security-context-constraints-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enforce policy test-security-context-constraints-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Policy test-security-context-constraints-policy-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1623812844 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12611:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11745:63)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12551:8)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1623812844 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#policy-status-templates`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:4358:12)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1623812844 cluster acm-spoke-47 template test-security-context-constraints-policy-1623812844-restricted-scc

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1623812844 cluster acm-spoke-48 template test-security-context-constraints-policy-1623812844-restricted-scc

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1623812844 cluster local-cluster template test-security-context-constraints-policy-1623812844-restricted-scc

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for cluster violation status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#grc-cluster-view`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:4331:14)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for policy test-security-context-constraints-policy-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster acm-spoke-47 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster acm-spoke-48 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1623812844 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12611:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11745:63)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12551:8)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1623812844 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#policy-status-templates`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:4358:12)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1623812844 cluster acm-spoke-47 template test-namespace-policy-1623812844-prod-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1623812844 cluster acm-spoke-48 template test-namespace-policy-1623812844-prod-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1623812844 cluster local-cluster template test-namespace-policy-1623812844-prod-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for cluster violation status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#grc-cluster-view`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:4331:14)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster acm-spoke-47 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster acm-spoke-48 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1623812844 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12611:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11745:63)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12551:8)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1623812844 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#policy-status-templates`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:4358:12)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1623812844 cluster acm-spoke-47 template test-limitrange-policy-1623812844-container-mem-limit-range

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1623812844 cluster acm-spoke-48 template test-limitrange-policy-1623812844-container-mem-limit-range

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1623812844 cluster local-cluster template test-limitrange-policy-1623812844-container-mem-limit-range

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for cluster violation status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#grc-cluster-view`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:4331:14)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1623812844 on the detailed policy page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12674:24)
```

#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1623812844 on the detailed policy page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12674:24)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1623812844-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12674:24)
```

#### :x: RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13021:31)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster acm-spoke-47 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster acm-spoke-48 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1623812844 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12611:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11745:63)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12551:8)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1623812844 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#policy-status-templates`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:4358:12)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1623812844 cluster acm-spoke-47 template test-pod-policy-1623812844-nginx-pod

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1623812844 cluster acm-spoke-48 template test-pod-policy-1623812844-nginx-pod

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1623812844 cluster local-cluster template test-pod-policy-1623812844-nginx-pod

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for cluster violation status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#grc-cluster-view`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:4331:14)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster acm-spoke-47 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster acm-spoke-48 violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy test-imagemanifest-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy test-imagemanifest-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy test-imagemanifest-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12346:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy test-imagemanifest-policy-1623812844 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy test-imagemanifest-policy-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy test-imagemanifest-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy test-imagemanifest-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy test-imagemanifest-policy-1623812844

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy test-imagemanifest-policy-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12438:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1623812844 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12611:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11745:63)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1623812844 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12551:8)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1623812844 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#policy-status-templates`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/ImageManifest_governance.spec.js:4358:12)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster acm-spoke-47 template test-imagemanifest-policy-1623812844-image-vulnerability

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster acm-spoke-47 template test-imagemanifest-policy-1623812844-image-vulnerability-sub

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster acm-spoke-48 template test-imagemanifest-policy-1623812844-image-vulnerability

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster acm-spoke-48 template test-imagemanifest-policy-1623812844-image-vulnerability-sub

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster local-cluster template test-imagemanifest-policy-1623812844-image-vulnerability

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1623812844 cluster local-cluster template test-imagemanifest-policy-1623812844-image-vulnerability-sub

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13283:6)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11766:73)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for cluster violation status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#grc-cluster-view`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/ImageManifest_governance.spec.js:4331:14)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy test-imagemanifest-policy-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:326
Timed out after 120.000s.
Expected
    <int>: 1
to equal
    <int>: 3
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:345
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:176
Timed out after 60.000s.
Expected
    <string>: Pending
to equal
    <string>: Running
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:194
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:144
Timed out after 30.016s.
Expected
    <*errors.StatusError | 0xc0002575e0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:222
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000710500>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:196
Timed out after 120.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:202
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:160
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:174
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:123
Timed out after 60.000s.
Expected
    <*errors.StatusError | 0xc000471c20>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:128
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:142
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:303
Timed out after 240.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:308
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:310
Test Panicked
/usr/lib/golang/src/runtime/iface.go:261

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.7.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:314 +0x149
reflect.Value.call(0x135fb00, 0x15ead08, 0x13, 0x1543f68, 0x4, 0xc0005b10e0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15ead08, 0x13, 0xc0005b10e0, 0x0, 0x0, 0xfbb966edfbe73, 0xc00008ad78, 0xfbb966edfbe73)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000515440, 0xc00008ad70, 0x2216b00, 0x203000, 0xc00003c120)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000515440, 0x16efae0, 0xc000413ed0, 0x414301, 0x0, 0x0, 0x0, 0xc000413ed0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000515440, 0x16efae0, 0xc000413ed0, 0x0, 0x0, 0x0, 0x16e54a0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.7()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:315 +0x14e
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000330f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000330f00, 0x15eabb8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:317
Test Panicked
/usr/lib/golang/src/runtime/iface.go:261

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.8.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:321 +0x149
reflect.Value.call(0x135fb00, 0x15ead18, 0x13, 0x1543f68, 0x4, 0xc0005b10e0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15ead18, 0x13, 0xc0005b10e0, 0x0, 0x0, 0xfbb9671dd42ae, 0xc00008b8b8, 0xfbb9671dd42ae)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000515900, 0xc00008b8b0, 0x2216b00, 0x203000, 0xc00003c120)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000515900, 0x16efae0, 0xc0004aef50, 0x414301, 0x0, 0x0, 0x0, 0xc0004aef50)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000515900, 0x16efae0, 0xc0004aef50, 0x0, 0x0, 0x0, 0x16e54a0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.8()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:322 +0x14e
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000330f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000330f00, 0x15eabb8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:272
Timed out after 120.000s.
Expected
    <nil>: nil
not to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:280
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:256
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000471c20>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:287
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000683180>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:251
Timed out after 60.000s.
Expected
    <*errors.StatusError | 0xc000624140>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Namespace policy to create template ns as duplicatetest

```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:4807:13)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1623812844 using the form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1623812844 using the form

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11698:28)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1623812844 using the form

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11698:28)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1623812844 can be deleted in the policy listing

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11689:27)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card

```
AssertionError: Timed out retrying after 30000ms: expected 'https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/multicloud/policies/create' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11774:12)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card

```
AssertionError: Timed out retrying after 30000ms: expected 'https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/multicloud/policies/create' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11774:12)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `dd.grc-cards-container`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11811:6)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1623812844 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12942:8)
```

#### :x: RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check long but valid policy name pattern

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check that invalid policy name pattern issues an error

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check warning about a policy with a duplicate name

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11698:28)
```

#### :x: RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Cleanup: delete previously created policy

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `a`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12508:12)
```

#### :x: RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Individual YAML updates are reflected in a form

```
TypeError: Cannot read property 'length' of undefined
    at action_createPolicyFromSelection (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12196:39)
    at Context.eval (https://multicloud-console.apps.acm-hub-47.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:11730:61)
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:371
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:385
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:355
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:369
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:444
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:447 +0x245
reflect.Value.call(0x135fb00, 0x15eaf88, 0x13, 0x1543f68, 0x4, 0xc0005b10e0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eaf88, 0x13, 0xc0005b10e0, 0x0, 0x0, 0xfbadf1723de1e, 0xc00060ae68, 0xfbadf1723de1e)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc00039e900, 0xc00060ae60, 0x2216b00, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc00039e900, 0x16efae0, 0xc000413f40, 0x414301, 0x0, 0x0, 0x0, 0xc000413f40)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc00039e900, 0x16efae0, 0xc000413f40, 0x0, 0x0, 0x0, 0x16e54a0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:448 +0x124
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000330f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000330f00, 0x15eabb8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:450
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0000b4e60>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:433
Timed out after 60.202s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:438
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:306
Timed out after 240.000s.
Expected
    <string>: Error from server (NotFound): customresourcedefinitions.apiextensions.k8s.io "assign.mutations.gatekeeper.sh" not found
    
to contain substring
    <string>: CREATED AT
    assign.mutations.gatekeeper.sh
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:310
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:328
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:331 +0x245
reflect.Value.call(0x135fb00, 0x15eaee0, 0x13, 0x1543f68, 0x4, 0xc0005b10b0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eaee0, 0x13, 0xc0005b10b0, 0x0, 0x0, 0xfba8629b025aa, 0xc000405638, 0xfba8629b025aa)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0001f8ac0, 0xc000405630, 0x2216b00, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0001f8ac0, 0x16efae0, 0xc00056fa70, 0x414301, 0x0, 0x0, 0x0, 0xc00056fa70)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0001f8ac0, 0x16efae0, 0xc00056fa70, 0x0, 0x0, 0x0, 0x16e54a0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:332 +0x147
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000330f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000330f00, 0x15eabb8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:274
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000257540>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:317
Timed out after 60.482s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:322
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:290
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:304
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:391
Timed out after 180.345s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:398
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:66
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000256e60>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:119
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:125
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:134
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:140
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:82
Timed out after 360.011s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:94
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:164
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000257cc0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:108
Timed out after 60.000s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:113
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:148
Timed out after 180.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:162
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:45
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0001c1040>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {
                Name: "",
                Group: "",
                Kind: "",
                UID: "",
                Causes: [
                    {
                        Type: "UnexpectedServerResponse",
                        Message: "404 page not found",
                        Field: "",
                    },
                ],
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:115
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:50
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:64
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:224
Timed out after 180.000s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:229
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:195
Timed out after 180.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:209
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:244
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:258
```

