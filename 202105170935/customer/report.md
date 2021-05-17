# :warning: 2.3.0-SNAPSHOT-2021-05-17-08-01-44 had some failures when running Regression on user environment

## Job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/111/


Hub Cluster Version: v2.3.0

Hub Cluster: https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com

Managed Cluster Version: 4.8.0-fc.3

Managed Cluster: https://console-openshift-console.apps.ocp4-h27-0.qe.lab.redhat.com

## Tests:

|Results|Test|
|---|---|
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-sample |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :x: |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :x: |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-certificate-1621247965 is present in the policy listing |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-issuer-1621247965 is present in the policy listing |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Create the clean up policy using the YAML |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-certificate-1621247965 |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1621247965 |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-certificate-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-issuer-1621247965 is not present in the policy listing |
| :x: | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1621247965 status to become available |
| :x: | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Check that policy role-binding-cleanup-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Delete policy role-binding-cleanup-policy-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Verify that policy role-binding-cleanup-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Wait for role-binding-cleanup-policy-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Check that policy role-specification-cleanup-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Delete policy role-specification-cleanup-policy-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Verify that policy role-specification-cleanup-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Wait for role-specification-cleanup-policy-1621247965 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Check that policy scc-cleanup-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Delete policy scc-cleanup-policy-1621247965 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Verify that policy scc-cleanup-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Wait for scc-cleanup-policy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Check that policy test-issue3677-cert-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Create a customized policy |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Delete policy test-issue3677-cert-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Deleted policy test-issue3677-cert-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Prefill a new policy test-issue3677-cert-policy-1621247965 using the form |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Replace namespaceSelector value with "no-such-namespace" |
| :x: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Wait for policy test-issue3677-cert-policy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1621247965-create-cert-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1621247965-create-cert-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1621247965-create-issuer-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1621247965-create-issuer-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1621247965-create-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1621247965-create-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1621247965-delete-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1621247965-delete-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Create the clean up policy using the YAML |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1621247965-create-cert-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1621247965-create-cert-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1621247965-create-issuer-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1621247965-create-issuer-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1621247965-create-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1621247965-create-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1621247965-delete-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1621247965-delete-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Remove cert policy issue7520-1621247965-cert-policy |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1621247965-create-cert-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1621247965-create-cert-ns2 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1621247965-create-issuer-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1621247965-create-issuer-ns2 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1621247965-create-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1621247965-create-ns2 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1621247965-delete-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1621247965-delete-ns2 is not present in the policy listing |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-cert-ns1 status to become available |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-cert-ns2 status to become available |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-issuer-ns1 status to become available |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-issuer-ns2 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-ns1 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-ns2 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-delete-ns1 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-delete-ns2 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show compliance again |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected create certPolicy issue7520-1621247965-cert-policy, expecting a compliance |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster ocp4-h27-1 violations |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1621247965 using the form |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1621247965 can be deleted in the policy listing |
| :x: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1621247965 details at the detailed page |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1621247965 violations at the Status - Templates page |
| :x: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1621247965 cluster local-cluster template test-iam-policy-1621247965-limit-clusteradmin |
| :x: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1621247965 cluster ocp4-h27-1 template test-iam-policy-1621247965-limit-clusteradmin |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster ocp4-h27-1 violations |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1621247965 |
| :x: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1621247965 using the form |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1621247965 can be deleted in the policy listing |
| :x: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1621247965 details at the detailed page |
| :x: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1621247965 violations at the Status - Templates page |
| :x: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1621247965 cluster local-cluster template test-pod-security-policy-1621247965-restricted-psp |
| :x: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1621247965 cluster ocp4-h27-1 template test-pod-security-policy-1621247965-restricted-psp |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster ocp4-h27-1 violations |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check disabled policy test-role-policy-1621247965 |
| :x: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that enforced policy test-role-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that policy test-role-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Create new policy test-role-policy-1621247965 using the form |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Deleted policy test-role-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Disable policy test-role-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enable policy test-role-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enforce policy test-role-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Policy test-role-policy-1621247965 can be deleted in the policy listing |
| :x: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1621247965 details at the detailed page |
| :x: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1621247965 violations at the Status - Templates page |
| :x: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1621247965 cluster local-cluster template test-role-policy-1621247965-deployments-role |
| :x: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1621247965 cluster ocp4-h27-1 template test-role-policy-1621247965-deployments-role |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster ocp4-h27-1 violations |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check disabled policy test-role-binding-policy-1621247965 |
| :x: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that enforced policy test-role-binding-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that policy test-role-binding-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Create new policy test-role-binding-policy-1621247965 using the form |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Deleted policy test-role-binding-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Disable policy test-role-binding-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enable policy test-role-binding-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enforce policy test-role-binding-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Policy test-role-binding-policy-1621247965 can be deleted in the policy listing |
| :x: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1621247965 details at the detailed page |
| :x: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1621247965 violations at the Status - Templates page |
| :x: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1621247965 cluster local-cluster template test-role-binding-policy-1621247965-operatoruser-rolebinding |
| :x: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1621247965 cluster ocp4-h27-1 template test-role-binding-policy-1621247965-operatoruser-rolebinding |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for policy test-role-binding-policy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster ocp4-h27-1 violations |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check disabled policy test-security-context-constraints-policy-1621247965 |
| :x: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that enforced policy test-security-context-constraints-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that policy test-security-context-constraints-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Create new policy test-security-context-constraints-policy-1621247965 using the form |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Deleted policy test-security-context-constraints-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Disable policy test-security-context-constraints-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enable policy test-security-context-constraints-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enforce policy test-security-context-constraints-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Policy test-security-context-constraints-policy-1621247965 can be deleted in the policy listing |
| :x: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1621247965 details at the detailed page |
| :x: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1621247965 violations at the Status - Templates page |
| :x: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1621247965 cluster local-cluster template test-security-context-constraints-policy-1621247965-restricted-scc |
| :x: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1621247965 cluster ocp4-h27-1 template test-security-context-constraints-policy-1621247965-restricted-scc |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for policy test-security-context-constraints-policy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster ocp4-h27-1 violations |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1621247965 |
| :x: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1621247965 using the form |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1621247965 can be deleted in the policy listing |
| :x: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1621247965 details at the detailed page |
| :x: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1621247965 violations at the Status - Templates page |
| :x: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1621247965 cluster local-cluster template test-namespace-policy-1621247965-prod-ns |
| :x: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1621247965 cluster ocp4-h27-1 template test-namespace-policy-1621247965-prod-ns |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster ocp4-h27-1 violations |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1621247965 |
| :x: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1621247965 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1621247965 using the form |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1621247965 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1621247965 can be deleted in the policy listing |
| :x: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1621247965 details at the detailed page |
| :x: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1621247965 violations at the Status - Templates page |
| :x: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1621247965 cluster local-cluster template test-limitrange-policy-1621247965-container-mem-limit-range |
| :x: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1621247965 cluster ocp4-h27-1 template test-limitrange-policy-1621247965-container-mem-limit-range |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1621247965 is not present |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1621247965 |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create certificate policy policy-certificatepolicy-1621247965 |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1621247965 and change "remediateAction" to "enforce" |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-1621247965 |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1621247965 |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1621247965 |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1621247965 on the detailed policy page |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1621247965 on the policy status/history page |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1621247965 on the "Govern and risk" page |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Wait for certificate policy policy-certificatepolicy-1621247965 status to become available |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1621247965 status becomes available |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1621247965 is not present |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1621247965 |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1621247965 |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1621247965 and change "remediateAction" to "enforce" |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-rhacm4k-1205-1621247965 |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1621247965 |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1621247965 |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1621247965 on the detailed policy page |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1621247965 on the policy status/history page |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1621247965 on the "Govern and risk" page |
| :white_check_mark: | @extended Setup - create a certificate expiring soon "Govern risk" page can be launched. |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Check that policy policy-create-certificate-1621247965 is present in the policy listing |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Check that policy policy-create-issuer-1621247965 is present in the policy listing |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Create the clean up policy using the YAML |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Delete policy policy-create-certificate-1621247965 |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Delete policy policy-create-issuer-1621247965 |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Verify that policy policy-create-certificate-1621247965 is not present in the policy listing |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Verify that policy policy-create-issuer-1621247965 is not present in the policy listing |
| :x: | @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1621247965 status to become available |
| :x: | @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1621247965 status to become available |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-edit-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-group-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-view-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-admin-cluster |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-admin-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-edit-cluster |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-edit-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-group-cluster |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-group-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-view-cluster |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-view-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-edit-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-group-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-view-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-admin-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-edit-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-group-ns |
| :x: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-view-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-edit-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-group-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy edit page as e2e-view-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Create policies used for the testing |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login again as kubeadmin |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-admin-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-admin-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-cluster-admin-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-cluster-admin-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-edit-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-edit-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-group-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-group-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-view-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-view-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-admin-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-admin-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-cluster-admin-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-cluster-admin-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-edit-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-edit-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-group-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-group-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-view-cluster user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-view-ns user |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Remove test policies |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Verify that CYPRESS_RBAC_PASS environment variable is defined |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm can be created from resource type helm using template editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm2 can be created from resource type helm using template editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-obj can be created from resource type objectstore using template editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2 |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055 |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible resources created on the target cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm resources created on the target cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm timewindow - helm: ui-helm |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 resources created on the target cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 timewindow - helm: ui-helm2 |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj resources created on the target cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj timewindow - objectstore: ui-obj |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm channels, subscription and placementrule are valid - helm: ui-helm |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm2 channels, subscription and placementrule are valid - helm: ui-helm2 |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-obj channels, subscription and placementrule are valid - objectstore: ui-obj |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if not running on localhost |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if not running on localhost |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if not running on localhost |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm2 |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-helm is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-helm was selected |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm single app page info is valid after new subscription is created |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm template editor valid after new subscription is created |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm are properly shown in the app Editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm2 are properly shown in the app Editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected" |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource git - ui-git-ansible |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource helm - ui-helm2 |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2 |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj |
| :white_check_mark: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :x: | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode" |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1621247965 is present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1621247965 |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1621247965 is not present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1621247965 status to become available |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1621247965 is present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1621247965 |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1621247965 is not present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1621247965 status to become available |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P1][Sev1][policy-grc] should load |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should not show perspective switcher on kube >1.2 |
| :x: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should open left navigation |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should show perspective switcher on kube 1.2 |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Create page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Info page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Search page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to User page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Applications page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Clusters page |
| :x: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to GRC page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Home page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to KUI |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Overview page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to credentials page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page validate links on Welcome page |
| :x: | Observability: [P1][Sev1][Observability] Cannot enable observability service successfully |
| :x: | Observability: [P1][Sev1][Observability] Cannot uninstall observability service completely |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-731[P1][Sev1][observability-usa] Login: search-e2e-admin-cluster user |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-731[P1][Sev1][observability-usa] Logout: search-e2e-admin-cluster user |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-731[P2][Sev2][observability-usa] As an user with name search-e2e-admin-cluster with cluster-role-binding of default admin role, the user can read the Overview page. |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-919[P1][Sev1][observability-usa] Login: search-e2e-view-ns user |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-919[P1][Sev1][observability-usa] Logout: search-e2e-view-ns user |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-919[P2][Sev2][observability-usa] As an user with name search-e2e-view-ns with ns-role-binding of default view role, the user can read the Overview page. |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-920[P1][Sev1][observability-usa] Login: search-e2e-edit-ns user |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-920[P1][Sev1][observability-usa] Logout: search-e2e-edit-ns user |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-920[P2][Sev2][observability-usa] As an user with name search-e2e-edit-ns with ns-role-binding of default edit role, the user can read the Overview page. |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-921[P1][Sev1][observability-usa] Login: search-e2e-admin-ns user |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-921[P1][Sev1][observability-usa] Logout: search-e2e-admin-ns user |
| :white_check_mark: | RBAC users to read the Overview page RHACM4K-921[P2][Sev2][observability-usa] As an user with name search-e2e-admin-ns with ns-role-binding of default admin role, the user can read the Overview page. |
| :white_check_mark: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Create Pod policy issue2444-1621247965-pod-policy from YAML, expecting a compliance |
| :white_check_mark: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Delete Pod policy ${policyName} |
| :x: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Access the Create policy page |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Check Specifications CertificatePolicy,EtcdEncryption |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Category PR.DS Data Security has been pre-selected |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Controls PR.DS-1 Data-at-rest,PR.DS-2 Data-in-transit have been pre-selected |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Specifications CertificatePolicy,EtcdEncryption are selected |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Standard NIST-CSF has been pre-selected |
| :white_check_mark: | RHACM4K-1695: Search - verify managed cluster info in the search page [P1][Sev1][observability-usa] Search - verify managed cluster info in the search page. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind application on specific namespace. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod and namespace open-cluster-management. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod on specific cluster. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:certpolicycontroller. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:iampolicycontroller. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Verify a deleted pod is recreated. |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by active |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apigroup |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apiversion |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by architecture |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by available |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by capacity |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by claimRef |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cluster |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by clusterIP |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by completions |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by consoleURL |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by container |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cpu |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by created |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by current |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by desired |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by hostIP |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by kubernetesVersion |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by lastSchedule |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by memory |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by nodes |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by osImage |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by parallelism |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by podIP |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by port |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by ready |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by reclaimPolicy |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by request |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by restarts |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by startedAt |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by successful |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by suspend |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by type |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by updated |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by volumeName |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster local-cluster violations |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster ocp4-h27-1 violations |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1621247965 |
| :x: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1621247965 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1621247965 is present in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1621247965 is present in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1621247965 using the form |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1621247965 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1621247965 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1621247965 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1621247965 can be deleted in the policy listing |
| :x: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1621247965 details at the detailed page |
| :x: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1621247965 violations at the Status - Templates page |
| :x: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1621247965 cluster local-cluster template test-pod-policy-1621247965-nginx-pod |
| :x: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1621247965 cluster ocp4-h27-1 template test-pod-policy-1621247965-nginx-pod |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for cluster violation status to become available |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1621247965 status to become available |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster local-cluster violations |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster ocp4-h27-1 violations |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy test-imagemanifest-policy-1621247965 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy test-imagemanifest-policy-1621247965 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy test-imagemanifest-policy-1621247965 is present in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy test-imagemanifest-policy-1621247965 is present in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy test-imagemanifest-policy-1621247965 using the form |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy test-imagemanifest-policy-1621247965 is not present in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy test-imagemanifest-policy-1621247965 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy test-imagemanifest-policy-1621247965 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy test-imagemanifest-policy-1621247965 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy test-imagemanifest-policy-1621247965 can be deleted in the policy listing |
| :x: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1621247965 details at the detailed page |
| :x: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1621247965 violations at the Status - Clusters page |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1621247965 violations at the Status - Templates page |
| :x: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1621247965 cluster local-cluster template test-imagemanifest-policy-1621247965-image-vulnerability |
| :x: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1621247965 cluster local-cluster template test-imagemanifest-policy-1621247965-image-vulnerability-sub |
| :x: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1621247965 cluster ocp4-h27-1 template test-imagemanifest-policy-1621247965-image-vulnerability |
| :x: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1621247965 cluster ocp4-h27-1 template test-imagemanifest-policy-1621247965-image-vulnerability-sub |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for cluster violation status to become available |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy test-imagemanifest-policy-1621247965 status to become available |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Namespace policy to create template ns as duplicatetest |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with default as namespace |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with duplicatetest as namespace |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Delete created policies |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1621247965 using the form |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1621247965 using the form |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1621247965 using the form |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1621247965 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1621247965 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1621247965 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1621247965 status to become available |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1621247965 status to become available |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1621247965 status to become available |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check long but valid policy name pattern |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check that invalid policy name pattern issues an error |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check warning about a policy with a duplicate name |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Cleanup: delete previously created policy |
| :x: | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :white_check_mark: | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Access the Create policy page |
| :white_check_mark: | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Check form is updated when whole policy YAML is pasted into YAML editor |
| :white_check_mark: | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Individual YAML updates are reflected in a form |
| :white_check_mark: | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Create policy for the URL visit |
| :white_check_mark: | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Delete the policy |
| :white_check_mark: | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Verify URLs for Namespace and policy that do exist |
| :white_check_mark: | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Verify URLs for Namespace and policy that dont exist |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for CertificatePolicy specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for ComplianceOperator specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for EtcdEncryption specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for GatekeeperOperator specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for IamPolicy specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for ImageManifestVulnPolicy specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for LimitRange specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for Namespace specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for Pod specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for PodSecurityPolicy specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for Role specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for RoleBinding specification |
| :white_check_mark: | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for SecurityContextConstraints specification |
| :white_check_mark: | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml Create policy should fail with invalid indentation in yaml |
| :white_check_mark: | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml Create policy should fail with invalid policy name in yaml |
| :white_check_mark: | RHACM4K-247 - GRC UI: [P1][Sev1][policy-grc] Create policy with invalid yaml Create policy should fail with missing namespace in yaml |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-gatekeeper-1621247965 into YAML editor |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-limitrange-1621247965 into YAML editor |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-gatekeeper-1621247965 to an Enforced state and then back to Inform |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-limitrange-1621247965 to an Enforced state and then back to Inform |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Verify that YAML editor content matches the template |
| :white_check_mark: | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to edit the saved searches |
| :white_check_mark: | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to find the saved searches |
| :white_check_mark: | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to revert back the edited saved searches |
| :white_check_mark: | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to save current search |
| :white_check_mark: | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to share the saved searches |
| :white_check_mark: | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should find each managed cluster has default namespace |
| :white_check_mark: | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should find open-cluster-management-agent namespace exists |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions [P1][Sev1][observability-usa] should create namespace and application |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions [P2][Sev2][observability-usa] should find expected application and delete application |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in kube-system on imported cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm on hub cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on hub cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on imported cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on hub cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on imported cluster. |
| :white_check_mark: | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect. |
| :white_check_mark: | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present. |
| :white_check_mark: | Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod. |
| :white_check_mark: | Search: Linked page [P2][Sev2][observability-usa] clusters page should have link to search page |
| :white_check_mark: | Search: Overview page [P1][Sev1][observability-usa] should load the overview page |
| :white_check_mark: | Search: Overview page [P2][Sev2][observability-usa] add cloud connection action works |
| :white_check_mark: | Search: Overview page [P2][Sev2][observability-usa] should have link to search page |
| :x: | Search: Search in Local Cluster [P1][Sev1][observability-usa] should create deployment from create resource UI |
| :x: | Search: Search in Local Cluster [P1][Sev1][observability-usa] should create namespace from create resource UI |
| :white_check_mark: | Search: Search in Local Cluster [P1][Sev1][observability-usa] should load the search page |
| :white_check_mark: | Search: Search in Local Cluster [P1][Sev1][observability-usa] should not see any cluster and namespace |
| :x: | Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that deployment resource exist |
| :x: | Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that namespace already exist |
| :x: | Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for deployment |
| :x: | Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for pod |
| :x: | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete deployment |
| :white_check_mark: | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete namespace |
| :x: | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete pod |
| :x: | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should see pod logs |
| :white_check_mark: | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should validate deployment was deleted |
| :white_check_mark: | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should validate namespace was deleted |
| :x: | Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should have expected count of relationships |
| :x: | Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should scale deployment |
| :x: | Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should verify that the deployment scaled |
| :x: | Search: Search in Managed Cluster "before all" hook for "[P1][Sev1][observability-usa] should load the search page" |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by combination with "next suggestion" value and "label" filter with "next suggestion" value |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by combination with "next suggestion" value and "name" filter with "next suggestion" value |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by multiple values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by next suggestion |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should suggest values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "label" filter should filter by next suggestion |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "label" filter should suggest values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "name" filter should filter by next suggestion |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "name" filter should suggest values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by master |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by multiple values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by worker |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should suggest values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should filter by multiple values |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should filter by next suggestion |
| :white_check_mark: | Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should suggest values |
| :white_check_mark: | Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the created last hour template & search tag in search items |
| :white_check_mark: | Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the unhealthy pods template & search tag in search items |
| :white_check_mark: | Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the workloads template & search tag in search items |
| :white_check_mark: | [P0][sev1][kui]Visual Web Terminal: Verify user path for rbash |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify KUI multiple tabs |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify kubectl |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify oc |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify supported CLIs can execute |
| :white_check_mark: | [P1][sev1][kui]Visual Web Terminal: Verify user home folder permissions |
| :white_check_mark: | [P2][sev1][kui]Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev1][kui]Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev1][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify KUI getting started command |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify commands are disabled - rbash |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify product header |
| :white_check_mark: | [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus |
| :white_check_mark: | [P2][sev3][kui]Visual Web Terminal: Verify supported themes |
| :x: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :x: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :x: | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :x: | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


---

### Failed Test Details

#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:416
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:430
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:400
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
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
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:491 +0x237
reflect.Value.call(0x1309bc0, 0x15a9980, 0x13, 0x1502685, 0x4, 0xc0007a50e0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a9980, 0x13, 0xc0007a50e0, 0x0, 0x0, 0x69ee3e4c50c74, 0xc00040b098, 0x69ee3e4c50c74)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000530b80, 0xc00040b090, 0x23dca80, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000530b80, 0x16f8740, 0xc00014f390, 0x412f01, 0x0, 0x0, 0x0, 0xc00014f390)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000530b80, 0x16f8740, 0xc00014f390, 0x0, 0x0, 0x0, 0x16ecfc0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:492 +0x124
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000360480)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc000360480, 0x15a92d0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:477
Timed out after 61.275s.
Expected
    <string>: I0517 14:52:54.987081   13207 request.go:655] Throttling request took 1.165877999s, request: GET:https://api.ocp4-h27-0.qe.lab.redhat.com:6443/apis/apps.openshift.io/v1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:482
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:351
Timed out after 240.102s.
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
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:376 +0x237
reflect.Value.call(0x1309bc0, 0x15a98d8, 0x13, 0x1502685, 0x4, 0xc0007a50b0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a98d8, 0x13, 0xc0007a50b0, 0x0, 0x0, 0x69e8d511d70a1, 0xc000313f48, 0x69e8d511d70a1)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc00013a580, 0xc000313f40, 0x23dca80, 0x203000, 0xc0007a51c8)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc00013a580, 0x16f8740, 0xc000483110, 0x412f01, 0x0, 0x0, 0x0, 0xc000483110)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc00013a580, 0x16f8740, 0xc000483110, 0x0, 0x0, 0x0, 0x16ecfc0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:377 +0x147
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000360480)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc000360480, 0x15a92d0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:362
Timed out after 61.326s.
Expected
    <string>: I0517 14:46:43.106153   12211 request.go:655] Throttling request took 1.152676616s, request: GET:https://api.ocp4-h27-0.qe.lab.redhat.com:6443/apis/cloudcredential.openshift.io/v1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
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
    <v1.ComplianceState>: NonCompliant
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:119
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:125
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:134
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:140
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:82
Timed out after 360.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:94
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:108
Timed out after 61.460s.
Expected
    <string>: I0517 13:59:46.615694    4941 request.go:655] Throttling request took 1.154266979s, request: GET:https://api.ocp4-h27-0.qe.lab.redhat.com:6443/apis/metal3.io/v1alpha1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:113
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:148
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:162
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:224
Timed out after 180.000s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:229
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:195
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:209
```
                        
#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:269
Timed out after 180.000s.
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
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:254
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
                        
#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:153
Timed out after 61.335s.
Expected
    <string>: I0517 14:29:33.558289    9200 request.go:655] Throttling request took 1.153563948s, request: GET:https://api.ocp4-h27-0.qe.lab.redhat.com:6443/apis/operators.coreos.com/v1alpha1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
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
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:207
```
                        
