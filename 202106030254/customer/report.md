# :warning: Had some failures when running regression on cluster slai-ocp48-aws with test snapshot 2.3.0-SNAPSHOT-2021-06-02-22-28-53 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/126/


ACM Version: v2.3.0

Hub Cluster Version: 4.8.0-0.nightly-2021-06-01-043518

Hub Cluster: https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.0-0.nightly-2021-06-01-043518

Managed Cluster: https://console-openshift-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202106030254/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-certificate-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-issuer-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-certificate-1622696458 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1622696458 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-certificate-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-issuer-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1622696458 status to become available |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Check that policy role-binding-cleanup-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Delete policy role-binding-cleanup-policy-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Verify that policy role-binding-cleanup-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Wait for role-binding-cleanup-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Check that policy role-specification-cleanup-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Delete policy role-specification-cleanup-policy-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Verify that policy role-specification-cleanup-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Wait for role-specification-cleanup-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Check that policy scc-cleanup-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Delete policy scc-cleanup-policy-1622696458 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Verify that policy scc-cleanup-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Wait for scc-cleanup-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Check that policy test-issue3677-cert-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Create a customized policy |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Delete policy test-issue3677-cert-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Deleted policy test-issue3677-cert-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Prefill a new policy test-issue3677-cert-policy-1622696458 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Replace namespaceSelector value with "no-such-namespace" |
| :x: | failed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Wait for policy test-issue3677-cert-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1622696458-create-cert-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1622696458-create-cert-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1622696458-create-issuer-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1622696458-create-issuer-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1622696458-create-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1622696458-create-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1622696458-delete-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1622696458-delete-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1622696458-create-cert-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1622696458-create-cert-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1622696458-create-issuer-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1622696458-create-issuer-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1622696458-create-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1622696458-create-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1622696458-delete-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1622696458-delete-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Remove cert policy issue7520-1622696458-cert-policy |
| :x: | failed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1622696458-create-cert-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1622696458-create-cert-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1622696458-create-issuer-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1622696458-create-issuer-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1622696458-create-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1622696458-create-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1622696458-delete-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1622696458-delete-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1622696458-create-cert-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1622696458-create-cert-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1622696458-create-issuer-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1622696458-create-issuer-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1622696458-create-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1622696458-create-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1622696458-delete-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1622696458-delete-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show compliance again |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected create certPolicy issue7520-1622696458-cert-policy, expecting a compliance |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1622696458 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1622696458 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622696458 details at the detailed page |
| :x: | failed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622696458 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1622696458 cluster local-cluster template test-iam-policy-1622696458-limit-clusteradmin |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1622696458 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1622696458 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622696458 details at the detailed page |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622696458 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1622696458 cluster local-cluster template test-pod-security-policy-1622696458-restricted-psp |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1622696458 status to become available |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check disabled policy test-role-policy-1622696458 |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that enforced policy test-role-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that policy test-role-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Create new policy test-role-policy-1622696458 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Deleted policy test-role-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Disable policy test-role-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enable policy test-role-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enforce policy test-role-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Policy test-role-policy-1622696458 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622696458 details at the detailed page |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622696458 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1622696458 cluster local-cluster template test-role-policy-1622696458-deployments-role |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for cluster violation status to become available |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check disabled policy test-role-binding-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that enforced policy test-role-binding-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that policy test-role-binding-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Create new policy test-role-binding-policy-1622696458 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Deleted policy test-role-binding-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Disable policy test-role-binding-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enable policy test-role-binding-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enforce policy test-role-binding-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Policy test-role-binding-policy-1622696458 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622696458 details at the detailed page |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622696458 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1622696458 cluster local-cluster template test-role-binding-policy-1622696458-operatoruser-rolebinding |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for policy test-role-binding-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check disabled policy test-security-context-constraints-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that enforced policy test-security-context-constraints-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that policy test-security-context-constraints-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Create new policy test-security-context-constraints-policy-1622696458 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Deleted policy test-security-context-constraints-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Disable policy test-security-context-constraints-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enable policy test-security-context-constraints-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enforce policy test-security-context-constraints-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Policy test-security-context-constraints-policy-1622696458 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622696458 details at the detailed page |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622696458 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1622696458 cluster local-cluster template test-security-context-constraints-policy-1622696458-restricted-scc |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for policy test-security-context-constraints-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1622696458 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1622696458 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622696458 details at the detailed page |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622696458 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1622696458 cluster local-cluster template test-namespace-policy-1622696458-prod-ns |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1622696458 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1622696458 can be deleted in the policy listing |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622696458 details at the detailed page |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622696458 violations at the Status - Templates page |
| :x: | failed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1622696458 cluster local-cluster template test-limitrange-policy-1622696458-container-mem-limit-range |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1622696458 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1622696458 is not present |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create certificate policy policy-certificatepolicy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1622696458 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1622696458 |
| :x: | failed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1622696458 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1622696458 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1622696458 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Wait for certificate policy policy-certificatepolicy-1622696458 status to become available |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1622696458 status becomes available |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1622696458 is not present |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1622696458 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-rhacm4k-1205-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1622696458 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1622696458 |
| :x: | failed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1622696458 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1622696458 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1622696458 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon "Govern risk" page can be launched. |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-certificate-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-issuer-1622696458 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-certificate-1622696458 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-issuer-1622696458 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-certificate-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-issuer-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1622696458 status to become available |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1622696458 status to become available |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy edit page as e2e-view-ns |
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
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible resources created on the target cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm resources created on the target cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm timewindow - helm: ui-helm |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 resources created on the target cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 timewindow - helm: ui-helm2 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj resources created on the target cluster |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj timewindow - objectstore: ui-obj |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm channels, subscription and placementrule are valid - helm: ui-helm |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm2 channels, subscription and placementrule are valid - helm: ui-helm2 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-obj channels, subscription and placementrule are valid - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if not running on localhost |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if not running on localhost |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if not running on localhost |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm2 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-helm is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-helm was selected |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm single app page info is valid after new subscription is created |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm template editor valid after new subscription is created |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm are properly shown in the app Editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm2 are properly shown in the app Editor |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected" |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource git - ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2 |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :x: | failed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode" |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1622696458 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1622696458 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1622696458 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1622696458 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1622696458 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1622696458 status to become available |
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
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Integration] Checking replicas in advanced config for each component (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Checking default value of PVC and StorageClass (config/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the alertmanager configured in rule (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Stable] Should run grafana-dev test successfully (grafana-dev/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Modifying MCO cr to enable observabilityaddon |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have endpoint-operator and metrics-collector being deployed |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement defined in CR |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement in metrics-collector |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should not have the expected MCO addon pods when disable observabilityaddon |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Waiting for check no metric data in grafana console |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Integration] Modifying managedcluster cr to enable observability |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Stable] Modifying managedcluster cr to disable observability |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Deleting metrics-collector deployment |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Updating metrics-collector deployment |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Integration] Checking resources in advanced config (config/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Integration] Should have metrics which defined in custom metrics allowlist (metricslist/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Integration] Should have no metrics after custom metrics allowlist deleted (metricslist/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Integration] Should have not metrics which have been marked for deletion in matches section (metricslist/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Integration] Should have not metrics which have been marked for deletion in names section (metricslist/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check compact args: --delete-delay=50h (retention/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check receive args: --tsdb.retention=5d (retention/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check rule args: --tsdb.block-duration=3h (retention/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check rule args: --tsdb.retention=5d (retention/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check store args: --ignore-deletion-marks-delay=25h (retention/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0) |
| :white_check_mark: | passed | Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |
| :white_check_mark: | passed | Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0) |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-731[P1][Sev1][observability-usa] Login: search-e2e-admin-cluster user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-731[P1][Sev1][observability-usa] Logout: search-e2e-admin-cluster user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-731[P2][Sev2][observability-usa] As an user with name search-e2e-admin-cluster with cluster-role-binding of default admin role, the user can read the Overview page. |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-919[P1][Sev1][observability-usa] Login: search-e2e-view-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-919[P1][Sev1][observability-usa] Logout: search-e2e-view-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-919[P2][Sev2][observability-usa] As an user with name search-e2e-view-ns with ns-role-binding of default view role, the user can read the Overview page. |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-920[P1][Sev1][observability-usa] Login: search-e2e-edit-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-920[P1][Sev1][observability-usa] Logout: search-e2e-edit-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-920[P2][Sev2][observability-usa] As an user with name search-e2e-edit-ns with ns-role-binding of default edit role, the user can read the Overview page. |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-921[P1][Sev1][observability-usa] Login: search-e2e-admin-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-921[P1][Sev1][observability-usa] Logout: search-e2e-admin-ns user |
| :white_check_mark: | passed | RBAC users to read the Overview page RHACM4K-921[P2][Sev2][observability-usa] As an user with name search-e2e-admin-ns with ns-role-binding of default admin role, the user can read the Overview page. |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Create Pod policy issue2444-1622696458-pod-policy from YAML, expecting a compliance |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Delete Pod policy issue2444-1622696458-pod-policy |
| :x: | failed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Check Specifications CertificatePolicy,EtcdEncryption |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Category PR.DS Data Security has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Controls PR.DS-1 Data-at-rest,PR.DS-2 Data-in-transit have been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Specifications CertificatePolicy,EtcdEncryption are selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Standard NIST-CSF has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1695: Search - verify managed cluster info in the search page [P1][Sev1][observability-usa] Search - verify managed cluster info in the search page. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind application on specific namespace. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod and namespace open-cluster-management. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod on specific cluster. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:certpolicycontroller. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:iampolicycontroller. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Verify a deleted pod is recreated. |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by active |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apigroup |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apiversion |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by architecture |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by available |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by capacity |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by claimRef |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cluster |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by clusterIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by completions |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by consoleURL |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by container |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cpu |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by created |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by current |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by desired |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by hostIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by kubernetesVersion |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by lastSchedule |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by memory |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by nodes |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by osImage |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by parallelism |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by podIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by port |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by ready |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by reclaimPolicy |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by request |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by restarts |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by startedAt |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by successful |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by suspend |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by type |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by updated |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by volumeName |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1622696458 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1622696458 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1622696458 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1622696458 using the form |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1622696458 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1622696458 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1622696458 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1622696458 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622696458 details at the detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622696458 violations at the Status - Templates page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1622696458 cluster local-cluster template test-pod-policy-1622696458-nginx-pod |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1622696458 status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy t-imp-1622696458 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy t-imp-1622696458 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy t-imp-1622696458 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy t-imp-1622696458 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy t-imp-1622696458 using the form |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy t-imp-1622696458 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy t-imp-1622696458 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy t-imp-1622696458 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy t-imp-1622696458 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy t-imp-1622696458 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1622696458 details at the detailed page |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1622696458 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1622696458 violations at the Status - Templates page |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1622696458 cluster local-cluster template t-imp-1622696458-image-vulnerability |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1622696458 cluster local-cluster template t-imp-1622696458-subscription |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy t-imp-1622696458 status to become available |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Namespace policy to create template ns as duplicatetest |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with default as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with duplicatetest as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Delete created policies |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1622696458 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1622696458 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1622696458 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1622696458 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1622696458 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1622696458 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1622696458 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1622696458 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1622696458 status to become available |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check long but valid policy name pattern |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check that invalid policy name pattern issues an error |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check warning about a policy with a duplicate name |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Cleanup: delete previously created policy |
| :white_check_mark: | passed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :white_check_mark: | passed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Check form is updated when whole policy YAML is pasted into YAML editor |
| :white_check_mark: | passed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Individual YAML updates are reflected in a form |
| :white_check_mark: | passed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Create policy for the URL visit |
| :white_check_mark: | passed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Delete the policy |
| :white_check_mark: | passed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Verify URLs for Namespace and policy that do exist |
| :white_check_mark: | passed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy Verify URLs for Namespace and policy that dont exist |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for CertificatePolicy specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for ComplianceOperator specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for EtcdEncryption specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for GatekeeperOperator specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for IamPolicy specification |
| :x: | failed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for ImageManifestVulnPolicy specification |
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
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-gatekeeper-1622696458 into YAML editor |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-limitrange-1622696458 into YAML editor |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-gatekeeper-1622696458 to an Enforced state and then back to Inform |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-limitrange-1622696458 to an Enforced state and then back to Inform |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Verify that YAML editor content matches the template |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-operator |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-sample |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
| :x: | failed | RHACM4K-412 - Search: Saved searches "after all" hook for "[P2][Sev2][observability-usa] should be able to share the saved searches" |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to edit the saved searches |
| :x: | failed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to find the saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to revert back the edited saved searches |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to save current search |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should find each managed cluster has default namespace |
| :white_check_mark: | passed | RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should find open-cluster-management-agent namespace exists |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P1][Sev1][observability-usa] should create namespace and application |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P2][Sev2][observability-usa] should find expected application and delete application |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in kube-system on imported cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on imported cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on hub cluster. |
| :white_check_mark: | passed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on imported cluster. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod. |
| :white_check_mark: | passed | Search: Linked page [P2][Sev2][observability-usa] clusters page should have link to search page |
| :white_check_mark: | passed | Search: Overview page [P1][Sev1][observability-usa] should load the overview page |
| :white_check_mark: | passed | Search: Overview page [P2][Sev2][observability-usa] add cloud connection action works |
| :white_check_mark: | passed | Search: Overview page [P2][Sev2][observability-usa] should have link to search page |
| :x: | failed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should create deployment from create resource UI |
| :x: | failed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should create namespace from create resource UI |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should load the search page |
| :white_check_mark: | passed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should not see any cluster and namespace |
| :x: | failed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that deployment resource exist |
| :x: | failed | Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that namespace already exist |
| :x: | failed | Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for deployment |
| :x: | failed | Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for pod |
| :x: | failed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete deployment |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete namespace |
| :x: | failed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete pod |
| :x: | failed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should see pod logs |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should validate deployment was deleted |
| :white_check_mark: | passed | Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should validate namespace was deleted |
| :x: | failed | Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should have expected count of relationships |
| :x: | failed | Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should scale deployment |
| :x: | failed | Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should verify that the deployment scaled |
| :x: | failed | Search: Search in Managed Cluster "before all" hook for "[P1][Sev1][observability-usa] should load the search page" |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by combination with "next suggestion" value and "label" filter with "next suggestion" value |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by combination with "next suggestion" value and "name" filter with "next suggestion" value |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by multiple values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should filter by next suggestion |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "kind" filter should suggest values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "label" filter should filter by next suggestion |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "label" filter should suggest values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "name" filter should filter by next suggestion |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "name" filter should suggest values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by master |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by multiple values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should filter by worker |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "role" filter should suggest values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should filter by multiple values |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should filter by next suggestion |
| :white_check_mark: | passed | Search: Search using filters [P1][Sev1][observability-usa] Search using "status" filter should suggest values |
| :white_check_mark: | passed | Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the created last hour template & search tag in search items |
| :white_check_mark: | passed | Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the unhealthy pods template & search tag in search items |
| :white_check_mark: | passed | Search: Verify the suggested search templates [P3][Sev3][observability-usa] should see the workloads template & search tag in search items |
| :white_check_mark: | passed | [P0][sev1][kui]Visual Web Terminal: Verify user path for rbash |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify KUI multiple tabs |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify kubectl |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify oc |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify supported CLIs can execute |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify user home folder permissions |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify KUI getting started command |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify commands are disabled - rbash |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify product header |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus |
| :white_check_mark: | passed | [P2][sev3][kui]Visual Web Terminal: Verify supported themes |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :x: | failed | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


---

### Failed Test Details

#### :x: @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1622696458 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13019:31)
```

#### :x: @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status

```
AssertionError: Timed out retrying after 30000ms: Expected <span.pf-c-spinner.pf-m-xl.patternfly-spinner> not to exist in the DOM, but it was continuously found.
    at Object.shouldNotExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12004:55)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11684:64)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622696458 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622696458 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13019:31)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622696458 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622696458 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13019:31)
