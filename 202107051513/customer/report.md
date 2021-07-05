# :warning: Had some failures when running regression on cluster acm-hub-46 with test snapshot 2.3.0-SNAPSHOT-2021-06-30-15-00-55 

## Jenkins job URL: No Job URL


ACM Version: v2.3.0

Hub Cluster Version: 4.6.28

Hub Cluster: https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com

Managed Cluster Version: 4.8.0-0.nightly-ppc64le-2021-04-21-154953

Managed Cluster: https://console-openshift-console.apps.acm-spoke-48.mon01.ibm-power-acm.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107051513/

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
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: | failed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: | failed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-certificate-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-issuer-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-certificate-1625498936 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1625498936 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-certificate-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-issuer-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1625498936 status to become available |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Check that policy role-binding-cleanup-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Delete policy role-binding-cleanup-policy-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Verify that policy role-binding-cleanup-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Wait for role-binding-cleanup-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Check that policy role-specification-cleanup-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Delete policy role-specification-cleanup-policy-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Verify that policy role-specification-cleanup-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Wait for role-specification-cleanup-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Check that policy scc-cleanup-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Delete policy scc-cleanup-policy-1625498936 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Verify that policy scc-cleanup-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Wait for scc-cleanup-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Check that policy test-issue3677-cert-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Create a customized policy |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Delete policy test-issue3677-cert-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Deleted policy test-issue3677-cert-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Prefill a new policy test-issue3677-cert-policy-1625498936 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Replace namespaceSelector value with "no-such-namespace" |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Wait for policy test-issue3677-cert-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1625498936-create-cert-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1625498936-create-cert-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1625498936-create-issuer-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1625498936-create-issuer-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1625498936-create-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1625498936-create-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1625498936-delete-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1625498936-delete-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete cert policy issue7520-1625498936-cert-policy |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1625498936-create-cert-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1625498936-create-cert-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1625498936-create-issuer-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1625498936-create-issuer-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1625498936-create-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1625498936-create-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1625498936-delete-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1625498936-delete-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1625498936-create-cert-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1625498936-create-cert-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1625498936-create-issuer-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1625498936-create-issuer-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1625498936-create-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1625498936-create-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1625498936-delete-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1625498936-delete-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1625498936-create-cert-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1625498936-create-cert-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1625498936-create-issuer-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1625498936-create-issuer-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1625498936-create-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1625498936-create-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1625498936-delete-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1625498936-delete-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show compliance again |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected create certPolicy issue7520-1625498936-cert-policy, expecting a compliance |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster acm-spoke-48 violations |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1625498936 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Edit policy test-iam-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1625498936 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1625498936 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1625498936 cluster acm-spoke-48 template test-iam-policy-1625498936-limit-clusteradmin |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster acm-spoke-48 violations |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1625498936 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Edit policy test-pod-security-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1625498936 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1625498936 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1625498936 cluster acm-spoke-48 template test-pod-security-policy-1625498936-restricted-psp |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check cluster acm-spoke-48 violations |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check disabled policy test-role-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that enforced policy test-role-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that policy test-role-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Create new policy test-role-policy-1625498936 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Deleted policy test-role-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Disable policy test-role-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Edit policy test-role-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enable policy test-role-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enforce policy test-role-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Policy test-role-policy-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1625498936 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1625498936 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1625498936 cluster acm-spoke-48 template test-role-policy-1625498936-deployments-role |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check cluster acm-spoke-48 violations |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check disabled policy test-role-binding-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that enforced policy test-role-binding-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that policy test-role-binding-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Create new policy test-role-binding-policy-1625498936 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Deleted policy test-role-binding-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Disable policy test-role-binding-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Edit policy test-role-binding-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enable policy test-role-binding-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enforce policy test-role-binding-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Policy test-role-binding-policy-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1625498936 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1625498936 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1625498936 cluster acm-spoke-48 template test-role-binding-policy-1625498936-operatoruser-rolebinding |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for policy test-role-binding-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check cluster acm-spoke-48 violations |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check disabled policy test-security-context-constraints-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that enforced policy test-security-context-constraints-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that policy test-security-context-constraints-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Create new policy test-security-context-constraints-policy-1625498936 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Deleted policy test-security-context-constraints-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Disable policy test-security-context-constraints-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Edit policy test-security-context-constraints-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enable policy test-security-context-constraints-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enforce policy test-security-context-constraints-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Policy test-security-context-constraints-policy-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1625498936 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1625498936 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1625498936 cluster acm-spoke-48 template test-security-context-constraints-policy-1625498936-restricted-scc |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for policy test-security-context-constraints-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster acm-spoke-48 violations |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1625498936 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Edit policy test-namespace-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1625498936 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1625498936 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1625498936 cluster acm-spoke-48 template test-namespace-policy-1625498936-prod-ns |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster acm-spoke-48 violations |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1625498936 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Edit policy test-limitrange-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1625498936 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1625498936 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1625498936 cluster acm-spoke-48 template test-limitrange-policy-1625498936-container-mem-limit-range |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1625498936 is not present |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create certificate policy policy-certificatepolicy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Delete created policy policy-certificatepolicy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1625498936 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1625498936 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1625498936 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1625498936 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Wait for certificate policy policy-certificatepolicy-1625498936 status to become available |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1625498936 status becomes available |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1625498936 is not present |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Delete created policy policy-certificatepolicy-rhacm4k-1205-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1625498936 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1625498936 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1625498936 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1625498936 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1625498936 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon "Govern risk" page can be launched. |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-certificate-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-issuer-1625498936 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-certificate-1625498936 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-issuer-1625498936 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-certificate-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-issuer-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1625498936 status to become available |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1625498936 status to become available |
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
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1625498936-e2e-rbac-test-1 policy page as e2e-view-ns |
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
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy Status page as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-edit-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-group-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-group-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1625498936-e2e-rbac-test-1 policy edit page as e2e-view-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Create policies used for the testing |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Delete test policies |
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
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Verify that CYPRESS_RBAC_PASS environment variable is defined |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-git-ansible can be created from resource type git using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm can be created from resource type helm using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-helm2 can be created from resource type helm using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test Verify application ui-obj can be created from resource type objectstore using template editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git content from the single application topology - git: ui-git |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm content from the single application topology - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-helm2 content from the single application topology - helm: ui-helm2 |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify defects 7696 and 8055 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git timewindow - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-git-ansible timewindow - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm timewindow - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-helm2 timewindow - helm: ui-helm2 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj resources created on the target cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Validate apps ui-obj timewindow - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-git-ansible channels, subscription and placementrule are valid - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm channels, subscription and placementrule are valid - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-helm2 channels, subscription and placementrule are valid - helm: ui-helm2 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist Verify that the apps ui-obj channels, subscription and placementrule are valid - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed Skipping validate delete test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test Skipping cleanup resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test Skipping delete resources test if running canary |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-helm2 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify first subscription can be deleted for app ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-git is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-helm is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test Verify ui-obj is valid after first subscription is deleted and selecting new placement rule, defect #7359 |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-git |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-helm |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test Verify new subscription can be added for application ui-obj |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-git single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-helm single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription Verify that ui-obj single app page info is valid after first subscription is deleted |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-git was selected |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify insecureSkipVerify option in new channel for app ui-helm was selected |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-git template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-helm template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj single app page info is valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription Verify that ui-obj template editor valid after new subscription is created |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the name of the managed OCP cluster |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-git-ansible are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-helm2 are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor Verify that settings for application ui-obj are properly shown in the app Editor |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Creation Validate invalid input Test Verify invalid input is rejected |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables maintain their state across SPA navigation |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-git channel, subscription, placement rule info from the advanced configuration tables - git: ui-git |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-helm channel, subscription, placement rule info from the advanced configuration tables - helm: ui-helm |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Wait for 5 mins... |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource git - ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables disable validation on resource helm - ui-helm2 |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables get the name of the managed OCP cluster |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm info from applications table - helm: ui-helm |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-helm2 info from applications table - helm: ui-helm2 |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj |
| :white_check_mark: | passed | Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table get the number of the managed OCP clusters |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui] Application Creation Validate git api Test Skipping test for canary or smoke test mode |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Application Creation Test Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Delete application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Edit application subscription Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | Application UI: [P3][Sev3][app-lifecycle-ui][RBAC] Validate view application Test Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true` |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1625498936 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1625498936 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1625498936 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1625498936 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1625498936 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1625498936 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P1][Sev1][policy-grc] should load |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P1][Sev1][policy-grc] should redirect from base and /multicloud |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should not show perspective switcher on kube >1.2 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should open left navigation |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should show perspective switcher on kube 1.2 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Create page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Info page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Search page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to User page |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should properly format apps dropdown |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Applications page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Clusters page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to GRC page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Home page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to KUI |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Overview page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to credentials page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page validate links on Welcome page |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Create Pod policy issue2444-1625498936-pod-policy from YAML, expecting a compliance |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Delete Pod policy issue2444-1625498936-pod-policy |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Check Specifications CertificatePolicy,EtcdEncryption |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Category PR.DS Data Security has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Controls PR.DS-1 Data-at-rest,PR.DS-2 Data-in-transit have been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Specifications CertificatePolicy,EtcdEncryption are selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Standard NIST-CSF has been pre-selected |
| :x: | failed | RHACM4K-1695: Search - verify managed cluster info in the search page [P1][Sev1][observability-usa] Search - verify managed cluster info in the search page. |
| :x: | failed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind application on specific namespace. |
| :x: | failed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod and namespace open-cluster-management. |
| :x: | failed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod on specific cluster. |
| :x: | failed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:certpolicycontroller. |
| :x: | failed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:iampolicycontroller. |
| :x: | failed | RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Verify a deleted pod is recreated. |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by active |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apigroup |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apiversion |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by architecture |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by available |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by capacity |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by claimRef |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cluster |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by clusterIP |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by completions |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by consoleURL |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by container |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cpu |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by created |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by current |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by desired |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by hostIP |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by kubernetesVersion |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by lastSchedule |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by memory |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by nodes |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by osImage |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by parallelism |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by podIP |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by port |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by ready |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by reclaimPolicy |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by request |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by restarts |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by startedAt |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by successful |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by suspend |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by type |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by updated |
| :x: | failed | RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by volumeName |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster acm-spoke-48 violations |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1625498936 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1625498936 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1625498936 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1625498936 using the form |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1625498936 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Edit policy test-pod-policy-1625498936 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1625498936 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1625498936 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1625498936 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1625498936 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1625498936 cluster acm-spoke-48 template test-pod-policy-1625498936-nginx-pod |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1625498936 status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster acm-spoke-48 violations |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy t-imp-1625498936 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy t-imp-1625498936 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy t-imp-1625498936 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy t-imp-1625498936 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy t-imp-1625498936 using the form |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy t-imp-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy t-imp-1625498936 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Edit policy t-imp-1625498936 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy t-imp-1625498936 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy t-imp-1625498936 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy t-imp-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1625498936 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1625498936 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1625498936 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1625498936 cluster acm-spoke-48 template t-imp-1625498936-image-vulnerability |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1625498936 cluster acm-spoke-48 template t-imp-1625498936-subscription |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy t-imp-1625498936 status to become available |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Namespace policy to create template ns as duplicatetest |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with default as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with duplicatetest as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Delete created policies |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1625498936 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1625498936 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1625498936 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1625498936 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1625498936 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1625498936 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1625498936 status to become available |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check long but valid policy name pattern |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check that invalid policy name pattern issues an error |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check warning about a policy with a duplicate name |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Cleanup: delete previously created policy |
| :x: | failed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
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
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-gatekeeper-1625498936 into YAML editor |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Paste raw YAML of policy policy-limitrange-1625498936 into YAML editor |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-gatekeeper-1625498936 to an Enforced state and then back to Inform |
| :white_check_mark: | passed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML Set policy-limitrange-1625498936 to an Enforced state and then back to Inform |
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
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy policy-create-credential-1625498936 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy policy-create-subscription-1625498936 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy to-automate-1625498936 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create the credential policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Creates a subscription to install the Ansible operator |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Creates the policy to automate using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-create-credential-1625498936 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-create-subscription-1625498936 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-delete-subscription-1625498936 |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy to-automate-1625498936 |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Prompts the user to install the ansible operator |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Skips install prompt if the ansible operator is installed |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "manual" automation |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "run once" automation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a disabled automation |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verifies successful job history with mock |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-create-credential-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-create-subscription-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-delete-subscription-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy to-automate-1625498936 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-credential-1625498936 status to become available |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-subscription-1625498936 status to become available |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-delete-subscription-1625498936 status to become available |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for to-automate-1625498936 status to become available |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal verifies sidebar credentials after creation |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal verifies sidebar credentials not existing |
| :x: | failed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in kube-system on imported cluster. |
| :x: | failed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm on hub cluster. |
| :x: | failed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on hub cluster. |
| :x: | failed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on imported cluster. |
| :x: | failed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on hub cluster. |
| :x: | failed | RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on imported cluster. |
| :x: | failed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect. |
| :x: | failed | Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present. |
| :x: | failed | Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod. |
| :white_check_mark: | passed | [P0][sev1][kui]Visual Web Terminal: Verify user path for rbash |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify KUI multiple tabs |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify kubectl |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify oc |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify subctl |
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
| :x: | failed | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


---

### Failed Test Details

#### :x:  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:538
Expected
    <string>: Error from server (NotFound): namespaces "gatekeeper-system" not found
    
to contain substring
    <string>: namespace "gatekeeper-system" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:554
```