#### :x: @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1621247965 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:4785:13)
```
                        
#### :x: @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1621247965 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:4785:13)
```
                        
#### :x: @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1621247965 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12970:48)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: 'Found 1 non compliant certificates in the namespace issue7520-1621247965-ns2' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/issue7520_added_removed_namespaces.spec.js:5911:24)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-cert-ns1 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:4785:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-cert-ns2 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:4785:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-issuer-ns1 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:4785:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1621247965-create-issuer-ns2 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:4785:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:4785:13)
```
                        
#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1621247965 details at the detailed page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1621247965 cluster local-cluster template test-iam-policy-1621247965-limit-clusteradmin


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1621247965 cluster ocp4-h27-1 template test-iam-policy-1621247965-limit-clusteradmin


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1621247965


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1621247965 details at the detailed page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1621247965 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12970:48)
```
                        
#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1621247965 cluster local-cluster template test-pod-security-policy-1621247965-restricted-psp


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1621247965 cluster ocp4-h27-1 template test-pod-security-policy-1621247965-restricted-psp


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1621247965


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1621247965 details at the detailed page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1621247965 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12970:48)
```
                        
#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1621247965 cluster local-cluster template test-role-policy-1621247965-deployments-role


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1621247965 cluster ocp4-h27-1 template test-role-policy-1621247965-deployments-role


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1621247965


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1621247965 details at the detailed page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1621247965 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12970:48)
```
                        