```

#### :x: @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1622696458 cluster local-cluster template test-pod-security-policy-1622696458-restricted-psp

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13290:28)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster local-cluster violations

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12940:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1622696458

```
AssertionError: Timed out retrying after 30000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#3e8635'
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12367:42)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622696458 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: expected '<svg>' to have attribute 'fill' with the value '#c9190b', but the value was '#3e8635'
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12640:42)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622696458 violations at the Status - Clusters page

```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:4807:13)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1622696458 cluster local-cluster template test-role-policy-1622696458-deployments-role

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/violation - roles not found: \[deployments-role\] in namespace default missing/' within the element: [ <td>, 8 more... ] but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13288:20)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for cluster violation status to become available

```
CypressError: `cy.type()` failed because this element is detached from the DOM.

`<input class="pf-c-search-input__text-input" placeholder="Find policies" aria-label="Search input" value="test-role-policy-1622696458">`

Cypress requires elements be attached in the DOM to interact with them.

The previous command that ran was:

  > `cy.clear()`

This DOM element likely became detached somewhere between the previous and current command.

Common situations why this happens:
  - Your JS framework re-rendered asynchronously
  - Your app code reacted to an event firing and removed the element

You typically need to re-query for the element or add 'guards' which delay Cypress from running new commands.

https://on.cypress.io/element-has-detached-from-dom
    at ensureAttached (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:142509:24)
    at validateType (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:142356:11)
    at Object.ensureSubjectByType (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:142396:9)
    at pushSubjectAndValidate (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:151316:15)
    at Context.<anonymous> (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:151668:18)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12944:8)