#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:419
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:433
```

#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:403
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:417
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:491
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.7.4.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:494 +0x245
reflect.Value.call(0x135fb00, 0x15eb498, 0x13, 0x1543f68, 0x4, 0xc0006df0e0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eb498, 0x13, 0xc0006df0e0, 0x0, 0x0, 0x7a46c4e12be9, 0xc0005612c8, 0x7a46c4e12be9)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000485380, 0xc0005612c0, 0x2216b00, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000485380, 0x16efd80, 0xc0004af7c0, 0x414301, 0x0, 0x0, 0x0, 0xc0004af7c0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000485380, 0x16efd80, 0xc0004af7c0, 0x0, 0x0, 0x0, 0x16e5740)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:495 +0x124
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000332f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000332f00, 0x15eade8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:480
Timed out after 60.124s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:485
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:354
Timed out after 240.002s.
Expected
    <string>: Error from server (NotFound): customresourcedefinitions.apiextensions.k8s.io "assign.mutations.gatekeeper.sh" not found
    
to contain substring
    <string>: CREATED AT
    assign.mutations.gatekeeper.sh
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:358
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:376
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.4.6.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:379 +0x245
reflect.Value.call(0x135fb00, 0x15eb3f0, 0x13, 0x1543f68, 0x4, 0xc0006ef0b0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eb3f0, 0x13, 0xc0006ef0b0, 0x0, 0x0, 0x79efa3228bda, 0xc0004f95e8, 0x79efa3228bda)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000452880, 0xc0004f95e0, 0x2216b00, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000452880, 0x16efd80, 0xc000201a30, 0x414301, 0x0, 0x0, 0x0, 0xc000201a30)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000452880, 0x16efd80, 0xc000201a30, 0x0, 0x0, 0x0, 0x16e5740)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func4.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:380 +0x147
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000332f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000332f00, 0x15eade8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:365
Timed out after 60.751s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:370
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:338
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:352
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:439
Timed out after 180.636s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:446
```

