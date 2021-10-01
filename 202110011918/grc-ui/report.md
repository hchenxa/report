# :warning: Had some failures when running regression on cluster ocp-rosa-4 with test snapshot 2.4.0-SNAPSHOT-2021-09-30-03-17-33 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/278/


ACM Version: v2.4.0

Hub Cluster Version: 4.8.11

Hub Cluster: https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com

Managed Cluster Version: v1.21.1+9807387

Managed Cluster: https://console-openshift-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110011918/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-certificate-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-issuer-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-certificate-1633116084 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1633116084 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-certificate-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-issuer-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1633116084 status to become available |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1633116084 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1633116084 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1633116084 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1633116084 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1633116084 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1633116084 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1633116084 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1633116084 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1633116084 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1633116084 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1633116084 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1633116084 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1633116084 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1633116084 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1633116084 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1633116084 status becomes available |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1633116084 is not present |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Delete created policy policy-certificatepolicy-rhacm4k-1205-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1633116084 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1633116084 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1633116084 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1633116084 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Check created policy policy-certificatepolicy-1633116084 is not present |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Check enabled policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Create certificate policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Delete created policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Edit policy policy-certificatepolicy-1633116084 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Validate disable of the policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Validate enable of the policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Validate violations/status of created policy policy-certificatepolicy-1633116084 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Validate violations/status of created policy policy-certificatepolicy-1633116084 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Verify all information about the created certificate policy policy-certificatepolicy-1633116084 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance on local-cluster Wait for certificate policy policy-certificatepolicy-1633116084 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Check that policy test-issue3677-cert-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Create a customized policy |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Delete policy test-issue3677-cert-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Deleted policy test-issue3677-cert-policy-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Prefill a new policy test-issue3677-cert-policy-1633116084 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Replace namespaceSelector value with "no-such-namespace" |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1633116084 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Wait for policy test-issue3677-cert-policy-1633116084 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1633116084-create-cert-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1633116084-create-cert-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1633116084-create-issuer-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1633116084-create-issuer-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1633116084-create-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1633116084-create-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1633116084-delete-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1633116084-delete-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete cert policy issue7520-1633116084-cert-policy |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1633116084-create-cert-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1633116084-create-cert-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1633116084-create-issuer-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1633116084-create-issuer-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1633116084-create-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1633116084-create-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1633116084-delete-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1633116084-delete-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1633116084-create-cert-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1633116084-create-cert-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1633116084-create-issuer-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1633116084-create-issuer-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1633116084-create-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1633116084-create-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1633116084-delete-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1633116084-delete-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1633116084-create-cert-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1633116084-create-cert-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1633116084-create-issuer-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1633116084-create-issuer-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1633116084-create-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1633116084-create-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1633116084-delete-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1633116084-delete-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show compliance again |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected create certPolicy issue7520-1633116084-cert-policy, expecting a compliance |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1633116084 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Edit policy test-iam-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1633116084 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1633116084 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1633116084 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1633116084 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1633116084 cluster local-cluster template test-iam-policy-1633116084-limit-clusteradmin |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1633116084 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1633116084 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Edit policy test-pod-security-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1633116084 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1633116084 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1633116084 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1633116084 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1633116084 cluster local-cluster template test-pod-security-policy-1633116084-restricted-psp |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1633116084 status to become available |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1633116084 using the form" |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1633116084 using the form" |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1633116084 using the form" |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1633116084 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Edit policy test-namespace-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1633116084 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1633116084 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1633116084 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1633116084 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1633116084 cluster local-cluster template test-namespace-policy-1633116084-prod-ns |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1633116084 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1633116084 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Edit policy test-limitrange-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1633116084 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1633116084 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1633116084 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1633116084 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1633116084 cluster local-cluster template test-limitrange-policy-1633116084-container-mem-limit-range |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1633116084 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1633116084 is not present |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create certificate policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Delete created policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1633116084 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1633116084 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1633116084 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1633116084 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1633116084 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Wait for certificate policy policy-certificatepolicy-1633116084 status to become available |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon "Govern risk" page can be launched. |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-certificate-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-issuer-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-certificate-1633116084 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-issuer-1633116084 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-certificate-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-issuer-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1633116084 status to become available |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1633116084 status to become available |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Check that policy policy-create-credential-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Check that policy policy-create-subscription-1633116084 is present in the policy listing |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Create a subscription to install the Ansible operator |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Create the credential policy using the YAML |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Delete policy policy-create-credential-1633116084 |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Delete policy policy-create-subscription-1633116084 |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Enforce policy-create-credential-1633116084 |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Wait for policy-create-credential-1633116084 status to be Compliant |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Wait for policy-create-credential-1633116084 status to become NonCompliant |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Wait for policy-create-subscription-1633116084 status to become available |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: verifies sidebar credentials after creation |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-edit-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-group-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-view-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-edit-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-group-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-view-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-edit-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-group-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-view-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-cluster-admin-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-cluster-admin-ns |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-edit-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-group-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-edit-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-group-cluster |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-view-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Create policies used for the testing |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-admin-cluster user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-cluster-admin-cluster user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-cluster-admin-ns user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-edit-cluster user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-group-cluster user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-view-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-admin-cluster user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-cluster-admin-cluster user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-cluster-admin-ns user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-edit-cluster user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-group-cluster user |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-view-cluster user |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Verify that CYPRESS_RBAC_PASS environment variable is defined |
| :x: | failed | @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check All policies listing page content as e2e-cmgr-admin-cluster |
| :x: | failed | @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-cmgr-admin-cluster |
| :x: | failed | @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check policy creation as e2e-cmgr-admin-cluster |
| :x: | failed | @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check policy removal as e2e-cmgr-admin-cluster |
| :x: | failed | @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-cmgr-admin-cluster |
| :white_check_mark: | passed | @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-cmgr-admin-cluster |
| :x: | failed | @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Login e2e-cmgr-admin-cluster user |
| :x: | failed | @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Logout e2e-cmgr-admin-cluster user |
| :x: | failed | @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check All policies listing page content as e2e-admin-ns |
| :x: | failed | @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-admin-ns |
| :x: | failed | @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check policy creation as e2e-admin-ns |
| :x: | failed | @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check policy removal as e2e-admin-ns |
| :x: | failed | @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-admin-ns |
| :white_check_mark: | passed | @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-admin-ns |
| :x: | failed | @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Login e2e-admin-ns user |
| :x: | failed | @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Logout e2e-admin-ns user |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check All policies listing page content as e2e-group-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check All policies listing page content as e2e-view-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-group-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-view-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check policy creation as e2e-group-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check policy creation as e2e-view-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-group-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-view-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-group-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-view-ns |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Login e2e-group-ns user |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Login e2e-view-ns user |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Logout e2e-group-ns user |
| :x: | failed | @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Logout e2e-view-ns user |
| :x: | failed | @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Check All policies listing page content as e2e-edit-ns |
| :x: | failed | @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-edit-ns |
| :x: | failed | @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Check policy creation as e2e-edit-ns |
| :x: | failed | @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-edit-ns |
| :white_check_mark: | passed | @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-edit-ns |
| :x: | failed | @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Login e2e-edit-ns user |
| :x: | failed | @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Logout e2e-edit-ns user |
| :x: | failed | @rbac clean up rbac related Ansible cleanup: Create the clean up policy using the YAML |
| :x: | failed | @rbac clean up rbac related Ansible cleanup: Delete policy policy-delete-subscription-1633116084 |
| :x: | failed | @rbac clean up rbac related Ansible cleanup: Enforce policy-delete-subscription-1633116084 |
| :white_check_mark: | passed | @rbac clean up rbac related Ansible cleanup: Verify that policy policy-delete-subscription-1633116084 is not present in the policy listing |
| :x: | failed | @rbac clean up rbac related Ansible cleanup: Wait for policy-delete-subscription-1633116084 status to be Compliant |
| :x: | failed | @rbac clean up rbac related Ansible cleanup: Wait for policy-delete-subscription-1633116084 status to become NonCompliant |
| :x: | failed | @rbac clean up rbac related Delete test policies |
| :x: | failed | @rbac clean up rbac related Login again as kubeadmin |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1633116084 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1633116084 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1633116084 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1633116084 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1633116084 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1633116084 status to become available |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load" |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Check created policy policy-check-localcluster-1633116084 is not present |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Check disabled policy |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Check enabled policy policy-check-localcluster-1633116084 |
| :x: | failed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Check remediated the violations |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Check that policy policy-check-localcluster-1633116084 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Creates the policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Delete created policy policy-check-localcluster-1633116084 |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Edit policy policy-check-localcluster-1633116084 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Validate disable of the policy policy-check-localcluster-1633116084 |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Validate enable of the policy policy-check-localcluster-1633116084 |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Validate violations/status of created policy policy-check-localcluster-1633116084 on the detailed policy page |
| :x: | failed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Validate violations/status of created policy policy-check-localcluster-1633116084 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Wait for policy-check-localcluster-1633116084 status to become available |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Create Pod policy issue2444-1633116084-pod-policy from YAML, expecting a compliance |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Delete Pod policy issue2444-1633116084-pod-policy |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Check Specifications CertificatePolicy,EtcdEncryption |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Category PR.DS Data Security has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Controls PR.DS-1 Data-at-rest,PR.DS-2 Data-in-transit have been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Specifications CertificatePolicy,EtcdEncryption are selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Standard NIST-CSF has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1633116084 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1633116084 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1633116084 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1633116084 using the form |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1633116084 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Edit policy test-pod-policy-1633116084 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1633116084 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1633116084 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1633116084 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1633116084 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1633116084 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1633116084 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1633116084 cluster local-cluster template test-pod-policy-1633116084-nginx-pod |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1633116084 status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster local-cluster violations |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy t-imp-1633116084 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy t-imp-1633116084 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy t-imp-1633116084 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy t-imp-1633116084 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy t-imp-1633116084 using the form |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy t-imp-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy t-imp-1633116084 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Edit policy t-imp-1633116084 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy t-imp-1633116084 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy t-imp-1633116084 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy t-imp-1633116084 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1633116084 details at the detailed page |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1633116084 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1633116084 violations at the Status - Templates page |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1633116084 cluster local-cluster template t-imp-1633116084-image-vulnerability |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1633116084 cluster local-cluster template t-imp-1633116084-subscription |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy t-imp-1633116084 status to become available |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Namespace policy to create template ns as duplicatetest |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with default as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with duplicatetest as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Delete created policies |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1633116084 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1633116084 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1633116084 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1633116084 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1633116084 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1633116084 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1633116084 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1633116084 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1633116084 status to become available |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check long but valid policy name pattern |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check that invalid policy name pattern issues an error |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Check warning about a policy with a duplicate name |
| :white_check_mark: | passed | RHACM4K-2349 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy field validations Cleanup: delete previously created policy |
| :white_check_mark: | passed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Check form is updated when whole policy YAML is pasted into YAML editor |
| :white_check_mark: | passed | RHACM4K-2351 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor Individual YAML updates are reflected in a form |
| :x: | failed | RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit" |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for CertificatePolicy specification |
| :white_check_mark: | passed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for ComplianceOperator specification |
| :x: | failed | RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for EtcdEncryption specification |
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
| :x: | failed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1633116084 into YAML editor" |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy policy-create-credential-1633116084 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy policy-create-subscription-1633116084 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy to-automate-1633116084 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create a subscription to install the Ansible operator |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create the credential policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Creates the policy to automate using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-create-credential-1633116084 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-create-subscription-1633116084 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-delete-subscription-1633116084 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy to-automate-1633116084 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Enforce policy-create-credential-1633116084 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Enforce policy-delete-subscription-1633116084 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Prompts the user to install the ansible operator |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Skips install prompt if the ansible operator is installed |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "manual" automation |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "run once" automation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a disabled automation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verifies successful job history with mock |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-create-credential-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-create-subscription-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-delete-subscription-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy to-automate-1633116084 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-credential-1633116084 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-credential-1633116084 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-subscription-1633116084 status to become available |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-delete-subscription-1633116084 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-delete-subscription-1633116084 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for to-automate-1633116084 status to become available |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal verifies sidebar credentials after creation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal verifies sidebar credentials not existing |
| :white_check_mark: | passed | RHACM4K-3471 - cleanup configuration policy Check that policy policy-check-clean-localcluster-1633116084 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - cleanup configuration policy Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - cleanup configuration policy Delete policy policy-check-clean-localcluster-1633116084 |
| :white_check_mark: | passed | RHACM4K-3471 - cleanup configuration policy Verify that policy policy-check-clean-localcluster-1633116084 is not present in the policy listing |
| :x: | failed | RHACM4K-3471 - cleanup configuration policy Wait for policy-check-clean-localcluster-1633116084 status to become available |