```

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1622696458 status to become available

```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:4807:13)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622696458 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622696458 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13019:31)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1622696458 cluster local-cluster template test-role-binding-policy-1622696458-operatoruser-rolebinding

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13290:28)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622696458 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622696458 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13019:31)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1622696458 cluster local-cluster template test-security-context-constraints-policy-1622696458-restricted-scc

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13290:28)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622696458 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622696458 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13019:31)
```

#### :x: @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1622696458 cluster local-cluster template test-namespace-policy-1622696458-prod-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13290:28)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622696458 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622696458 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13019:31)
```

#### :x: @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1622696458 cluster local-cluster template test-limitrange-policy-1622696458-container-mem-limit-range

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13290:28)
```

#### :x: @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1622696458 on the detailed policy page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1622696458 on the detailed policy page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-edit-cluster

```
AssertionError: Timed out retrying after 30000ms: expected '<button#create-policy.pf-c-button.pf-m-primary>' to have attribute 'aria-disabled' with the value 'true', but the value was 'false'
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13453:28)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11883:59)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1622696458-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-edit-cluster

```
AssertionError: Timed out retrying after 30000ms: expected 'https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/multicloud/policies/create' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4547:16)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1622696458-e2e-rbac-test-1 policy Status page as e2e-edit-cluster

```
AssertionError: Timed out retrying after 30000ms: expected '<a>' to have class 'link-disabled'
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11921:81)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before each" hook for "get the name of the managed OCP cluster"

```
TypeError: Cannot read property 'match' of undefined

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:556:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:556:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:556:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:556:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:556:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055

```
AssertionError: Timed out retrying after 20000ms: expected '<div#edit-button-portal-id>' to be 'visible'

This element `<div#edit-button-portal-id>` is not visible because it has an effective width and height of: `0 x 0` pixels.
    at validateDefect7696 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:2219:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:129:44)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster

