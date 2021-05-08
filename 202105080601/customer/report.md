# :warning: 2.3.0-SNAPSHOT-2021-04-24-05-15-03 had some failures when running Regression on user environment

## Job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/85/


Hub Cluster Version: v2.3.0

Hub Cluster: https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com

Managed Cluster Version: v1.20.0+5fbfd19

Managed Cluster: https://console-openshift-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com

## Tests:

|Results|Test|
|---|---|
| :x: |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
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
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :x: |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :x: |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :x: |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :x: |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-certificate-1620458858 is present in the policy listing |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-issuer-1620458858 is present in the policy listing |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Create the clean up policy using the YAML |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-certificate-1620458858 |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1620458858 |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-certificate-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-issuer-1620458858 is not present in the policy listing |
| :x: | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1620458858 status to become available |
| :x: | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Check that policy role-binding-cleanup-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Delete policy role-binding-cleanup-policy-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Verify that policy role-binding-cleanup-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Wait for role-binding-cleanup-policy-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Check that policy role-specification-cleanup-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Delete policy role-specification-cleanup-policy-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Verify that policy role-specification-cleanup-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Wait for role-specification-cleanup-policy-1620458858 status to become available |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Check that policy scc-cleanup-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Delete policy scc-cleanup-policy-1620458858 |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Verify that policy scc-cleanup-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Wait for scc-cleanup-policy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Check that policy test-issue3677-cert-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Create a customized policy |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Delete policy test-issue3677-cert-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Deleted policy test-issue3677-cert-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Prefill a new policy test-issue3677-cert-policy-1620458858 using the form |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Replace namespaceSelector value with "no-such-namespace" |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Wait for policy test-issue3677-cert-policy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620458858-create-cert-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620458858-create-cert-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620458858-create-issuer-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620458858-create-issuer-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620458858-create-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620458858-create-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620458858-delete-ns1 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1620458858-delete-ns2 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Create the clean up policy using the YAML |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620458858-create-cert-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620458858-create-cert-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620458858-create-issuer-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620458858-create-issuer-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620458858-create-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620458858-create-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620458858-delete-ns1 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1620458858-delete-ns2 |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Remove cert policy issue7520-1620458858-cert-policy |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620458858-create-cert-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620458858-create-cert-ns2 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620458858-create-issuer-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620458858-create-issuer-ns2 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620458858-create-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620458858-create-ns2 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620458858-delete-ns1 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1620458858-delete-ns2 is not present in the policy listing |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-cert-ns1 status to become available |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-cert-ns2 status to become available |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-issuer-ns1 status to become available |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-issuer-ns2 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-ns1 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-ns2 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-delete-ns1 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-delete-ns2 status to become available |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show compliance again |
| :x: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation |
| :white_check_mark: | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected create certPolicy issue7520-1620458858-cert-policy, expecting a compliance |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1620458858 using the form |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1620458858 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1620458858 details at the detailed page |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1620458858 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1620458858 cluster local-cluster template test-iam-policy-1620458858-limit-clusteradmin |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1620458858 using the form |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1620458858 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1620458858 details at the detailed page |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1620458858 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1620458858 cluster local-cluster template test-pod-security-policy-1620458858-restricted-psp |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check disabled policy test-role-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that enforced policy test-role-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that policy test-role-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Create new policy test-role-policy-1620458858 using the form |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Deleted policy test-role-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Disable policy test-role-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enable policy test-role-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enforce policy test-role-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Policy test-role-policy-1620458858 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1620458858 details at the detailed page |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1620458858 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1620458858 cluster local-cluster template test-role-policy-1620458858-deployments-role |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check disabled policy test-role-binding-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that enforced policy test-role-binding-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that policy test-role-binding-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Create new policy test-role-binding-policy-1620458858 using the form |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Deleted policy test-role-binding-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Disable policy test-role-binding-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enable policy test-role-binding-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enforce policy test-role-binding-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Policy test-role-binding-policy-1620458858 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1620458858 details at the detailed page |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1620458858 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1620458858 cluster local-cluster template test-role-binding-policy-1620458858-operatoruser-rolebinding |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for policy test-role-binding-policy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check disabled policy test-security-context-constraints-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that enforced policy test-security-context-constraints-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that policy test-security-context-constraints-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Create new policy test-security-context-constraints-policy-1620458858 using the form |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Deleted policy test-security-context-constraints-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Disable policy test-security-context-constraints-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enable policy test-security-context-constraints-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enforce policy test-security-context-constraints-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Policy test-security-context-constraints-policy-1620458858 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1620458858 details at the detailed page |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1620458858 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1620458858 cluster local-cluster template test-security-context-constraints-policy-1620458858-restricted-scc |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for policy test-security-context-constraints-policy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1620458858 using the form |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1620458858 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1620458858 details at the detailed page |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1620458858 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1620458858 cluster local-cluster template test-namespace-policy-1620458858-prod-ns |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster local-cluster violations |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1620458858 is present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1620458858 using the form |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1620458858 |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1620458858 can be deleted in the policy listing |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1620458858 details at the detailed page |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1620458858 violations at the Status - Templates page |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1620458858 cluster local-cluster template test-limitrange-policy-1620458858-container-mem-limit-range |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for cluster violation status to become available |
| :white_check_mark: | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1620458858 is not present |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1620458858 |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create certificate policy policy-certificatepolicy-1620458858 |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1620458858 and change "remediateAction" to "enforce" |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-1620458858 |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1620458858 |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1620458858 |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1620458858 on the detailed policy page |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1620458858 on the policy status/history page |
| :x: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1620458858 on the "Govern and risk" page |
| :white_check_mark: | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Wait for certificate policy policy-certificatepolicy-1620458858 status to become available |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1620458858 status becomes available |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1620458858 is not present |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1620458858 |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1620458858 |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1620458858 and change "remediateAction" to "enforce" |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-rhacm4k-1205-1620458858 |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1620458858 |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1620458858 |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1620458858 on the detailed policy page |
| :white_check_mark: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1620458858 on the policy status/history page |
| :x: | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1620458858 on the "Govern and risk" page |
| :white_check_mark: | @extended Setup - create a certificate expiring soon "Govern risk" page can be launched. |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Check that policy policy-create-certificate-1620458858 is present in the policy listing |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Check that policy policy-create-issuer-1620458858 is present in the policy listing |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Create the clean up policy using the YAML |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Delete policy policy-create-certificate-1620458858 |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Delete policy policy-create-issuer-1620458858 |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Verify that policy policy-create-certificate-1620458858 is not present in the policy listing |
| :white_check_mark: | @extended Setup - create a certificate expiring soon Verify that policy policy-create-issuer-1620458858 is not present in the policy listing |
| :x: | @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1620458858 status to become available |
| :x: | @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1620458858 status to become available |
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
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-edit-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-group-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed rbac-test-1620458858-e2e-rbac-test-1 policy page as e2e-view-ns |
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
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-edit-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-group-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy Status page as e2e-view-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-edit-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-edit-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-group-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-group-ns |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-view-cluster |
| :white_check_mark: | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check rbac-test-1620458858-e2e-rbac-test-1 policy edit page as e2e-view-ns |
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
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1620458858 is present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1620458858 |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1620458858 is not present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1620458858 status to become available |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1620458858 is present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1620458858 |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1620458858 is not present in the policy listing |
| :white_check_mark: | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1620458858 status to become available |
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
| :white_check_mark: | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted |
| :large_blue_circle: | Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :large_blue_circle: | Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana-dev/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability][Stable] Checking default value of PVC and StorageClass (config/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | Observability: [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0) |
| :x: | Observability: [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0) |
| :x: | Observability: [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Modifying MCO cr to enable observabilityaddon |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have endpoint-operator and metrics-collector being deployed |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should not have the expected MCO addon pods when disable observabilityaddon |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Waiting for check no metric data in grafana console |
| :large_blue_circle: | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Integration] Modifying managedcluster cr to disable observability |
| :large_blue_circle: | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Integration] Modifying managedcluster cr to enable observability |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Deleting metrics-collector deployment |
| :white_check_mark: | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Updating metrics-collector deployment |
| :large_blue_circle: | Observability: [P2][Sev2][Observability][Integration] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :x: | Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0) |
| :x: | Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Customize the replicas for thanos query (reconcile/g0) |
| :x: | Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0) |
| :x: | Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0) |
| :x: | Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have metrics which defined in custom metrics allowlist (metricslist/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have no metrics after custom metrics allowlist deleted (metricslist/g0) |
| :x: | Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :white_check_mark: | Observability: [P2][Sev2][Observability][Stable] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :x: | Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0) |
| :x: | Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |
| :white_check_mark: | Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0) |
| :x: | RBAC users to read the Overview page "after all" hook for "RHACM4K-731[P1][Sev1][search] As an user with name search-e2e-admin-cluster with cluster-role-binding of default admin role, the user can read the Overview page." |
| :x: | RBAC users to read the Overview page "before all" hook for "RHACM4K-731[P1][Sev1][search] As an user with name search-e2e-admin-cluster with cluster-role-binding of default admin role, the user can read the Overview page." |
| :white_check_mark: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Create Pod policy issue2444-1620458858-pod-policy from YAML, expecting a compliance |
| :white_check_mark: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Delete Pod policy ${policyName} |
| :white_check_mark: | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Access the Create policy page |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Check Specifications CertificatePolicy,EtcdEncryption |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Category PR.DS Data Security has been pre-selected |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Controls PR.DS-1 Data-at-rest,PR.DS-2 Data-in-transit have been pre-selected |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Specifications CertificatePolicy,EtcdEncryption are selected |
| :white_check_mark: | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Standard NIST-CSF has been pre-selected |
| :white_check_mark: | RHACM4K-1695: Search - verify managed cluster info in the search page Search - verify managed cluster info in the search page. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind application on specific namespace. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod and namespace open-cluster-management. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod on specific cluster. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:certpolicycontroller. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:iampolicycontroller. |
| :white_check_mark: | RHACM4K-1696: Search - Verify search result with common filter and conditions Verify a deleted pod is recreated. |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by active |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by apigroup |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by apiversion |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by architecture |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by available |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by capacity |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by claimRef |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by cluster |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by clusterIP |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by completions |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by consoleURL |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by container |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by cpu |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by created |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by current |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by desired |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by hostIP |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by kubernetesVersion |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by lastSchedule |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by memory |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by nodes |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by osImage |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by parallelism |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by podIP |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by port |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by ready |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by reclaimPolicy |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by request |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by restarts |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by startedAt |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by successful |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by suspend |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by type |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by updated |
| :white_check_mark: | RHACM4K-1709: Search - Search using filters should filter by volumeName |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster local-cluster violations |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1620458858 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1620458858 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1620458858 is present in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1620458858 is present in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1620458858 using the form |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1620458858 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1620458858 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1620458858 |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1620458858 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1620458858 details at the detailed page |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1620458858 violations at the Status - Templates page |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1620458858 cluster local-cluster template test-pod-policy-1620458858-nginx-pod |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for cluster violation status to become available |
| :white_check_mark: | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1620458858 status to become available |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster local-cluster violations |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy test-imagemanifest-policy-1620458858 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy test-imagemanifest-policy-1620458858 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy test-imagemanifest-policy-1620458858 is present in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy test-imagemanifest-policy-1620458858 is present in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy test-imagemanifest-policy-1620458858 using the form |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy test-imagemanifest-policy-1620458858 is not present in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy test-imagemanifest-policy-1620458858 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy test-imagemanifest-policy-1620458858 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy test-imagemanifest-policy-1620458858 |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy test-imagemanifest-policy-1620458858 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1620458858 details at the detailed page |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1620458858 violations at the Status - Clusters page |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1620458858 violations at the Status - Templates page |
| :x: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1620458858 cluster local-cluster template test-imagemanifest-policy-1620458858-image-vulnerability |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1620458858 cluster local-cluster template test-imagemanifest-policy-1620458858-image-vulnerability-sub |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for cluster violation status to become available |
| :white_check_mark: | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy test-imagemanifest-policy-1620458858 status to become available |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :x: | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Namespace policy to create template ns as duplicatetest |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with default as namespace |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with duplicatetest as namespace |
| :white_check_mark: | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Delete created policies |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1620458858 using the form |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1620458858 using the form |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1620458858 using the form |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1620458858 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1620458858 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1620458858 can be deleted in the policy listing |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1620458858 status to become available |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1620458858 status to become available |
| :white_check_mark: | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1620458858 status to become available |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check long but valid policy name pattern |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check that invalid policy name pattern issues an error |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check warning about a policy with a duplicate name |
| :white_check_mark: | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Cleanup: delete previously created policy |
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
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-gatekeeper-1620458858 into YAML editor |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-limitrange-1620458858 into YAML editor |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-gatekeeper-1620458858 to an Enforced state and then back to Inform |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-limitrange-1620458858 to an Enforced state and then back to Inform |
| :white_check_mark: | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Verify that YAML editor content matches the template |
| :x: | RHACM4K-412 - Search: Saved searches "after all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace" |
| :x: | RHACM4K-412 - Search: Saved searches "before all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace" |
| :x: | RHACM4K-913: Search - common filter and conditions "after all" hook for "[P1][Sev1][search] should create namespace and application" |
| :x: | RHACM4K-913: Search - common filter and conditions "before all" hook for "[P1][Sev1][search] should create namespace and application" |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in kube-system on imported cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm on hub cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent on hub cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent on imported cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent-addon on hub cluster. |
| :white_check_mark: | RHACM4K-913: Search - common filter and conditions should have expected count of pods in ocm-agent-addon on imported cluster. |
| :white_check_mark: | Search API: Validate autocomplete [P3][Sev3][search][PLACEHOLDER] This test not yet implemented. |
| :white_check_mark: | Search API: Verify access: [P1][Sev1][search] should get 401 if authorization header is incorrect. |
| :white_check_mark: | Search API: Verify access: [P1][Sev1][search] should get 401 if authorization header is not present. |
| :white_check_mark: | Search API: Verify access: [P1][Sev1][search] should return results when searching for kind:pod. |
| :x: | Search: Linked page "after all" hook for "[P2][Sev2][search] clusters page should have link to search page" |
| :x: | Search: Linked page "before all" hook for "[P2][Sev2][search] clusters page should have link to search page" |
| :x: | Search: Overview page "after all" hook for "[P1][Sev1][search] should load the overview page" |
| :x: | Search: Overview page "before all" hook for "[P1][Sev1][search] should load the overview page" |
| :x: | Search: Search in Local Cluster "after all" hook for "[P1][Sev1][search] should load the search page" |
| :x: | Search: Search in Local Cluster "before all" hook for "[P1][Sev1][search] should load the search page" |
| :x: | Search: Search using filters [P1][Sev1][search] Search using "name" filter "after all" hook for "should suggest values" |
| :x: | Search: Search using filters [P1][Sev1][search] Search using "name" filter "before all" hook for "should suggest values" |
| :x: | Search: Verify the suggested search templates "after all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items" |
| :x: | Search: Verify the suggested search templates "before all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items" |
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
| :x: | [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus |
| :white_check_mark: | [P2][sev3][kui]Visual Web Terminal: Verify supported themes |
| :white_check_mark: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |


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
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:491 +0x237
reflect.Value.call(0x1309bc0, 0x15a9950, 0x13, 0x1502683, 0x4, 0xc0007110e0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a9950, 0x13, 0xc0007110e0, 0x0, 0x0, 0x3ce509bc0e5c6, 0xc000490be8, 0x3ce509bc0e5c6)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0006b2380, 0xc000490be0, 0x23dca80, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0006b2380, 0x16f8720, 0xc00069a460, 0x412f01, 0x0, 0x0, 0x0, 0xc00069a460)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0006b2380, 0x16f8720, 0xc00069a460, 0x0, 0x0, 0x0, 0x16ecfa0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:492 +0x124
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002e3c20)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002e3c20, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:494
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00017a780>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:450
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0007565a0>: {
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
Timed out after 63.249s.
Expected
    <string>: I0508 10:48:12.988714   11551 request.go:655] Throttling request took 1.197299591s, request: GET:https://api.rosa-acmqe4.hz70.p1.openshiftapps.com:6443/apis/image.openshift.io/v1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:482
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:351
Timed out after 120.000s.
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
reflect.Value.call(0x1309bc0, 0x15a98a8, 0x13, 0x1502683, 0x4, 0xc0007110b0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a98a8, 0x13, 0xc0007110b0, 0x0, 0x0, 0x3cdf8a6ec4851, 0xc000490b98, 0x3cdf8a6ec4851)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc00056b7c0, 0xc000490b90, 0x23dca80, 0x203000, 0xc0007111c8)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc00056b7c0, 0x16f8720, 0xc0003b88b0, 0x412f01, 0x0, 0x0, 0x0, 0xc0003b88b0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc00056b7c0, 0x16f8720, 0xc0003b88b0, 0x0, 0x0, 0x0, 0x16ecfa0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:377 +0x147
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002e3c20)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002e3c20, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:319
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00017b040>: {
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
Timed out after 63.296s.
Expected
    <string>: I0508 10:41:55.017962   10750 request.go:655] Throttling request took 1.018247888s, request: GET:https://api.rosa-acmqe4.hz70.p1.openshiftapps.com:6443/apis/managed.openshift.io/v1alpha1?timeout=32s
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
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:349
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:436
Timed out after 180.169s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:443
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:66
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0005aa500>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:164
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00017b220>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:108
Timed out after 63.426s.
Expected
    <string>: I0508 09:50:42.283466    4915 request.go:655] Throttling request took 1.009234335s, request: GET:https://api.rosa-acmqe4.hz70.p1.openshiftapps.com:6443/apis/machineconfiguration.openshift.io/v1?timeout=32s
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
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:162
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:45
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00017a820>: {
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
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:50
Timed out after 60.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:64
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
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:209
```
                        
#### :x:  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:244
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:258
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
    <*errors.StatusError | 0xc00053b220>: {
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
Timed out after 120.000s.
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
    <*errors.StatusError | 0xc0003c2780>: {
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
Timed out after 63.278s.
Expected
    <string>: I0508 10:23:42.303691    8736 request.go:655] Throttling request took 1.030333843s, request: GET:https://api.rosa-acmqe4.hz70.p1.openshiftapps.com:6443/apis/app.k8s.io/v1beta1?timeout=32s
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
    <*errors.StatusError | 0xc000756c80>: {
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
                        
#### :x: @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1620458858 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4446:13)
```
                        
#### :x: @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1620458858 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4446:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: 'NonCompliant' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/issue7520_added_removed_namespaces.spec.js:15136:24)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-cert-ns1 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4446:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-cert-ns2 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4446:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-issuer-ns1 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4446:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1620458858-create-issuer-ns2 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4446:13)
```
                        
#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4446:13)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1620458858


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:18331:42)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:18331:42)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1620458858 on the detailed policy page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:18647:42)
```
                        
#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1620458858 on the "Govern and risk" page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:18331:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1620458858


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:18331:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:18331:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1620458858 on the detailed policy page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:18647:42)
```
                        
#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1620458858 on the "Govern and risk" page


```
AssertionError: Timed out retrying after 60000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#467f40'
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:18331:42)
```
                        
#### :x: @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1620458858 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4446:13)
```
                        