---

### Failed Test Details

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1633116084 using the form"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1633116084 using the form"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1633116084 using the form"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-cluster-admin-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-edit-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-group-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check All policies listing page content as e2e-view-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-edit-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-group-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-view-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `button[aria-label="namespace"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4530:10)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `button[aria-label="namespace"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4530:10)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-cluster-admin-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `button[aria-label="namespace"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4530:10)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-edit-cluster

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=30027fe350cecb172f7505df012cad88%3A%2Fmulticloud%2Fpolicies%2Fcreate' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4555:16)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-group-cluster

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=4479d8dc7949834de5858654cc432a77%3A%2Fmulticloud%2Fpolicies%2Fcreate' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4555:16)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy creation as e2e-view-cluster

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=1430e31b37042573c021573df475fdfe%3A%2Fmulticloud%2Fpolicies%2Fcreate' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4555:16)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: expected '/oauth/authorize' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11804:27)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: expected '/oauth/authorize' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11804:27)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check policy removal as e2e-cluster-admin-ns

```
AssertionError: Timed out retrying after 30000ms: expected '/oauth/authorize' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11804:27)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-cluster-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-cluster-admin-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-edit-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-group-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-view-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-group-cluster

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=c296b69f38deaf5cb7b1d3b0fa5272ca%3A%2Fmulticloud%2Fpolicies' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4517:20)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-view-cluster

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=09a7332c43e620a5c0895e7a33db5d04%3A%2Fmulticloud%2Fpolicies' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4517:20)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-admin-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-cluster-admin-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-cluster-admin-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-edit-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-group-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Login e2e-view-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-admin-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-cluster-admin-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-cluster-admin-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-edit-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-group-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout e2e-view-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check All policies listing page content as e2e-cmgr-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-cmgr-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check policy creation as e2e-cmgr-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `button[aria-label="namespace"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4530:10)
```

#### :x: @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check policy removal as e2e-cmgr-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: expected '/oauth/authorize' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11804:27)
```