#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1621247965 cluster local-cluster template test-role-binding-policy-1621247965-operatoruser-rolebinding


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1621247965 cluster ocp4-h27-1 template test-role-binding-policy-1621247965-operatoruser-rolebinding


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1621247965


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1621247965 details at the detailed page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1621247965 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12970:48)
```
                        
#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1621247965 cluster local-cluster template test-security-context-constraints-policy-1621247965-restricted-scc


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1621247965 cluster ocp4-h27-1 template test-security-context-constraints-policy-1621247965-restricted-scc


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1621247965


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1621247965 details at the detailed page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1621247965 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12970:48)
```
                        
#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1621247965 cluster local-cluster template test-namespace-policy-1621247965-prod-ns


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1621247965 cluster ocp4-h27-1 template test-namespace-policy-1621247965-prod-ns


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1621247965


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1621247965 details at the detailed page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1621247965 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12970:48)
```
                        
#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1621247965 cluster local-cluster template test-limitrange-policy-1621247965-container-mem-limit-range


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1621247965 cluster ocp4-h27-1 template test-limitrange-policy-1621247965-container-mem-limit-range


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1621247965


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1621247965 on the detailed policy page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1621247965 on the "Govern and risk" page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1621247965


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1621247965 on the detailed policy page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1621247965 on the "Govern and risk" page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1621247965 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:4785:13)
```
                        
