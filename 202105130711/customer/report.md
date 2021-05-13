# :warning: 2.3.0-SNAPSHOT-2021-05-10-21-30-53 had some failures when running Regression on user environment

## Job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/100/


Hub Cluster Version: v2.3.0

Hub Cluster: https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com

Managed Cluster Version: 4.7.6

Managed Cluster: https://console-openshift-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com

## Tests:

|Results|Test|
|---|---|
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-sample |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-certificate-1620890797 is present in the policy listing |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-issuer-1620890797 is present in the policy listing |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Create the clean up policy using the YAML |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-certificate-1620890797 |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1620890797 |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-certificate-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-issuer-1620890797 is not present in the policy listing |
| :x: | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1620890797 status to become available |
| :x: | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Check that policy role-binding-cleanup-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Delete policy role-binding-cleanup-policy-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Verify that policy role-binding-cleanup-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Wait for role-binding-cleanup-policy-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Check that policy role-specification-cleanup-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Delete policy role-specification-cleanup-policy-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Verify that policy role-specification-cleanup-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Wait for role-specification-cleanup-policy-1620890797 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Check that policy scc-cleanup-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Delete policy scc-cleanup-policy-1620890797 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Verify that policy scc-cleanup-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Wait for scc-cleanup-policy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Check that policy test-issue3677-cert-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Create a customized policy |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Delete policy test-issue3677-cert-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Deleted policy test-issue3677-cert-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Prefill a new policy test-issue3677-cert-policy-1620890797 using the form |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Replace namespaceSelector value with "no-such-namespace" |
| :x: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Wait for policy test-issue3677-cert-policy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620890797-create-cert-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620890797-create-cert-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620890797-create-issuer-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620890797-create-issuer-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620890797-create-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620890797-create-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620890797-delete-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620890797-delete-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Create the clean up policy using the YAML |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620890797-create-cert-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620890797-create-cert-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620890797-create-issuer-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620890797-create-issuer-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620890797-create-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620890797-create-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620890797-delete-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620890797-delete-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Remove cert policy issue7520-1620890797-cert-policy |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620890797-create-cert-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620890797-create-cert-ns2 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620890797-create-issuer-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620890797-create-issuer-ns2 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620890797-create-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620890797-create-ns2 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620890797-delete-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620890797-delete-ns2 is not present in the policy listing |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-cert-ns1 status to become available |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-cert-ns2 status to become available |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-issuer-ns1 status to become available |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-issuer-ns2 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-ns1 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-ns2 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-delete-ns1 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-delete-ns2 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show compliance again |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected create certPolicy issue7520-1620890797-cert-policy, expecting a compliance |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1620890797 using the form |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1620890797 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1620890797 details at the detailed page |
| :x: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1620890797 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1620890797 cluster local-cluster template test-iam-policy-1620890797-limit-clusteradmin |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1620890797 using the form |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1620890797 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1620890797 details at the detailed page |
| :x: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1620890797 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1620890797 cluster local-cluster template test-pod-security-policy-1620890797-restricted-psp |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check disabled policy test-role-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that enforced policy test-role-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that policy test-role-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Create new policy test-role-policy-1620890797 using the form |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Deleted policy test-role-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Disable policy test-role-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enable policy test-role-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enforce policy test-role-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Policy test-role-policy-1620890797 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1620890797 details at the detailed page |
| :x: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1620890797 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1620890797 cluster local-cluster template test-role-policy-1620890797-deployments-role |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check disabled policy test-role-binding-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that enforced policy test-role-binding-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that policy test-role-binding-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Create new policy test-role-binding-policy-1620890797 using the form |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Deleted policy test-role-binding-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Disable policy test-role-binding-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enable policy test-role-binding-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enforce policy test-role-binding-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Policy test-role-binding-policy-1620890797 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1620890797 details at the detailed page |
| :x: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1620890797 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1620890797 cluster local-cluster template test-role-binding-policy-1620890797-operatoruser-rolebinding |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for policy test-role-binding-policy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check disabled policy test-security-context-constraints-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that enforced policy test-security-context-constraints-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that policy test-security-context-constraints-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Create new policy test-security-context-constraints-policy-1620890797 using the form |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Deleted policy test-security-context-constraints-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Disable policy test-security-context-constraints-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enable policy test-security-context-constraints-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enforce policy test-security-context-constraints-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Policy test-security-context-constraints-policy-1620890797 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1620890797 details at the detailed page |
| :x: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1620890797 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1620890797 cluster local-cluster template test-security-context-constraints-policy-1620890797-restricted-scc |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for policy test-security-context-constraints-policy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1620890797 using the form |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1620890797 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1620890797 details at the detailed page |
| :x: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1620890797 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1620890797 cluster local-cluster template test-namespace-policy-1620890797-prod-ns |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1620890797 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1620890797 using the form |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1620890797 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1620890797 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1620890797 details at the detailed page |
| :x: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1620890797 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1620890797 cluster local-cluster template test-limitrange-policy-1620890797-container-mem-limit-range |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1620890797 is not present |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1620890797 |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create certificate policy policy-certificatepolicy-1620890797 |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1620890797 and change "remediateAction" to "enforce" |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-1620890797 |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1620890797 |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1620890797 |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1620890797 on the detailed policy page |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1620890797 on the policy status/history page |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1620890797 on the "Govern and risk" page |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Wait for certificate policy policy-certificatepolicy-1620890797 status to become available |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1620890797 status becomes available |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1620890797 is not present |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1620890797 |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1620890797 |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1620890797 and change "remediateAction" to "enforce" |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-rhacm4k-1205-1620890797 |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1620890797 |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1620890797 |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1620890797 on the detailed policy page |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1620890797 on the policy status/history page |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1620890797 on the "Govern and risk" page |
| :white_check_mark: | @extended Setup - create a certificate expiring soon "Govern risk" page can be launched. |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Check that policy policy-create-certificate-1620890797 is present in the policy listing |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Check that policy policy-create-issuer-1620890797 is present in the policy listing |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Create the clean up policy using the YAML |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Delete policy policy-create-certificate-1620890797 |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Delete policy policy-create-issuer-1620890797 |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Verify that policy policy-create-certificate-1620890797 is not present in the policy listing |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Verify that policy policy-create-issuer-1620890797 is not present in the policy listing |
| :x: | @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1620890797 status to become available |
| :x: | @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1620890797 status to become available |
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
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-edit-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-group-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620890797-e2e-rbac-test-1 policy page as e2e-view-ns |
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
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-edit-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-group-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy Status page as e2e-view-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-edit-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-group-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620890797-e2e-rbac-test-1 policy edit page as e2e-view-ns |
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
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table "before all" hook for "get the number of the managed OCP clusters" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Skipping validate delete test if not running on localhost" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Skipping cleanup resources test if not running on localhost" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before all" hook for "Skipping delete resources test if not running on localhost" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before all" hook for "Verify first subscription can be deleted for app ui-git" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before all" hook for "get the name of the managed OCP cluster" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before all" hook for "Verify that settings for application ui-git are properly shown in the app Editor" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test "before all" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before all" hook for "Verify invalid input is rejected" |
| :x: | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation" |
| :x: | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before all" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode" |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1620890797 is present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1620890797 |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1620890797 is not present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1620890797 status to become available |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1620890797 is present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1620890797 |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1620890797 is not present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1620890797 status to become available |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P1][Sev1][policy-grc] should load |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should not show perspective switcher on kube >1.2 |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should open left navigation |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should show perspective switcher on kube 1.2 |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Create page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Info page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Search page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to User page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Applications page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Clusters page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to GRC page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Home page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to KUI |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Overview page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to credentials page |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Welcome page validate links on Welcome page |
| :x: | Observability: [P1][Sev1][Observability] Cannot enable observability service successfully |
| :x: | Observability: [P1][Sev1][Observability] Cannot uninstall observability service completely |
| :white_check_mark: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Create Pod policy issue2444-1620890797-pod-policy from YAML, expecting a compliance |
| :white_check_mark: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Delete Pod policy ${policyName} |
| :x: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Access the Create policy page |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Check Specifications CertificatePolicy,EtcdEncryption |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Category PR.DS Data Security has been pre-selected |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Controls PR.DS-1 Data-at-rest,PR.DS-2 Data-in-transit have been pre-selected |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Specifications CertificatePolicy,EtcdEncryption are selected |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Standard NIST-CSF has been pre-selected |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster local-cluster violations |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1620890797 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1620890797 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1620890797 is present in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1620890797 is present in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1620890797 using the form |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1620890797 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1620890797 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1620890797 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1620890797 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1620890797 details at the detailed page |
| :x: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1620890797 violations at the Status - Templates page |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1620890797 cluster local-cluster template test-pod-policy-1620890797-nginx-pod |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for cluster violation status to become available |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1620890797 status to become available |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster local-cluster violations |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy test-imagemanifest-policy-1620890797 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy test-imagemanifest-policy-1620890797 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy test-imagemanifest-policy-1620890797 is present in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy test-imagemanifest-policy-1620890797 is present in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy test-imagemanifest-policy-1620890797 using the form |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy test-imagemanifest-policy-1620890797 is not present in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy test-imagemanifest-policy-1620890797 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy test-imagemanifest-policy-1620890797 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy test-imagemanifest-policy-1620890797 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy test-imagemanifest-policy-1620890797 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1620890797 details at the detailed page |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1620890797 violations at the Status - Clusters page |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1620890797 violations at the Status - Templates page |
| :x: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1620890797 cluster local-cluster template test-imagemanifest-policy-1620890797-image-vulnerability |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1620890797 cluster local-cluster template test-imagemanifest-policy-1620890797-image-vulnerability-sub |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for cluster violation status to become available |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy test-imagemanifest-policy-1620890797 status to become available |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Namespace policy to create template ns as duplicatetest |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with default as namespace |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with duplicatetest as namespace |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Delete created policies |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1620890797 using the form |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1620890797 using the form |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1620890797 using the form |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1620890797 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1620890797 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1620890797 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1620890797 status to become available |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1620890797 status to become available |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1620890797 status to become available |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check long but valid policy name pattern |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check that invalid policy name pattern issues an error |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check warning about a policy with a duplicate name |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Cleanup: delete previously created policy |
| :white_check_mark: | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
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
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-gatekeeper-1620890797 into YAML editor |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-limitrange-1620890797 into YAML editor |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-gatekeeper-1620890797 to an Enforced state and then back to Inform |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-limitrange-1620890797 to an Enforced state and then back to Inform |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Verify that YAML editor content matches the template |
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
| :white_check_mark: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :white_check_mark: | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :white_check_mark: | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