#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:272
Timed out after 180.000s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:277
```

#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:243
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:257
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:167
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:173
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:182
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:188
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:136
Timed out after 240.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:142
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:156
Timed out after 60.000s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:161
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:196
Timed out after 180.019s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:210
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-git-ansible content from the single application topology - git: ui-git-ansible

```
AssertionError: expected 0 to be at least 3
    at validateTopology (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:622:64)
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  Verify application ui-obj content from the single application topology - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: Expected to find content: '1 Remote, 1 Local' within the element: <div.pf-l-grid__item> but never did.
    at validateTopology (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:613:15)
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/03-validate-ui-single-app.spec.js:123:45)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for advanced configuration tables Verify application ui-obj channel, subscription, placement rule info from the advanced configuration tables - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote'
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/01-validate-ui-advanced-table.spec.js:1494:107)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git info from applications table - git: ui-git

```
AssertionError: Timed out retrying after 4000ms: expected 'https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/search' to include 'multicloud/search?filters={%22textsearch%22:%22name%3Aui-git%20namespace%3Aui-git-ns%20kind%3Aapplication%20apigroup%3Aapp.k8s.io%22}'
    at validateAppTableMenu (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:649:12)
    at validateResourceTable (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:748:5)
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:117:50)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-git-ansible info from applications table - git: ui-git-ansible

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include 'Local'
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application Validation Test for applications table Verify application ui-obj info from applications table - objectstore: ui-obj

```
AssertionError: Timed out retrying after 4000ms: expected 'None' to include '1 Remote, 1 Local'
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02-validate/02-validate-ui-app-table.spec.js:715:133)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should properly format apps dropdown