#### :x: @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1621247965 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:4785:13)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-admin-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-admin-ns


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-edit-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-edit-ns


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-group-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-group-ns


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-view-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1621247965-e2e-rbac-test-1 policy page as e2e-view-ns


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-admin-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11891:8)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11891:8)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-edit-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11891:8)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-group-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11891:8)
```
                        
#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1621247965-e2e-rbac-test-1 policy Status page as e2e-view-cluster


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11891:8)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git


```
AssertionError: Timed out retrying after 4000ms: Expected to find content: '1 Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:625:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible


```
AssertionError: expected 0 to be at least 3
    at validateTopology (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:634:64)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm


```
AssertionError: expected 0 to be at least 3
    at validateTopology (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:634:64)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected"


```
CypressError: `cy.request()` failed on:

https://oauth-openshift.apps.ocp4-h27-0.qe.lab.redhat.com/oauth/authorize?response_type=token&client_id=openshift-challenging-client

The response we received from your web server was:

  > 401: Unauthorized

This was considered a failure because the status code was not `2xx` or `3xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

-----------------------------------------------------------

The request we sent was:

Method: HEAD
URL: https://oauth-openshift.apps.ocp4-h27-0.qe.lab.redhat.com/oauth/authorize?response_type=token&client_id=openshift-challenging-client
Headers: {
  "Connection": "keep-alive",
  "X-CSRF-Token": 1,
  "user-agent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/87.0.4280.66 Safari/537.36",
  "accept": "*/*",
  "authorization": "Basic dGVzdC1jbHVzdGVyLW1hbmFnZXItYWRtaW46aXVMWW8tb0RFM2ctbmpUQ3ItdXZhOGI=",
  "accept-encoding": "gzip, deflate",
  "content-length": 0
}