```
AssertionError: Timed out retrying after 4000ms: expected '' to include 'ui-git-subscription-1'
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:302:24)
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
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:334:12)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible

```
CypressError: `cy.exec('oc get subscription ui-git-ansible-subscription-1 -n ui-git-ansible-ns -o yaml')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ansible-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:334:12)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm resources created on the target cluster

```
AssertionError: Timed out retrying after 4000ms: expected '' to include 'ui-helm-subscription-1'
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:302:24)
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
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:334:12)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 resources created on the target cluster

```
AssertionError: Timed out retrying after 4000ms: expected '' to include 'ui-helm2-subscription-1'
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:302:24)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 timewindow - helm: ui-helm2

```
CypressError: `cy.exec('oc get subscription ui-helm2-subscription-1 -n ui-helm2-ns -o yaml')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-helm2-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:334:12)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj resources created on the target cluster

```
AssertionError: Timed out retrying after 4000ms: expected '' to include 'ui-obj-subscription-1'
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:302:24)
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
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:334:12)
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
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:250:13)
    at channels (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:268:3)
    at apiResources (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible

```
CypressError: `cy.exec('oc -n ui-git-ansible-ns get subscription ui-git-ansible-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ansible-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:250:13)
    at channels (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:268:3)
    at apiResources (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
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
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:250:13)
    at channels (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:268:3)
    at apiResources (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm2 channels, subscription and placementrule are valid - helm: ui-helm2

```
CypressError: `cy.exec('oc -n ui-helm2-ns get subscription ui-helm2-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-helm2-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:250:13)
    at channels (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:268:3)
    at apiResources (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
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
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:250:13)
    at channels (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:268:3)
    at apiResources (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:184:7)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/04-validate-backend.spec.js:115:41)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1211:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:883:25)
    at deleteFirstSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:935:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-git-ansible-ns/ui-git-ansible"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1211:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:883:25)
    at deleteFirstSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:935:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1211:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:883:25)
    at deleteFirstSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:935:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm2

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-helm2-ns/ui-helm2"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1211:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:883:25)
    at deleteFirstSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:935:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1211:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:883:25)
    at deleteFirstSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:935:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:110:52)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1211:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:883:25)
    at verifyEditAfterDeleteSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:988:5)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:115:64)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-helm is valid after first subscription is deleted and selecting new placement rule, defect #7359

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1211:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:883:25)
    at verifyEditAfterDeleteSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:988:5)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:115:64)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:1211:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:883:25)
    at verifyEditAfterDeleteSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:988:5)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/02-edit-application-delete-subs.spec.js:115:64)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1217:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:889:25)
    at addNewSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:971:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1217:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:889:25)
    at addNewSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:971:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:1217:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:889:25)
    at addNewSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:971:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/04-edit-application-insert-subs.spec.js:121:49)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:549:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:549:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:549:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/03-edit-application-delete-subs-validate.spec.js:122:47)
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
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:2376:13)
    at verifyInsecureSkipAfterNewSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1044:38)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:125:71)
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
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:2376:13)
    at verifyInsecureSkipAfterNewSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1044:38)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:125:71)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:569:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:142:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1238:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:910:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1029:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm single app page info is valid after new subscription is created

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:569:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:142:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm template editor valid after new subscription is created

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1238:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:910:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1029:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created

```
AssertionError: Timed out retrying after 20000ms: Expected to find element: `#app-search-link`, but never found it.
    at validateTopology (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:569:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:142:47)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1238:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:910:25)
    at verifyEditAfterNewSubscription (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:1029:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/05-edit-application-insert-subs-validate.spec.js:120:61)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1205:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:877:25)
    at editApplication (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:898:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-git-ansible-ns/ui-git-ansible"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1205:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:877:25)
    at editApplication (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:898:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm are properly shown in the app Editor

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1205:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:877:25)
    at editApplication (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:898:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm2 are properly shown in the app Editor

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-helm2-ns/ui-helm2"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1205:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:877:25)
    at editApplication (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:898:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:1205:37)
    at edit (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:877:25)
    at editApplication (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:898:3)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/03-edit/01-validate-edit-application-spec.js:110:44)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test "before each" hook for "Verify invalid input is rejected"

```
TypeError: Cannot read property 'match' of undefined

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before each" hook for "Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm"

```
TypeError: Cannot read property 'match' of undefined

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git

```
CypressError: `cy.exec('oc -n ui-git-ns get subscription ui-git-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-git-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:2355:13)
    at validateAdvancedTables (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:486:40)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:119:53)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj

```
CypressError: `cy.exec('oc -n ui-obj-ns get subscription ui-obj-subscription-1 -o=jsonpath='{.spec.channel}'')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (NotFound): namespaces "ui-obj-ns" not found

https://on.cypress.io/exec
    at https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:136589:26
    at tryCatcher (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:10747:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8682:31)
    at Promise._settlePromise (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8739:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8784:10)
    at Promise._settlePromises (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:8864:18)
    at _drainQueueStep (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5454:12)
    at _drainQueue (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5447:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5463:5)
    at Async.drainQueues (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/runner/cypress_runner.js:5333:14)
From Your Spec Code:
    at channelsInformation (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:2355:13)
    at validateAdvancedTables (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:486:40)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:119:53)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git

```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-git-ns/ui-git"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1212:37)
    at validateResourceTable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:710:25)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible

```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-git-ansible-ns/ui-git-ansible"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1212:37)
    at validateResourceTable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:710:25)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm

```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-helm-ns/ui-helm"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1212:37)
    at validateResourceTable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:710:25)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2

```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-helm2-ns/ui-helm2"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1212:37)
    at validateResourceTable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:710:25)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj

```
AssertionError: Timed out retrying after 60000ms: Expected to find element: `[data-ouia-component-type="PF4/TableRow"][data-ouia-component-id="local-cluster/ui-obj-ns/ui-obj"]`, but never found it.
    at Object.rowShouldExist (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:1212:37)
    at validateResourceTable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:710:25)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```

#### :x: Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test "before each" hook for "Skipping git api validation test, this test is only run against localhost, PR execution and is not run in smoke test mode"

```
TypeError: Cannot read property 'match' of undefined

Because this error occurred during a `before each` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=cypress/support/index.js:810:42)
```

#### :x: Observability: [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_default_config_test.go:30
Expected
    <int64>: 60