#### :x: @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-cmgr-admin-cluster

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Login e2e-cmgr-admin-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-734 - GRC UI: [P1][Sev1][policy-grc] As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy Logout e2e-cmgr-admin-cluster user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check All policies listing page content as e2e-admin-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-admin-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check policy creation as e2e-admin-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `button[aria-label="namespace"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4530:10)
```

#### :x: @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check policy removal as e2e-admin-ns

```
AssertionError: Timed out retrying after 30000ms: expected '/oauth/authorize' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11804:27)
```

#### :x: @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-admin-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Login e2e-admin-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-956 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default admin role to check policy Logout e2e-admin-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check All policies listing page content as e2e-group-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check All policies listing page content as e2e-view-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-group-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-view-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check policy creation as e2e-group-ns

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=05fdec68f0c4855ae93443af3942c366%3A%2Fmulticloud%2Fpolicies%2Fcreate' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4555:16)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check policy creation as e2e-view-ns

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=8e6ad5a6d16727028bfb8629fccd0f6e%3A%2Fmulticloud%2Fpolicies%2Fcreate' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4555:16)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-group-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-view-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-group-ns

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=88bdfef4b316118fae102c45685d7683%3A%2Fmulticloud%2Fpolicies' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4517:20)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Check test-1633116084-e2e-rbac-test-1 policy edit page as e2e-view-ns

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=0b725ed82bdc497fe308fe4e2e246565%3A%2Fmulticloud%2Fpolicies' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4517:20)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Login e2e-group-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Login e2e-view-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Logout e2e-group-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-957 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default view role to check policy Logout e2e-view-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Check All policies listing page content as e2e-edit-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `#create-policy`, but never found it.
    at action_checkPolicyListingPageUserPermissions (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13638:28)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12004:59)