-----------------------------------------------------------

The response we got was:

Status: 401 - Unauthorized
Headers: {
  "cache-control": "no-cache, no-store, max-age=0, must-revalidate",
  "expires": "0",
  "pragma": "no-cache",
  "referrer-policy": "strict-origin-when-cross-origin",
  "www-authenticate": "Basic realm=\"openshift\"",
  "x-content-type-options": "nosniff",
  "x-dns-prefetch-control": "off",
  "x-frame-options": "DENY",
  "x-xss-protection": "1; mode=block",
  "date": "Mon, 17 May 2021 14:58:40 GMT"
}
Body: 


https://on.cypress.io/request

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140051:21
    at tryCatcher (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:797:6)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git


```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1492:107)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git


```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:726:121)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible


```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include 'Local'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:726:121)
```
                        
#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode"


```
CypressError: `cy.request()` failed on:

https://oauth-openshift.apps.ocp4-h27-0.qe.lab.redhat.com/oauth/authorize?response_type=token&client_id=openshift-challenging-client

The response we received from your web server was:

  > 401: Unauthorized

This was considered a failure because the status code was not `2xx` or `3xx`.

If you do not want status codes to cause failures pass the option: `failOnStatusCode: false`

-----------------------------------------------------------

The request we sent was:

Method: HEAD
URL: https://oauth-openshift.apps.ocp4-h27-0.qe.lab.redhat.com/oauth/authorize?response_type=token&client_id=openshift-challenging-client
Headers: {
  "Connection": "keep-alive",
  "X-CSRF-Token": 1,
  "user-agent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/87.0.4280.66 Safari/537.36",
  "accept": "*/*",
  "authorization": "Basic dGVzdC1jbHVzdGVyLW1hbmFnZXItYWRtaW46aXVMWW8tb0RFM2ctbmpUQ3ItdXZhOGI=",
  "accept-encoding": "gzip, deflate",
  "content-length": 0
}

-----------------------------------------------------------

The response we got was:

Status: 401 - Unauthorized
Headers: {
  "cache-control": "no-cache, no-store, max-age=0, must-revalidate",
  "expires": "0",
  "pragma": "no-cache",
  "referrer-policy": "strict-origin-when-cross-origin",
  "www-authenticate": "Basic realm=\"openshift\"",
  "x-content-type-options": "nosniff",
  "x-dns-prefetch-control": "off",
  "x-frame-options": "DENY",
  "x-xss-protection": "1; mode=block",
  "date": "Mon, 17 May 2021 14:58:15 GMT"
}
Body: 


https://on.cypress.io/request

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:140051:21
    at tryCatcher (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=cypress/support/index.js:797:6)
```
                        