to equal
    <int64>: 30
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_default_config_test.go:37
```

#### :x: Observability: [P1][Sev1][Observability][Stable] Should run grafana-dev test successfully (grafana-dev/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_grafana_dev_test.go:19
Timed out after 600.000s.
Expected success, but got an error:
    <*os.PathError | 0xc0003020c0>: {
        Op: "fork/exec",
        Path: "../../cicd-scripts/grafana-dev-test.sh",
        Err: 0x2,
    }
    fork/exec ../../cicd-scripts/grafana-dev-test.sh: no such file or directory
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_grafana_dev_test.go:29
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement defined in CR

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:67
Test Panicked
/usr/local/go/src/runtime/iface.go:260

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/observability-e2e-test/pkg/utils.GetMCOAddonSpecResources(0x0, 0x0, 0x0, 0x0, 0x0, 0xc000180090, 0x29, 0x0, 0x0, 0x0, ...)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/utils/mco_deploy.go:775 +0x29d
github.com/open-cluster-management/observability-e2e-test/pkg/tests.glob..func3.2.2()
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:69 +0x7e
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc000419620, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc000419620, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:64 +0xcf
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc0002a0ae0, 0x1a9d000, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/it_node.go:26 +0x64
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc00041b590, 0x0, 0x1a9d000, 0xc0000de8c0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:215 +0x638
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc00041b590, 0x1a9d000, 0xc0000de8c0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc0002c0f00, 0xc00041b590, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:200 +0x10f
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc0002c0f00, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:170 +0x120
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc0002c0f00, 0xc0000a8c20)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc0000fa070, 0x7f21cc3fb118, 0xc0002c7c20, 0x1872919, 0x17, 0xc0002a0380, 0x2, 0x2, 0x1aebce0, 0xc0000de8c0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/suite/suite.go:79 +0x586
github.com/onsi/ginkgo.RunSpecsWithCustomReporters(0x1a9e520, 0xc0002c7c20, 0x1872919, 0x17, 0xc0002a0300, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:229 +0x217
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1a9e520, 0xc0002c7c20, 0x1872919, 0x17, 0xc000056f60, 0x1, 0x1, 0xc000056f70)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:217 +0xad
github.com/open-cluster-management/observability-e2e-test/pkg/tests.TestObservabilityE2E(0xc0002c7c20)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:90 +0x117
testing.tRunner(0xc0002c7c20, 0x19157d0)
	/usr/local/go/src/testing/testing.go:991 +0xdc
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1042 +0x357
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement in metrics-collector

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:79
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc000178e70>: {
        s: "metrics-collector-deployment resource <{map[cpu:{{100 -3} {<nil>} 100m DecimalSI} memory:{{629145600 0} {<nil>}  BinarySI}] map[cpu:{{100 -3} {<nil>} 100m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{209715200 0} {<nil>}  BinarySI}]}>",
    }
    metrics-collector-deployment resource <{map[cpu:{{100 -3} {<nil>} 100m DecimalSI} memory:{{629145600 0} {<nil>}  BinarySI}] map[cpu:{{100 -3} {<nil>} 100m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{209715200 0} {<nil>}  BinarySI}]}>
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:83
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check compact args: --delete-delay=50h (retention/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:30
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc00014abb0>: {
        s: "Failed to check compact args: --delete-delay=50h. args is [compact --wait --log.level=info --log.format=logfmt --objstore.config=$(OBJSTORE_CONFIG) --data-dir=/var/thanos/compact --debug.accept-malformed-index --retention.resolution-raw=30d --retention.resolution-5m=180d --retention.resolution-1h=0d --delete-delay=48h --deduplication.replica-label=replica]",
    }
    Failed to check compact args: --delete-delay=50h. args is [compact --wait --log.level=info --log.format=logfmt --objstore.config=$(OBJSTORE_CONFIG) --data-dir=/var/thanos/compact --debug.accept-malformed-index --retention.resolution-raw=30d --retention.resolution-5m=180d --retention.resolution-1h=0d --delete-delay=48h --deduplication.replica-label=replica]
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:44
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check receive args: --tsdb.retention=5d (retention/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:64
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc000178880>: {
        s: "Failed to check receive args: --tsdb.retention=5d. args is [receive --log.level=info --log.format=logfmt --grpc-address=0.0.0.0:10901 --http-address=0.0.0.0:10902 --remote-write.address=0.0.0.0:19291 --receive.replication-factor=3 --objstore.config=$(OBJSTORE_CONFIG) --tsdb.path=/var/thanos/receive --tsdb.retention=24h --receive.local-endpoint=$(NAME).observability-thanos-receive-default.$(NAMESPACE).svc.cluster.local:10901 --label=replica=\"$(NAME)\" --label=receive=\"true\" --receive.hashrings-file=/var/lib/thanos-receive/hashrings.json]",
    }
    Failed to check receive args: --tsdb.retention=5d. args is [receive --log.level=info --log.format=logfmt --grpc-address=0.0.0.0:10901 --http-address=0.0.0.0:10902 --remote-write.address=0.0.0.0:19291 --receive.replication-factor=3 --objstore.config=$(OBJSTORE_CONFIG) --tsdb.path=/var/thanos/receive --tsdb.retention=24h --receive.local-endpoint=$(NAME).observability-thanos-receive-default.$(NAMESPACE).svc.cluster.local:10901 --label=replica="$(NAME)" --label=receive="true" --receive.hashrings-file=/var/lib/thanos-receive/hashrings.json]
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:78
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check rule args: --tsdb.block-duration=3h (retention/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:98
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0001a5880>: {
        s: "Failed to check rule args: --tsdb.block-duration=3h. args is [rule --log.level=info --log.format=logfmt --grpc-address=0.0.0.0:10901 --http-address=0.0.0.0:10902 --objstore.config=$(OBJSTORE_CONFIG) --data-dir=/var/thanos/rule --label=rule_replica=\"$(NAME)\" --alert.label-drop=rule_replica --tsdb.retention=24h --tsdb.block-duration=2h --query=dnssrv+_http._tcp.observability-thanos-query.open-cluster-management-observability.svc.cluster.local --alertmanagers.config-file=/etc/thanos/config/thanos-ruler-config/config.yaml --rule-file=/etc/thanos/rules/thanos-ruler-default-rules/default_rules.yaml]",
    }
    Failed to check rule args: --tsdb.block-duration=3h. args is [rule --log.level=info --log.format=logfmt --grpc-address=0.0.0.0:10901 --http-address=0.0.0.0:10902 --objstore.config=$(OBJSTORE_CONFIG) --data-dir=/var/thanos/rule --label=rule_replica="$(NAME)" --alert.label-drop=rule_replica --tsdb.retention=24h --tsdb.block-duration=2h --query=dnssrv+_http._tcp.observability-thanos-query.open-cluster-management-observability.svc.cluster.local --alertmanagers.config-file=/etc/thanos/config/thanos-ruler-config/config.yaml --rule-file=/etc/thanos/rules/thanos-ruler-default-rules/default_rules.yaml]
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:112
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check rule args: --tsdb.retention=5d (retention/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:81
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0003da9a0>: {
        s: "Failed to check rule args: --tsdb.retention=5d. args is [rule --log.level=info --log.format=logfmt --grpc-address=0.0.0.0:10901 --http-address=0.0.0.0:10902 --objstore.config=$(OBJSTORE_CONFIG) --data-dir=/var/thanos/rule --label=rule_replica=\"$(NAME)\" --alert.label-drop=rule_replica --tsdb.retention=24h --tsdb.block-duration=2h --query=dnssrv+_http._tcp.observability-thanos-query.open-cluster-management-observability.svc.cluster.local --alertmanagers.config-file=/etc/thanos/config/thanos-ruler-config/config.yaml --rule-file=/etc/thanos/rules/thanos-ruler-default-rules/default_rules.yaml]",
    }
    Failed to check rule args: --tsdb.retention=5d. args is [rule --log.level=info --log.format=logfmt --grpc-address=0.0.0.0:10901 --http-address=0.0.0.0:10902 --objstore.config=$(OBJSTORE_CONFIG) --data-dir=/var/thanos/rule --label=rule_replica="$(NAME)" --alert.label-drop=rule_replica --tsdb.retention=24h --tsdb.block-duration=2h --query=dnssrv+_http._tcp.observability-thanos-query.open-cluster-management-observability.svc.cluster.local --alertmanagers.config-file=/etc/thanos/config/thanos-ruler-config/config.yaml --rule-file=/etc/thanos/rules/thanos-ruler-default-rules/default_rules.yaml]
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:95
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check store args: --ignore-deletion-marks-delay=25h (retention/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:47
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0006be5b0>: {
        s: "Failed to check store args: --ignore-deletion-marks-delay=25h. args is [store --log.level=info --log.format=logfmt --data-dir=/var/thanos/store --grpc-address=0.0.0.0:10901 --http-address=0.0.0.0:10902 --objstore.config=$(OBJSTORE_CONFIG) --ignore-deletion-marks-delay=24h --index-cache.config=\"config\":\n  \"addresses\":\n  - \"dnssrv+_client._tcp.observability-thanos-store-memcached.open-cluster-management-observability.svc\"\n  \"dns_provider_update_interval\": \"10s\"\n  \"max_async_buffer_size\": 100000\n  \"max_async_concurrency\": 100\n  \"max_get_multi_batch_size\": 1000\n  \"max_get_multi_concurrency\": 900\n  \"max_idle_connections\": 1000\n  \"max_item_size\": \"1MiB\"\n  \"timeout\": \"2s\"\n\"type\": \"memcached\" --store.caching-bucket.config=\"blocks_iter_ttl\": \"5m\"\n\"chunk_object_attrs_ttl\": \"24h\"\n\"chunk_subrange_size\": 16000\n\"chunk_subrange_ttl\": \"24h\"\n\"config\":\n  \"addresses\":\n  - \"dnssrv+_client._tcp.observability-thanos-store-memcached.open-cluster-management-observability.svc\"\n  \"dns_provider_update_interval\": \"10s\"\n  \"max_async_buffer_size\": 100000\n  \"max_async_concurrency\": 100\n  \"max_get_multi_batch_size\": 1000\n  \"max_get_multi_concurrency\": 900\n  \"max_idle_connections\": 1000\n  \"max_item_size\": \"1MiB\"\n  \"timeout\": \"2s\"\n\"max_chunks_get_range_requests\": 3\n\"metafile_content_ttl\": \"24h\"\n\"metafile_doesnt_exist_ttl\": \"15m\"\n\"metafile_exists_ttl\": \"2h\"\n\"metafile_max_size\": \"1MiB\"\n\"type\": \"memcached\" --selector.relabel-config=\n  - action: hashmod\n    source_labels: [\"__block_id\"]\n    target_label: shard\n    modulus: 3\n  - action: keep\n    source_labels: [\"shard\"]\n    regex: 0\n]",
    }
    Failed to check store args: --ignore-deletion-marks-delay=25h. args is [store --log.level=info --log.format=logfmt --data-dir=/var/thanos/store --grpc-address=0.0.0.0:10901 --http-address=0.0.0.0:10902 --objstore.config=$(OBJSTORE_CONFIG) --ignore-deletion-marks-delay=24h --index-cache.config="config":
      "addresses":
      - "dnssrv+_client._tcp.observability-thanos-store-memcached.open-cluster-management-observability.svc"
      "dns_provider_update_interval": "10s"
      "max_async_buffer_size": 100000
      "max_async_concurrency": 100
      "max_get_multi_batch_size": 1000
      "max_get_multi_concurrency": 900
      "max_idle_connections": 1000
      "max_item_size": "1MiB"
      "timeout": "2s"
    "type": "memcached" --store.caching-bucket.config="blocks_iter_ttl": "5m"
    "chunk_object_attrs_ttl": "24h"
    "chunk_subrange_size": 16000
    "chunk_subrange_ttl": "24h"
    "config":
      "addresses":
      - "dnssrv+_client._tcp.observability-thanos-store-memcached.open-cluster-management-observability.svc"
      "dns_provider_update_interval": "10s"
      "max_async_buffer_size": 100000
      "max_async_concurrency": 100
      "max_get_multi_batch_size": 1000
      "max_get_multi_concurrency": 900
      "max_idle_connections": 1000
      "max_item_size": "1MiB"
      "timeout": "2s"
    "max_chunks_get_range_requests": 3
    "metafile_content_ttl": "24h"
    "metafile_doesnt_exist_ttl": "15m"
    "metafile_exists_ttl": "2h"
    "metafile_max_size": "1MiB"
    "type": "memcached" --selector.relabel-config=
      - action: hashmod
        source_labels: ["__block_id"]
        target_label: shard
        modulus: 3
      - action: keep
        source_labels: ["shard"]
        regex: 0
    ]
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:61
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:123
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0001a4b50>: {
        s: "the storage size of statefulset observability-alertmanager should have 2Gi but got {{1073741824 0} {<nil>} 1Gi BinarySI}",
    }
    the storage size of statefulset observability-alertmanager should have 2Gi but got {{1073741824 0} {<nil>} 1Gi BinarySI}
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:131
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:50
Test Panicked
/usr/local/go/src/runtime/iface.go:260

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/observability-e2e-test/pkg/utils.ModifyMCOCR(0x0, 0x0, 0x0, 0x0, 0x0, 0xc000180090, 0x29, 0x0, 0x0, 0x0, ...)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/utils/mco_deploy.go:580 +0x522
github.com/open-cluster-management/observability-e2e-test/pkg/tests.glob..func15.2()
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:52 +0x9b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc000185e60, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc000185e60, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:64 +0xcf
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc0000b92a0, 0x1a9d000, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/it_node.go:26 +0x64
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc0003b0e10, 0x0, 0x1a9d000, 0xc0000de8c0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:215 +0x638
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc0003b0e10, 0x1a9d000, 0xc0000de8c0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc0002c0f00, 0xc0003b0e10, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:200 +0x10f
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc0002c0f00, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:170 +0x120
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc0002c0f00, 0xc0000a8c20)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc0000fa070, 0x7f21cc3fb118, 0xc0002c7c20, 0x1872919, 0x17, 0xc0002a0380, 0x2, 0x2, 0x1aebce0, 0xc0000de8c0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/suite/suite.go:79 +0x586
github.com/onsi/ginkgo.RunSpecsWithCustomReporters(0x1a9e520, 0xc0002c7c20, 0x1872919, 0x17, 0xc0002a0300, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:229 +0x217
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1a9e520, 0xc0002c7c20, 0x1872919, 0x17, 0xc000056f60, 0x1, 0x1, 0xc000056f70)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:217 +0xad
github.com/open-cluster-management/observability-e2e-test/pkg/tests.TestObservabilityE2E(0xc0002c7c20)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:90 +0x117
testing.tRunner(0xc0002c7c20, 0x19157d0)
	/usr/local/go/src/testing/testing.go:991 +0xdc
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1042 +0x357
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:134
Test Panicked
/usr/local/go/src/runtime/iface.go:260

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/observability-e2e-test/pkg/utils.RevertMCOCRModification(0x0, 0x0, 0x0, 0x0, 0x0, 0xc000180090, 0x29, 0x0, 0x0, 0x0, ...)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/utils/mco_deploy.go:604 +0x453
github.com/open-cluster-management/observability-e2e-test/pkg/tests.glob..func15.6()
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:137 +0x9b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc000076300, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc000076300, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:64 +0xcf
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc0000b9640, 0x1a9d000, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/it_node.go:26 +0x64
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc0003b11d0, 0x0, 0x1a9d000, 0xc0000de8c0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:215 +0x638
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc0003b11d0, 0x1a9d000, 0xc0000de8c0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc0002c0f00, 0xc0003b11d0, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:200 +0x10f
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc0002c0f00, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:170 +0x120
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc0002c0f00, 0xc0000a8c20)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc0000fa070, 0x7f21cc3fb118, 0xc0002c7c20, 0x1872919, 0x17, 0xc0002a0380, 0x2, 0x2, 0x1aebce0, 0xc0000de8c0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/suite/suite.go:79 +0x586
github.com/onsi/ginkgo.RunSpecsWithCustomReporters(0x1a9e520, 0xc0002c7c20, 0x1872919, 0x17, 0xc0002a0300, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:229 +0x217
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1a9e520, 0xc0002c7c20, 0x1872919, 0x17, 0xc000056f60, 0x1, 0x1, 0xc000056f70)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:217 +0xad
github.com/open-cluster-management/observability-e2e-test/pkg/tests.TestObservabilityE2E(0xc0002c7c20)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:90 +0x117
testing.tRunner(0xc0002c7c20, 0x19157d0)
	/usr/local/go/src/testing/testing.go:991 +0xdc
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1042 +0x357
```