#### :x: @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1620458858 status to become available


```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4446:13)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc adm policy add-cluster-role-to-user                                 open-cluster-management:view:undefined test-mngd-cluster-view|                                 oc policy add-role-to-user view test-mngd-cluster-view -n undefined')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Warning: User 'test-mngd-cluster-view' not found
Error from server (NotFound): namespaces "undefined" not found

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:674:10)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table "before all" hook for "get the number of the managed OCP clusters"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Skipping validate delete test if not running on localhost"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Skipping cleanup resources test if not running on localhost"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before all" hook for "Skipping delete resources test if not running on localhost"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before all" hook for "Verify first subscription can be deleted for app ui-git"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before all" hook for "get the name of the managed OCP cluster"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before all" hook for "Verify that settings for application ui-git are properly shown in the app Editor"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test "before all" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before all" hook for "Verify invalid input is rejected"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before all" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode"


```
CypressError: `cy.exec('oc create namespace app-ui-ansibleoperator')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (Forbidden): namespaces is forbidden: User "test-cluster-admin" cannot create resource "namespaces" in API group "" at the cluster scope

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:135:14)
```
                        
#### :x: Observability: [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:193
Unexpected error:
    <*errors.errorString | 0xc0006207d0>: {
        s: "Deployment observability-grafana should have 2 but got 6 ready replicas",
    }
    Deployment observability-grafana should have 2 but got 6 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:200