#### :x: GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should open left navigation


```
AssertionError: Timed out retrying after 60000ms: Not enough elements found. Found '8', expected '11'.
    at Object.validateMenu (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/welcomePage_and_Header.spec.js:247:68)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/welcomePage_and_Header.spec.js:371:33)
```
                        
#### :x: GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to GRC page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: 'Governance' within the element: <div#page-sidebar.pf-c-page__sidebar.pf-m-expanded> but never did.
    at Object.goToGRC (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/welcomePage_and_Header.spec.js:280:52)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/welcomePage_and_Header.spec.js:411:33)
```
                        
#### :x: Observability: [P1][Sev1][Observability] Cannot enable observability service successfully


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:95
Unexpected error:
    <*errors.StatusError | 0xc00003bc20>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "secrets \"multiclusterhub-operator-pull-secret\" not found",
            Reason: "NotFound",
            Details: {
                Name: "multiclusterhub-operator-pull-secret",
                Group: "",
                Kind: "secrets",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    secrets "multiclusterhub-operator-pull-secret" not found
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_install_test.go:72
```
                        
#### :x: Observability: [P1][Sev1][Observability] Cannot uninstall observability service completely


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:100
Unexpected error:
    <*errors.StatusError | 0xc000206be0>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "multiclusterobservabilities.observability.open-cluster-management.io \"observability\" not found",
            Reason: "NotFound",
            Details: {
                Name: "observability",
                Group: "observability.open-cluster-management.io",
                Kind: "multiclusterobservabilities",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    multiclusterobservabilities.observability.open-cluster-management.io "observability" not found
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_uninstall_test.go:38
```
                        
#### :x: RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12986:31)
```
                        
#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1621247965


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12342:42)
```
                        
#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1621247965 details at the detailed page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1621247965 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12970:48)
```
                        