```

#### :x: @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Check detailed test-1633116084-e2e-rbac-test-1 policy page as e2e-edit-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Check policy creation as e2e-edit-ns

```
AssertionError: Timed out retrying after 30000ms: expected 'https://oauth-openshift.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/oauth/authorize?approval_prompt=force&client_id=multicloudingress&redirect_uri=https%3A%2F%2Fmulticloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com%2Foauth%2Fcallback&response_type=code&scope=user%3Afull&state=9552020c2bb3fc4cff82ee237cf38e08%3A%2Fmulticloud%2Fpolicies%2Fcreate' to match /\/multicloud\/policies\/all[?]?/
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4555:16)
```

#### :x: @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Check test-1633116084-e2e-rbac-test-1 policy Clusters page as e2e-edit-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RBAC.spec.js:4500:10)
```

#### :x: @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Login e2e-edit-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: @rbac RHACM4K-958 - GRC UI: [P1][Sev1][policy-grc] As an user with namespace-role-binding of default edit role to check policy Logout e2e-edit-ns user

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-app-launcher.pf-m-align-right.co-app-launcher.co-user-menu`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11695:6)
```

#### :x: @rbac clean up rbac related Ansible cleanup: Create the clean up policy using the YAML

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `textarea.inputarea`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11731:6)
```

#### :x: @rbac clean up rbac related Ansible cleanup: Delete policy policy-delete-subscription-1633116084

```
AssertionError: Timed out retrying after 30000ms: expected '/oauth/authorize' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11804:27)
```

#### :x: @rbac clean up rbac related Ansible cleanup: Enforce policy-delete-subscription-1633116084

```
AssertionError: Timed out retrying after 30000ms: expected '/oauth/authorize' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11804:27)
```

#### :x: @rbac clean up rbac related Ansible cleanup: Wait for policy-delete-subscription-1633116084 status to be Compliant

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac clean up rbac related Ansible cleanup: Wait for policy-delete-subscription-1633116084 status to become NonCompliant

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `div.page-content-container`, but never found it.
    at action_doTableSearch (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13120:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11992:49)
```