#### :x: RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13019:31)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622696458 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622696458 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13019:31)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1622696458 cluster local-cluster template test-pod-policy-1622696458-nginx-pod

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13290:28)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1622696458 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12672:24)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1622696458 violations at the Status - Clusters page

```
TypeError: Cannot read property '0' of undefined
    at getPolicyStatusForViolationId (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13040:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:12570:35)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1622696458 cluster local-cluster template t-imp-1622696458-image-vulnerability

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13290:28)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1622696458 cluster local-cluster template t-imp-1622696458-subscription

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `table[aria-label="Simple Table"]`, but never found it.
    at action_verifyPolicyViolationDetailsInHistory (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13281:6)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11764:73)
```

#### :x: RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for ImageManifestVulnPolicy specification

```
AssertionError: Editor content should match YAML template: expected 'apiVersion: policy.open-cluster-management.io/v1\nkind: Policy\nmetadata:\n  name: imagemanifestvulnpolicy\n  namespace: default\n  annotations:\n    policy.open-cluster-management.io/standards: NIST-CSF\n    policy.open-cluster-management.io/categories: DE.CM Security Continuous Monitoring\n    policy.open-cluster-management.io/controls: DE.CM-8 Vulnerability Scans\nspec:\n  remediationAction: inform\n  disabled: false\n  policy-templates:\n    - objectDefinition:\n        apiVersion: policy.open-cluster-management.io/v1\n        kind: ConfigurationPolicy\n        metadata:\n          name: imagemanifestvulnpolicy-image-vulnerability-sub\n        spec:\n          remediationAction: inform\n          severity: high\n          object-templates:\n            - complianceType: musthave\n              objectDefinition:\n                apiVersion: operators.coreos.com/v1alpha1\n                kind: Subscription\n                metadata:\n                  name: container-security-operator\n                  namespace: openshift-operators\n                spec:\n                  channel: quay-v3.3\n                  installPlanApproval: Automatic\n                  name: container-security-operator\n                  source: redhat-operators\n                  sourceNamespace: openshift-marketplace\n    - objectDefinition:\n        apiVersion: policy.open-cluster-management.io/v1\n        kind: ConfigurationPolicy\n        metadata:\n          name: imagemanifestvulnpolicy-image-vulnerability\n        spec:\n          remediationAction: inform\n          severity: high\n          namespaceSelector:\n            exclude:\n              - kube-*\n            include:\n              - \'*\'\n          object-templates:\n            - complianceType: mustnothave\n              objectDefinition:\n                apiVersion: secscan.quay.redhat.com/v1alpha1\n                kind: ImageManifestVuln\n---\napiVersion: policy.open-cluster-management.io/v1\nkind: PlacementBinding\nmetadata:\n  name: binding-imagemanifestvulnpolicy\n  namespace: default\nplacementRef:\n  name: placement-imagemanifestvulnpolicy\n  kind: PlacementRule\n  apiGroup: apps.open-cluster-management.io\nsubjects:\n  - name: imagemanifestvulnpolicy\n    kind: Policy\n    apiGroup: policy.open-cluster-management.io\n---\napiVersion: apps.open-cluster-management.io/v1\nkind: PlacementRule\nmetadata:\n  name: placement-imagemanifestvulnpolicy\n  namespace: default\nspec:\n  clusterConditions:\n    - status: \'True\'\n      type: ManagedClusterConditionAvailable\n  clusterSelector:\n    matchExpressions:\n      - key: local-cluster\n        operator: In\n        values:\n          - \'true\'\n' to equal 'apiVersion: policy.open-cluster-management.io/v1\nkind: Policy\nmetadata:\n  name: imagemanifestvulnpolicy\n  namespace: default\n  annotations:\n    policy.open-cluster-management.io/standards: NIST-CSF\n    policy.open-cluster-management.io/categories: DE.CM Security Continuous Monitoring\n    policy.open-cluster-management.io/controls: DE.CM-8 Vulnerability Scans\nspec:\n  remediationAction: inform\n  disabled: false\n  policy-templates:\n    - objectDefinition:\n        apiVersion: policy.open-cluster-management.io/v1\n        kind: ConfigurationPolicy\n        metadata:\n          name: imagemanifestvulnpolicy-subscription\n        spec:\n          remediationAction: inform\n          severity: high\n          object-templates:\n            - complianceType: musthave\n              objectDefinition:\n                apiVersion: operators.coreos.com/v1alpha1\n                kind: Subscription\n                metadata:\n                  name: container-security-operator\n                  namespace: openshift-operators\n                spec:\n                  channel: quay-v3.3\n                  installPlanApproval: Automatic\n                  name: container-security-operator\n                  source: redhat-operators\n                  sourceNamespace: openshift-marketplace\n    - objectDefinition:\n        apiVersion: policy.open-cluster-management.io/v1\n        kind: ConfigurationPolicy\n        metadata:\n          name: imagemanifestvulnpolicy-image-vulnerability\n        spec:\n          remediationAction: inform\n          severity: high\n          namespaceSelector:\n            exclude:\n              - kube-*\n            include:\n              - \'*\'\n          object-templates:\n            - complianceType: mustnothave\n              objectDefinition:\n                apiVersion: secscan.quay.redhat.com/v1alpha1\n                kind: ImageManifestVuln\n---\napiVersion: policy.open-cluster-management.io/v1\nkind: PlacementBinding\nmetadata:\n  name: binding-imagemanifestvulnpolicy\n  namespace: default\nplacementRef:\n  name: placement-imagemanifestvulnpolicy\n  kind: PlacementRule\n  apiGroup: apps.open-cluster-management.io\nsubjects:\n  - name: imagemanifestvulnpolicy\n    kind: Policy\n    apiGroup: policy.open-cluster-management.io\n---\napiVersion: apps.open-cluster-management.io/v1\nkind: PlacementRule\nmetadata:\n  name: placement-imagemanifestvulnpolicy\n  namespace: default\nspec:\n  clusterConditions:\n    - status: \'True\'\n      type: ManagedClusterConditionAvailable\n  clusterSelector:\n    matchExpressions:\n      - key: local-cluster\n        operator: In\n        values:\n          - \'true\'\n'
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/policy_YAML_templates_verification.spec.js:4183:16)
```