```
                        
#### :x: Observability: [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:193
Unexpected error:
    <*errors.errorString | 0xc0000ab700>: {
        s: "Deployment observability-grafana should have 2 but got 6 ready replicas",
    }
    Deployment observability-grafana should have 2 but got 6 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:200
```
                        
#### :x: Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:115
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc000736980>: {
        s: "the storage size of statefulset observability-alertmanager should have 2Gi but got {{5368709120 0} {<nil>} 5Gi BinarySI}",
    }
    the storage size of statefulset observability-alertmanager should have 2Gi but got {{5368709120 0} {<nil>} 5Gi BinarySI}
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:123
```
                        
#### :x: Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:93
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0007fdda0>: {
        s: "Failed to check node selector for pod: observability-alertmanager-0",
    }
    Failed to check node selector for pod: observability-alertmanager-0
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:101
```
                        
#### :x: Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:51
Timed out after 600.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0000aace0>: {
        s: "Statefulset observability-alertmanager should have 3 but got 4 ready replicas",
    }
    Statefulset observability-alertmanager should have 3 but got 4 ready replicas
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:90
```
                        
#### :x: Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:162
Timed out after 900.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0000d8930>: {
        s: "Deployment observability-grafana should have 2 but got 6 ready replicas",
    }
    Deployment observability-grafana should have 2 but got 6 ready replicas
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:201
```
                        