#### :x: @rbac clean up rbac related Delete test policies

```
AssertionError: Timed out retrying after 30000ms: expected '/oauth/authorize' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11804:27)
```

#### :x: @rbac clean up rbac related Login again as kubeadmin

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Check remediated the violations

```
AssertionError: Timed out retrying after 30000ms: expected '<svg>' to have attribute 'fill' with the value '#3e8635', but the value was '#c9190b'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:12508:42)
```

#### :x: RHACM4K-1568 - Test configuration policy governance in a hub-self-imported managed cluster Validate violations/status of created policy policy-check-localcluster-1633116084 on the policy status/history page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `.pf-c-page__main-nav .pf-c-nav__link`, but never found it.
    at verifyPolicyInPolicyStatus (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Configuration_policy_on_localcluster.spec.js:5393:6)
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Configuration_policy_on_localcluster.spec.js:6507:45)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1633116084 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/NonCompliant; violation - couldn't find mapping resource with kind ImageManifestVuln, please check if you have CRD deployed/' within the element: <td.pf-m-break-word> but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13200:30)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1633116084 cluster local-cluster template t-imp-1633116084-image-vulnerability

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/violation - couldn't find mapping resource with kind ImageManifestVuln, please check if you have CRD deployed/' within the element: [ <td>, 4 more... ] but never did.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13473:20)
```

#### :x: RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: RHACM4K-2357 - GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates Verify YAML template for EtcdEncryption specification

```
AssertionError: Editor content should match YAML template: expected 'apiVersion: policy.open-cluster-management.io/v1\nkind: Policy\nmetadata:\n  name: etcdencryption\n  namespace: default\n  annotations:\n    policy.open-cluster-management.io/standards: NIST-CSF\n    policy.open-cluster-management.io/categories: PR.DS Data Security\n    policy.open-cluster-management.io/controls: PR.DS-1 Data-at-rest\nspec:\n  remediationAction: inform\n  disabled: false\n  policy-templates:\n    - objectDefinition:\n        apiVersion: policy.open-cluster-management.io/v1\n        kind: ConfigurationPolicy\n        metadata:\n          name: etcdencryption-etcd-encryption\n        spec:\n          remediationAction: inform\n          severity: medium\n          namespaceSelector:\n            exclude:\n              - kube-*\n            include:\n              - default\n          object-templates:\n            - complianceType: musthave\n              objectDefinition:\n                apiVersion: config.openshift.io/v1\n                kind: APIServer\n                metadata:\n                  name: cluster\n                spec:\n                  encryption:\n                    type: aescbc\n---\napiVersion: policy.open-cluster-management.io/v1\nkind: PlacementBinding\nmetadata:\n  name: binding-etcdencryption\n  namespace: default\nplacementRef:\n  name: placement-etcdencryption\n  kind: PlacementRule\n  apiGroup: apps.open-cluster-management.io\nsubjects:\n  - name: etcdencryption\n    kind: Policy\n    apiGroup: policy.open-cluster-management.io\n---\napiVersion: apps.open-cluster-management.io/v1\nkind: PlacementRule\nmetadata:\n  name: placement-etcdencryption\n  namespace: default\nspec:\n  clusterConditions:\n    - status: \'True\'\n      type: ManagedClusterConditionAvailable\n  clusterSelector:\n    matchExpressions:\n      - key: local-cluster\n        operator: In\n        values:\n          - \'true\'\n' to equal 'apiVersion: policy.open-cluster-management.io/v1\nkind: Policy\nmetadata:\n  name: etcdencryption\n  namespace: default\n  annotations:\n    policy.open-cluster-management.io/standards: NIST-CSF\n    policy.open-cluster-management.io/categories: PR.DS Data Security\n    policy.open-cluster-management.io/controls: PR.DS-1 Data-at-rest\nspec:\n  remediationAction: inform\n  disabled: false\n  policy-templates:\n    - objectDefinition:\n        apiVersion: policy.open-cluster-management.io/v1\n        kind: ConfigurationPolicy\n        metadata:\n          name: etcdencryption-etcd-encryption\n        spec:\n          remediationAction: inform\n          severity: med\n          namespaceSelector:\n            exclude:\n              - kube-*\n            include:\n              - default\n          object-templates:\n            - complianceType: musthave\n              objectDefinition:\n                apiVersion: config.openshift.io/v1\n                kind: APIServer\n                metadata:\n                  name: cluster\n                spec:\n                  encryption:\n                    type: aescbc\n---\napiVersion: policy.open-cluster-management.io/v1\nkind: PlacementBinding\nmetadata:\n  name: binding-etcdencryption\n  namespace: default\nplacementRef:\n  name: placement-etcdencryption\n  kind: PlacementRule\n  apiGroup: apps.open-cluster-management.io\nsubjects:\n  - name: etcdencryption\n    kind: Policy\n    apiGroup: policy.open-cluster-management.io\n---\napiVersion: apps.open-cluster-management.io/v1\nkind: PlacementRule\nmetadata:\n  name: placement-etcdencryption\n  namespace: default\nspec:\n  clusterConditions:\n    - status: \'True\'\n      type: ManagedClusterConditionAvailable\n  clusterSelector:\n    matchExpressions:\n      - key: local-cluster\n        operator: In\n        values:\n          - \'true\'\n'
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/policy_YAML_templates_verification.spec.js:4183:16)
```

#### :x: RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1633116084 into YAML editor"

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'grc-e2e-htpasswd' but never did.

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:11612:12)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "manual" automation

```
AssertionError: Timed out retrying after 120000ms: Expected to find element: `.pf-c-empty-state`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13912:35)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "run once" automation

```
AssertionError: Timed out retrying after 120000ms: Expected to find element: `.pf-c-empty-state`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:13912:35)
```

#### :x: RHACM4K-3471 - cleanup configuration policy Wait for policy-check-clean-localcluster-1633116084 status to become available

```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:4924:13)
```