```
CypressError: Timed out retrying after 30050ms: `cy.click()` failed because this element is detached from the DOM.

`<nav hidden="" data-test="app-dropdown" data-quickstart-id="qs-masthead-appmenu" aria-label="app-menu" class="pf-c-app-launcher pf-m-align-right co-app-launcher co-app-menu" data-ouia-component-type="PF4/ApplicationLauncher" data-ouia-safe="true" style="vertical-align: 0.125em;">...</nav>`

Cypress requires elements be attached in the DOM to interact with them.

The previous command that ran was:

  > `cy.get()`

This DOM element likely became detached somewhere between the previous and current command.

Common situations why this happens:
  - Your JS framework re-rendered asynchronously
  - Your app code reacted to an event firing and removed the element

You typically need to re-query for the element or add 'guards' which delay Cypress from running new commands.

https://on.cypress.io/element-has-detached-from-dom
    at $Cy.ensureAttached (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:142457:24)
    at runAllChecks (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131064:12)
    at retryActionability (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131141:16)
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147263:21)
    at whenStable (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147301:12)
    at https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:146793:16
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8915:18)
    at Promise._fulfill (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8859:18)
    at https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10473:46
From Your Spec Code:
    at Object.openAppsNoArgo (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/welcomePage_and_Header.spec.js:351:42)
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/tests/welcomePage_and_Header.spec.js:471:34)
```