#### :x: RHACM4K-412 - Search: Saved searches "after all" hook for "[P2][Sev2][observability-usa] should be able to share the saved searches"

```
AssertionError: Timed out retrying after 10000ms: Expected to find content: 'Saved searches' within the element: <h4.pf-c-title.pf-m-md> but never did.

Because this error occurred during a `after all` hook we are skipping the remaining tests in the current suite: `RHACM4K-412 - Search: Saved...`

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Object.whenDeleteSavedSearch (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/savedSearches.spec.js:1197:37)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/savedSearches.spec.js:1005:34)
```

#### :x: RHACM4K-412 - Search: Saved searches [P2][Sev2][observability-usa] should be able to find the saved searches

```
AssertionError: Timed out retrying after 10000ms: Expected to find content: 'Saved searches' within the element: <h4.pf-c-title.pf-m-md> but never did.
    at Object.getSavedSearch (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/savedSearches.spec.js:1188:37)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/savedSearches.spec.js:1031:34)
```

#### :x: Search: Search in Local Cluster [P1][Sev1][observability-usa] should create deployment from create resource UI

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#acm-create-resource`, but never found it.
    at Object.whenGoToResourcePage (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1360:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1115:30)
```

#### :x: Search: Search in Local Cluster [P1][Sev1][observability-usa] should create namespace from create resource UI

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#acm-create-resource`, but never found it.
    at Object.whenGoToResourcePage (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1360:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1101:30)