#### :x: Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:90
Timed out after 600.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0007fcd30>: {
        s: "Statefulset observability-thanos-rule should have 3 but got 4 ready replicas",
    }
    Statefulset observability-thanos-rule should have 3 but got 4 ready replicas
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:116
```
                        
#### :x: Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:193
Unexpected error:
    <*errors.errorString | 0xc0007fdc30>: {
        s: "Deployment observability-grafana should have 2 but got 6 ready replicas",
    }
    Deployment observability-grafana should have 2 but got 6 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:200
```
                        
#### :x: Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:161
Timed out after 600.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc00049c680>: {
        s: "Statefulset observability-thanos-rule should have 3 but got 4 ready replicas",
    }
    Statefulset observability-thanos-rule should have 3 but got 4 ready replicas
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:188
```
                        
#### :x: Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0)


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:193
Unexpected error:
    <*errors.errorString | 0xc000519f50>: {
        s: "Deployment observability-grafana should have 2 but got 6 ready replicas",
    }
    Deployment observability-grafana should have 2 but got 6 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:200
```
                        
#### :x: RBAC users to read the Overview page "after all" hook for "RHACM4K-731[P1][Sev1][search] As an user with name search-e2e-admin-cluster with cluster-role-binding of default admin role, the user can read the Overview page."


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2753:43)
```
                        
#### :x: RBAC users to read the Overview page "before all" hook for "RHACM4K-731[P1][Sev1][search] As an user with name search-e2e-admin-cluster with cluster-role-binding of default admin role, the user can read the Overview page."


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1620458858 cluster local-cluster template test-imagemanifest-policy-1620458858-image-vulnerability


```
AssertionError: Timed out retrying after 60000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:19241:28)
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:348
Expected
    <string>: Error from server (NotFound): namespaces "openshift-compliance" not found
    