#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1621247965 cluster local-cluster template test-pod-policy-1621247965-nginx-pod


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1621247965 cluster ocp4-h27-1 template test-pod-policy-1621247965-nginx-pod


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1621247965 details at the detailed page


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `#compliance\.details`, but never found it.
    at action_verifyPolicyInPolicyDetails (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12576:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11723:63)
```
                        
#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1621247965 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:12970:48)
```
                        
#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1621247965 cluster local-cluster template test-imagemanifest-policy-1621247965-image-vulnerability


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1621247965 cluster local-cluster template test-imagemanifest-policy-1621247965-image-vulnerability-sub


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1621247965 cluster ocp4-h27-1 template test-imagemanifest-policy-1621247965-image-vulnerability


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1621247965 cluster ocp4-h27-1 template test-imagemanifest-policy-1621247965-image-vulnerability-sub


```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:13243:6)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:11744:73)
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:326
Expected
    <string>: I0517 13:51:58.075959    4753 request.go:655] Throttling request took 1.123459441s, request: GET:https://api.ocp4-h27-0.qe.lab.redhat.com:6443/apis/whereabouts.cni.cncf.io/v1alpha1?timeout=32s
    error: the server doesn't have a resource type "ScanSettingBinding"
    
to contain substring
    <string>: scansettingbinding.compliance.openshift.io "e8" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:332
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:176
Timed out after 360.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:188
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:303
Test Panicked
/usr/lib/golang/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.6.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:307 +0xf3
reflect.Value.call(0x1309bc0, 0x15a9410, 0x13, 0x1502685, 0x4, 0xc0004d10e0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a9410, 0x13, 0xc0004d10e0, 0x0, 0x0, 0x69b50886436eb, 0xc000313a48, 0x69b50886436eb)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0002fa780, 0xc000313a40, 0x23dca80, 0x203000, 0xc00003c120)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0002fa780, 0x16f8740, 0xc000416b50, 0x412f00, 0x0, 0x0, 0x0, 0xc000416b50)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).ShouldNot(0xc0002fa780, 0x16f8740, 0xc000416b50, 0x0, 0x0, 0x0, 0x16ecfc0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:56 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:308 +0x148
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000360480)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc000360480, 0x15a92d0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:310
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000449220>: {
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:317
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000732280>: {
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:272
Timed out after 120.000s.
Expected
    <*errors.StatusError | 0xc0001c10e0>: {
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
                        
#### :x: RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication


```
/opt/e2e/client/canary/e2e_canary_helmrepo_basicath_test.go:11
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_helmrepo_basicath_test.go:14
```
                        
#### :x: Search: Search in Local Cluster [P1][Sev1][observability-usa] should create deployment from create resource UI


```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#acm-create-resource`, but never found it.
    at Object.whenGoToResourcePage (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1360:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1115:30)