```

#### :x: Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that deployment resource exist

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#acm-create-resource`, but never found it.
    at Object.whenGoToResourcePage (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1360:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1124:30)
```

#### :x: Search: Search in Local Cluster [P1][Sev1][observability-usa] should verify that namespace already exist

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#acm-create-resource`, but never found it.
    at Object.whenGoToResourcePage (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1360:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1108:30)
```

#### :x: Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for deployment

```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1150:27)
```

#### :x: Search: Search in Local Cluster search resources [P1][Sev1][observability-usa] should work kind filter for pod

```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1155:27)
```

#### :x: Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete deployment

```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1191:27)
```

#### :x: Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should delete pod

```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1168:27)
```

#### :x: Search: Search in Local Cluster search resources [P2][Sev2][observability-usa] should see pod logs

```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1160:27)
```

#### :x: Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should have expected count of relationships

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: ``, but never found it. Queried from element: <div.pf-l-gallery.pf-m-gutter.jss15>
    at Object.whenExpandRelationshipTiles (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1489:19)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1141:28)
```

#### :x: Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should scale deployment

```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1175:27)
```

#### :x: Search: Search in Local Cluster search resources [P3][Sev3][observability-usa] should verify that the deployment scaled

```
AssertionError: Timed out retrying after 10000ms: expected '<li#ReactTags-0.is-disabled>' to have a length above 1 but got 1
    at Object.whenSuggestionsAreAvailable (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1630:66)
    at Object.whenEnterTextInSearchBar (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1642:17)
    at Object.whenFilterByKind (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1655:15)
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/tests/adminSearch.spec.js:1184:27)
```

#### :x: Search: Search in Managed Cluster "before all" hook for "[P1][Sev1][observability-usa] should load the search page"

```
AssertionError: Timed out retrying after 10000ms: Expected to find element: `#inputUsername`, but never found it.

Because this error occurred during a `before all` hook we are skipping the remaining tests in the current suite: `Search: Search in Managed C...`

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at Context.eval (https://multicloud-console.apps.slai-ocp48-aws.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:2657:10)
```

#### :x: e2e-server [P1][Sev1][app-lifecycle] Test argocd integration

```
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:10
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:12
```