#### :x: RHACM4K-1695: Search - verify managed cluster info in the search page [P1][Sev1][observability-usa] Search - verify managed cluster info in the search page.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind application on specific namespace.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod and namespace open-cluster-management.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind pod on specific cluster.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:certpolicycontroller.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Search kind:iampolicycontroller.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1696: Search - Verify search result with common filter and conditions [P2][Sev2][observability-usa] Verify a deleted pod is recreated.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by active

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apigroup

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by apiversion

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by architecture

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by available

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by capacity

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by claimRef

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cluster

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by clusterIP

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by completions

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by consoleURL

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by container

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by cpu

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by created

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by current

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by desired

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by hostIP

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by kubernetesVersion

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by lastSchedule

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by memory

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by nodes

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by osImage

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by parallelism

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by podIP

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by port

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by ready

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by reclaimPolicy

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by request

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by restarts

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by startedAt

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by successful

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by suspend

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by type

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by updated

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-1709: Search - Search using filters [P2][Sev2][observability-usa] should filter by volumeName

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:361
Timed out after 120.000s.
Expected
    <int>: 1
to equal
    <int>: 3
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:380
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:91
Timed out after 120.000s.
Expected
    <int>: 1
to equal
    <int>: 3
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:113
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:211
Timed out after 60.000s.
Expected
    <string>: Pending