to contain substring
    <string>: namespace "openshift-compliance" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:355
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:327
Expected
    <string>: I0508 09:41:19.604496    4760 request.go:655] Throttling request took 1.017212047s, request: GET:https://api.rosa-acmqe4.hz70.p1.openshiftapps.com:6443/apis/agent.open-cluster-management.io/v1?timeout=32s
    error: the server doesn't have a resource type "ScanSettingBinding"
    
to contain substring
    <string>: scansettingbinding.compliance.openshift.io "e8" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:333
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:144
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00053b400>: {
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
    <*errors.StatusError | 0xc0003c2be0>: {
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
    <*errors.StatusError | 0xc0005aa280>: {
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
Expected
    <*errors.StatusError | 0xc0002590e0>: {
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
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:307
```
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:311
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0003c3ae0>: {
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
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:318
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc00017b680>: {
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
    <*errors.StatusError | 0xc00017b7c0>: {
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
                        
#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan


```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:256
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc000756140>: {
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
    <*errors.StatusError | 0xc00053be00>: {
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
    <*errors.StatusError | 0xc00053b360>: {
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
                        
#### :x: RHACM4K-412 - Search: Saved searches "after all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2753:43)
```
                        
#### :x: RHACM4K-412 - Search: Saved searches "before all" hook for "[P2][Sev2][search] should find each managed cluster has default namespace"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions "after all" hook for "[P1][Sev1][search] should create namespace and application"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2753:43)
```
                        
#### :x: RHACM4K-913: Search - common filter and conditions "before all" hook for "[P1][Sev1][search] should create namespace and application"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Linked page "after all" hook for "[P2][Sev2][search] clusters page should have link to search page"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2753:43)
```
                        
#### :x: Search: Linked page "before all" hook for "[P2][Sev2][search] clusters page should have link to search page"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Overview page "after all" hook for "[P1][Sev1][search] should load the overview page"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2753:43)
```
                        
#### :x: Search: Overview page "before all" hook for "[P1][Sev1][search] should load the overview page"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Search in Local Cluster "after all" hook for "[P1][Sev1][search] should load the search page"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2753:43)
```
                        
#### :x: Search: Search in Local Cluster "before all" hook for "[P1][Sev1][search] should load the search page"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Search using filters [P1][Sev1][search] Search using "name" filter "after all" hook for "should suggest values"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2753:43)
```
                        
#### :x: Search: Search using filters [P1][Sev1][search] Search using "name" filter "before all" hook for "should suggest values"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: Search: Verify the suggested search templates "after all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items"


```
AssertionError: expected null to exist

Because this error occurred during a `after all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2753:43)
```
                        
#### :x: Search: Verify the suggested search templates "before all" hook for "[P3][Sev3][search] should see the workloads template & search tag in search items"


```
AssertionError: Timed out retrying after 15000ms: Expected to find content: 'kube:admin' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.rosa-acmqe4.hz70.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2656:46)
```
                        
#### :x: [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus


```
    at Page.clear (/usr/src/app/tests/page-objects/Prometheus.js:115:10)
    at Page.queryMetric (/usr/src/app/tests/page-objects/Prometheus.js:92:30)
    at Object.[P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus (/usr/src/app/tests/e2e/verifyMetricsInPrometheus.test.js:22:18)
```
                        