```
                        
#### :x: Search: Search in Local Cluster [P1][Sev1][observability-usa] should create namespace from create resource UI


```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#acm-create-resource`, but never found it.
    at Object.whenGoToResourcePage (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1360:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1101:30)
```
                        
#### :x: Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that deployment resource exist


```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#acm-create-resource`, but never found it.
    at Object.whenGoToResourcePage (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1360:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1124:30)
```
                        
#### :x: Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that namespace already exist


```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#acm-create-resource`, but never found it.
    at Object.whenGoToResourcePage (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1360:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1108:30)
```
                        
#### :x: Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for deployment


```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1150:27)
```
                        
#### :x: Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for pod


```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1155:27)
```
                        
#### :x: Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete deployment


```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1191:27)
```
                        
#### :x: Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete pod


```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1168:27)
```
                        
#### :x: Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should see pod logs


```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1160:27)
```
                        
#### :x: Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should have expected count of relationships


```
AssertionError: Timed out retrying after 10000ms: Expected to find element: ``, but never found it. Queried from element: <div.pf-l-gallery.pf-m-gutter.jss15>
    at Object.whenExpandRelationshipTiles (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1489:19)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1141:28)
```
                        
#### :x: Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should scale deployment


```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1175:27)
```
                        
#### :x: Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should verify that the deployment scaled


```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1184:27)
```
                        
#### :x: Search: Search in Managed Cluster "before all" hook for "[P1][Sev1][observability-usa] should load the search page"


```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#inputUsername`, but never found it.

Because this error occurred during a `before all` hook we are skipping the remaining tests in the current suite: `Search: Search in Managed C...`

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.ocp4-h27-0.qe.lab.redhat.com/__cypress/tests?p=tests/cypress/support/index.js:2657:10)
```
                        
#### :x: e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit


```
/opt/e2e/client/canary/e2e_subscription_test.go:12
Timed out after 47.424s.
Expected success, but got an error:
    <*errors.errorString | 0xc00056b1f0>: {
        s: "failed test on sub-004, with status failed err: failed",
    }
    failed test on sub-004, with status failed err: failed
/opt/e2e/client/canary/e2e_subscription_test.go:13
```
                        
#### :x: e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag


```
/opt/e2e/client/canary/e2e_subscription_test.go:9
Timed out after 54.947s.
Expected success, but got an error:
    <*errors.errorString | 0xc00087d750>: {
        s: "failed test on sub-003, with status failed err: failed",
    }
    failed test on sub-003, with status failed err: failed
/opt/e2e/client/canary/e2e_subscription_test.go:10
```
                        
#### :x: e2e-server [P1][Sev1][app-lifecycle] Test argocd integration


```
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:11
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:14
```
                        
#### :x: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate


```
/opt/e2e/client/canary/e2e_canary_git_custom_cert_test.go:10
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_git_custom_cert_test.go:12
```
                        