to equal
    <string>: Running
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:229
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:231
Timed out after 120.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:237
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:338
Timed out after 240.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:343
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:345
Test Panicked
/usr/lib/golang/src/runtime/iface.go:261

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.7.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:349 +0x149
reflect.Value.call(0x135fb00, 0x15eaf38, 0x13, 0x1543f68, 0x4, 0xc0006170e0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eaf38, 0x13, 0xc0006170e0, 0x0, 0x0, 0x76f9a1cddc82, 0xc00008d5e8, 0x76f9a1cddc82)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0004532c0, 0xc00008d5e0, 0x2216b00, 0x203000, 0xc00003c120)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0004532c0, 0x16efd80, 0xc00017a960, 0x414301, 0x0, 0x0, 0x0, 0xc00017a960)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0004532c0, 0x16efd80, 0xc00017a960, 0x0, 0x0, 0x0, 0x16e5740)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.7()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:350 +0x14e
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000332f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000332f00, 0x15eade8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:352
Test Panicked
/usr/lib/golang/src/runtime/iface.go:261

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.8.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:356 +0x149
reflect.Value.call(0x135fb00, 0x15eaf48, 0x13, 0x1543f68, 0x4, 0xc0006170e0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eaf48, 0x13, 0xc0006170e0, 0x0, 0x0, 0x76f9a521fc63, 0xc00008dd18, 0x76f9a521fc63)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0004536c0, 0xc00008dd10, 0x2216b00, 0x203000, 0xc00003c120)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0004536c0, 0x16efd80, 0xc00006eed0, 0x414301, 0x0, 0x0, 0x0, 0xc00006eed0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0004536c0, 0x16efd80, 0xc00006eed0, 0x0, 0x0, 0x0, 0x16e5740)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.8()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:357 +0x14e
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000332f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000332f00, 0x15eade8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:307
Timed out after 120.000s.
Expected
    <nil>: nil
not to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:315
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

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:371
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:385
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:355
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
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
reflect.Value.call(0x135fb00, 0x15eb1b8, 0x13, 0x1543f68, 0x4, 0xc0006290e0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eb1b8, 0x13, 0xc0006290e0, 0x0, 0x0, 0x78a648cba98f, 0xc000561728, 0x78a648cba98f)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0003c65c0, 0xc000561720, 0x2216b00, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0003c65c0, 0x16efd80, 0xc000414d40, 0x414301, 0x0, 0x0, 0x0, 0xc000414d40)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0003c65c0, 0x16efd80, 0xc000414d40, 0x0, 0x0, 0x0, 0x16e5740)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:448 +0x124
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000332f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000332f00, 0x15eade8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:433
Timed out after 60.702s.
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
reflect.Value.call(0x135fb00, 0x15eb110, 0x13, 0x1543f68, 0x4, 0xc00069b0b0, 0x0, 0x0, 0x135fb00, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:476 +0x8c7
reflect.Value.Call(0x135fb00, 0x15eb110, 0x13, 0xc00069b0b0, 0x0, 0x0, 0x784f37d7af7c, 0xc00008c4b8, 0x784f37d7af7c)
	/usr/lib/golang/src/reflect/value.go:337 +0xb9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000485640, 0xc00008c4b0, 0x2216b00, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000485640, 0x16efd80, 0xc0003b8150, 0x414301, 0x0, 0x0, 0x0, 0xc0003b8150)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000485640, 0x16efd80, 0xc0003b8150, 0x0, 0x0, 0x0, 0x16e5740)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:332 +0x147
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc000332f00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xfa
testing.tRunner(0xc000332f00, 0x15eade8)
	/usr/lib/golang/src/testing/testing.go:1123 +0xef
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1168 +0x2b3
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:317
Timed out after 60.313s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:322
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:391
Timed out after 180.000s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:398
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
Timed out after 120.000s.
Expected
    <string>: Pending