---

### Failed Test Details

#### :x: @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1620890797 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:6892:13)
```
                        
#### :x: @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1620890797 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:6892:13)
```
                        
#### :x: @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1620890797 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: 'Found 1 non compliant certificates in the namespace issue7520-1620890797-ns2' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/tests/issue7520_added_removed_namespaces.spec.js:15140:24)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-cert-ns1 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:6892:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-cert-ns2 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:6892:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-issuer-ns1 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:6892:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620890797-create-issuer-ns2 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:6892:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:6892:13)
```
                        
#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1620890797 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1620890797 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1620890797 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1620890797 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1620890797 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1620890797 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1620890797 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1620890797


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:21576:42)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:21576:42)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1620890797 on the detailed policy page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:21841:42)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1620890797 on the "Govern and risk" page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:21576:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1620890797


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:21576:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:21576:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1620890797 on the detailed policy page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:21841:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1620890797 on the "Govern and risk" page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:21576:42)
```
                        
#### :x: @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1620890797 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:6892:13)
```
                        
#### :x: @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1620890797 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:6892:13)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table "before all" hook for "get the number of the managed OCP clusters"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Skipping validate delete test if not running on localhost"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Skipping cleanup resources test if not running on localhost"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before all" hook for "Skipping delete resources test if not running on localhost"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before all" hook for "Verify first subscription can be deleted for app ui-git"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before all" hook for "Verify that settings for application ui-git are properly shown in the app Editor"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test "before all" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before all" hook for "Verify invalid input is rejected"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before all" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode"


```
CypressError: `cy.exec('oc set env deploy search-operator DEPLOY_REDISGRAPH="true" -n open-cluster-management')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "open-cluster-management" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:136950:26
    at tryCatcher (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:10791:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8726:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8783:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8828:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:8908:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5498:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5491:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5507:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/runner/cypress_runner.js:5377:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=cypress/support/index.js:1150:10)
```
                        
#### :x: Observability: [P1][Sev1][Observability] Cannot enable observability service successfully


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:95
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_install_test.go:35
```
                        
#### :x: Observability: [P1][Sev1][Observability] Cannot uninstall observability service completely


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:100
Unexpected error:
    <*errors.StatusError | 0xc00022e3c0>: {
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
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1620890797 violations at the Status - Clusters page


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22220:31)
```
                        
#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1620890797 cluster local-cluster template test-imagemanifest-policy-1620890797-image-vulnerability


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com/__cypress/tests?p=tests/cypress/support/index.js:22486:28)
```
                        