to equal
    <string>: Running
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:105
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:108
Timed out after 60.230s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:113
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
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:209
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy to-automate-1625498936

```
CypressError: Timed out retrying after 30050ms: `cy.click()` failed because this element:

`<button aria-label="Actions" id="pf-dropdown-toggle-id-957" class="pf-c-dropdown__toggle pf-m-plain" type="button" aria-expanded="false" aria-haspopup="true">...</button>`

is being covered by another element:

`<div id="pf-modal-part-7" class="pf-c-modal-box__body">...</div>`

Fix this problem, or use {force: true} to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:142591:26)
    at ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130790:8)
    at ensureDescendentsAndScroll (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130797:14)
    at ensureElIsNotCovered (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130931:5)
    at runAllChecks (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131118:52)
    at retryActionability (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131141:16)
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147263:21)
    at whenStable (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147301:12)
    at https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:146793:16
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8915:18)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:12496:24)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Prompts the user to install the ansible operator

```
CypressError: Timed out retrying after 30050ms: `cy.click()` failed because this element:

`<a target="_blank" rel="noreferrer" id="automationButton-to-automate-1625498936-policy-automation" aria-disabled="false" class="pf-c-button pf-m-link" data-ouia-component-type="PF4/Button" data-ouia-safe="true" data-ouia-component-id="OUIA-Generated-Button-link-12" style="margin-left: 0px; padding-left: 0px; font-size: 14px;">...</a>`

is being covered by another element:

`<div id="pf-modal-part-7" class="pf-c-modal-box__body">...</div>`

Fix this problem, or use {force: true} to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:142591:26)
    at ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130790:8)
    at ensureDescendentsAndScroll (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130797:14)
    at ensureElIsNotCovered (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130931:5)
    at runAllChecks (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131118:52)
    at retryActionability (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131141:16)
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147263:21)
    at whenStable (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147301:12)
    at https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:146793:16
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8915:18)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13657:19)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Skips install prompt if the ansible operator is installed

```
CypressError: Timed out retrying after 30050ms: `cy.click()` failed because this element:

`<a target="_blank" rel="noreferrer" id="automationButton-to-automate-1625498936-policy-automation" aria-disabled="false" class="pf-c-button pf-m-link" data-ouia-component-type="PF4/Button" data-ouia-safe="true" data-ouia-component-id="OUIA-Generated-Button-link-24" style="margin-left: 0px; padding-left: 0px; font-size: 14px;">...</a>`

is being covered by another element:

`<div id="pf-modal-part-7" class="pf-c-modal-box__body">...</div>`

Fix this problem, or use {force: true} to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:142591:26)
    at ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130790:8)
    at ensureDescendentsAndScroll (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130797:14)
    at ensureElIsNotCovered (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130931:5)
    at runAllChecks (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131118:52)
    at retryActionability (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131141:16)
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147263:21)
    at whenStable (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147301:12)
    at https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:146793:16
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8915:18)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13657:19)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "manual" automation

```
CypressError: Timed out retrying after 120050ms: `cy.click()` failed because this element:

`<a target="_blank" rel="noreferrer" id="automationButton-to-automate-1625498936-policy-automation" aria-disabled="false" class="pf-c-button pf-m-link" data-ouia-component-type="PF4/Button" data-ouia-safe="true" data-ouia-component-id="OUIA-Generated-Button-link-12" style="margin-left: 0px; padding-left: 0px; font-size: 14px;">...</a>`

is being covered by another element:

`<div id="pf-modal-part-7" class="pf-c-modal-box__body">...</div>`

Fix this problem, or use {force: true} to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:142591:26)
    at ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130790:8)
    at ensureDescendentsAndScroll (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130797:14)
    at ensureElIsNotCovered (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130931:5)
    at runAllChecks (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131118:52)
    at retryActionability (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131141:16)
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147263:21)
    at whenStable (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147301:12)
    at https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:146793:16
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8915:18)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13700:19)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "run once" automation

```
AssertionError: Timed out retrying after 120000ms: Expected to find element: `svg[fill="#c9190b"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13811:37)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verifies successful job history with mock

```
CypressError: Timed out retrying after 30050ms: `cy.click()` failed because this element:

`<a target="_blank" rel="noreferrer" id="automationButton-to-automate-1625498936-policy-automation" aria-disabled="false" class="pf-c-button pf-m-link" data-ouia-component-type="PF4/Button" data-ouia-safe="true" data-ouia-component-id="OUIA-Generated-Button-link-12" style="margin-left: 0px; padding-left: 0px; font-size: 14px;">...</a>`

is being covered by another element:

`<div id="pf-modal-part-7" class="pf-c-modal-box__body">...</div>`

Fix this problem, or use {force: true} to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:142591:26)
    at ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130790:8)
    at ensureDescendentsAndScroll (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130797:14)
    at ensureElIsNotCovered (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130931:5)
    at runAllChecks (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131118:52)
    at retryActionability (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131141:16)
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147263:21)
    at whenStable (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147301:12)
    at https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:146793:16
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8915:18)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13764:19)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal verifies sidebar credentials not existing

```
CypressError: Timed out retrying after 30050ms: `cy.click()` failed because this element:

`<a target="_blank" rel="noreferrer" id="automationButton-to-automate-1625498936-policy-automation" aria-disabled="false" class="pf-c-button pf-m-link" data-ouia-component-type="PF4/Button" data-ouia-safe="true" data-ouia-component-id="OUIA-Generated-Button-link-12" style="margin-left: 0px; padding-left: 0px; font-size: 14px;">...</a>`

is being covered by another element:

`<div id="pf-modal-part-7" class="pf-c-modal-box__body">...</div>`

Fix this problem, or use {force: true} to disable error checking.

https://on.cypress.io/element-cannot-be-interacted-with
    at $Cy.ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:142591:26)
    at ensureDescendents (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130790:8)
    at ensureDescendentsAndScroll (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130797:14)
    at ensureElIsNotCovered (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:130931:5)
    at runAllChecks (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131118:52)
    at retryActionability (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:131141:16)
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147263:21)
    at whenStable (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:147301:12)
    at https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:146793:16
    at tryCatcher (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/runner/cypress_runner.js:8915:18)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acm-hub-46.mon01.ibm-power-acm.com/__cypress/tests?p=tests/cypress/support/index.js:13616:19)
```

#### :x: RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in kube-system on imported cluster.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm on hub cluster.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on hub cluster.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent on imported cluster.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on hub cluster.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: RHACM4K-913: Search - common filter and conditions [P3][Sev3][observability-usa] should have expected count of pods in ocm-agent-addon on imported cluster.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is incorrect.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: Search API: Verify access: [P1][Sev1][observability-usa] should get 401 if authorization header is not present.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
```

#### :x: Search API: Verify access: [P1][Sev1][observability-usa] should return results when searching for kind:pod.

```
Error: Client network socket disconnected before secure TLS connection was established
    at connResetException (internal/errors.js:607:14)
    at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
    at TLSSocket.emit (events.js:327:22)
    at endReadableNT (internal/streams/readable.js:1327:12)
    at processTicksAndRejections (internal/process/task_queues.js:80:21)
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

#### :x: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate

```
/opt/e2e/client/canary/e2e_canary_git_custom_cert_test.go:10
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_git_custom_cert_test.go:12
```

