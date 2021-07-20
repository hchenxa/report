# :warning: Had some failures when running regression on cluster ocp4-az-3 with test snapshot 2.3.0-SNAPSHOT-2021-07-19-17-01-34 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/239/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.13

Hub Cluster: https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.7.3

Managed Cluster: https://console-openshift-console.apps.acmqe-225-23-hive-before-upgrade.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107200915/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-certificate-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Check that policy policy-create-issuer-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-certificate-1626776620 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Delete policy policy-create-issuer-1626776620 |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-certificate-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Verify that policy policy-create-issuer-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-certificate-1626776620 status to become available |
| :white_check_mark: | passed | @extended Cleanup - delete a certificate and an issuer Wait for policy-create-issuer-1626776620 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1626776620 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1626776620 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1626776620 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1626776620 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1626776620 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1626776620 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1626776620 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1626776620 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1626776620 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1626776620 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1626776620 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1626776620 status to become available |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1626776620 |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1626776620 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Check that policy test-issue3677-cert-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Create a customized policy |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Delete policy test-issue3677-cert-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Deleted policy test-issue3677-cert-policy-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Prefill a new policy test-issue3677-cert-policy-1626776620 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Replace namespaceSelector value with "no-such-namespace" |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1626776620 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1648 - GRC UI: [P2][Sev2][policy-grc] CertPolicy with wrong namespace selector Wait for policy test-issue3677-cert-policy-1626776620 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1626776620-create-cert-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1626776620-create-cert-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1626776620-create-issuer-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1626776620-create-issuer-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1626776620-create-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1626776620-create-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1626776620-delete-ns1 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Check that policy issue7520-1626776620-delete-ns2 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete cert policy issue7520-1626776620-cert-policy |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1626776620-create-cert-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1626776620-create-cert-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1626776620-create-issuer-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1626776620-create-issuer-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1626776620-create-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1626776620-create-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1626776620-delete-ns1 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Delete policy issue7520-1626776620-delete-ns2 |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify detailed template/cluster status |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1626776620-create-cert-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1626776620-create-cert-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1626776620-create-issuer-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1626776620-create-issuer-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1626776620-create-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1626776620-create-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1626776620-delete-ns1 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Verify that policy issue7520-1626776620-delete-ns2 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1626776620-create-cert-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1626776620-create-cert-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1626776620-create-issuer-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1626776620-create-issuer-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1626776620-create-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1626776620-create-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1626776620-delete-ns1 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for issue7520-1626776620-delete-ns2 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show compliance again |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected Wait for the cert policy status to show violation |
| :white_check_mark: | passed | @extended RHACM4K-1691 - GRC UI: [P2][Sev2][policy-grc] Certificate policy controller: with wildcard, added or removed namespaces are not detected create certPolicy issue7520-1626776620-cert-policy, expecting a compliance |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check cluster acmqe-225-23-hive-before-upgrade violations |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1626776620 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Edit policy test-iam-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1626776620 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1626776620 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1626776620 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1626776620 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1626776620 cluster acmqe-225-23-hive-before-upgrade template test-iam-policy-1626776620-limit-clusteradmin |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1626776620 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check cluster acmqe-225-23-hive-before-upgrade violations |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1626776620 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Edit policy test-pod-security-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1626776620 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1626776620 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1626776620 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1626776620 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1626776620 cluster acmqe-225-23-hive-before-upgrade template test-pod-security-policy-1626776620-restricted-psp |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1626776620 status to become available |
| :x: | failed | @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1626776620 using the form" |
| :x: | failed | @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1626776620 using the form" |
| :x: | failed | @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1626776620 using the form" |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check cluster acmqe-225-23-hive-before-upgrade violations |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1626776620 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Edit policy test-namespace-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1626776620 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1626776620 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1626776620 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1626776620 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1626776620 cluster acmqe-225-23-hive-before-upgrade template test-namespace-policy-1626776620-prod-ns |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1626776620 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check cluster acmqe-225-23-hive-before-upgrade violations |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1626776620 using the form |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Edit policy test-limitrange-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1626776620 can be deleted in the policy listing |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1626776620 details at the detailed page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1626776620 violations at the Status - Clusters page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1626776620 violations at the Status - Templates page |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1626776620 cluster acmqe-225-23-hive-before-upgrade template test-limitrange-policy-1626776620-container-mem-limit-range |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | @extended RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1626776620 status to become available |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1626776620 is not present |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create certificate policy policy-certificatepolicy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Delete created policy policy-certificatepolicy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1626776620 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1626776620 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1626776620 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1626776620 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended RHACM4K-2294 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Wait for certificate policy policy-certificatepolicy-1626776620 status to become available |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1626776620 status becomes available |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1626776620 is not present |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Delete created policy policy-certificatepolicy-rhacm4k-1205-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1626776620 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1626776620 |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1626776620 on the detailed policy page |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1626776620 on the policy status/history page |
| :white_check_mark: | passed | @extended RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1626776620 on the "Govern and risk" page |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon "Govern risk" page can be launched. |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-certificate-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Check that policy policy-create-issuer-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Create the clean up policy using the YAML |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-certificate-1626776620 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Delete policy policy-create-issuer-1626776620 |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-certificate-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Verify that policy policy-create-issuer-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-certificate-1626776620 status to become available |
| :white_check_mark: | passed | @extended Setup - create a certificate expiring soon Wait for policy-create-issuer-1626776620 status to become available |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests "after each" hook for "Logout" |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Check that policy policy-create-credential-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Check that policy policy-create-subscription-1626776620 is present in the policy listing |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Create a subscription to install the Ansible operator |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Create the credential policy using the YAML |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Delete policy policy-create-credential-1626776620 |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Delete policy policy-create-subscription-1626776620 |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Enforce policy-create-credential-1626776620 |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Enforce policy-create-subscription-1626776620 |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Wait for policy-create-credential-1626776620 status to be Compliant |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Wait for policy-create-credential-1626776620 status to become NonCompliant |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Wait for policy-create-subscription-1626776620 status to be Compliant |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: Wait for policy-create-subscription-1626776620 status to become NonCompliant |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Ansible setup: verifies sidebar credentials after creation |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Create policies used for the testing |
| :x: | failed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout |
| :white_check_mark: | passed | @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Verify that CYPRESS_RBAC_PASS environment variable is defined |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1626776620 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1626776620 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1626776620 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1626776620 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1626776620 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1626776620 status to become available |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load" |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Create Pod policy issue2444-1626776620-pod-policy from YAML, expecting a compliance |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Delete Pod policy issue2444-1626776620-pod-policy |
| :white_check_mark: | passed | RHACM4K-1650 - GRC UI: [P1][Sev1][policy-grc] configurationPoicy controller: not matching namespaceSelector issues a violation Verify the violation is listed on a policy Status page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Check Specifications CertificatePolicy,EtcdEncryption |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Category PR.DS Data Security has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Controls PR.DS-1 Data-at-rest,PR.DS-2 Data-in-transit have been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Specifications CertificatePolicy,EtcdEncryption are selected |
| :white_check_mark: | passed | RHACM4K-1671 - GRC UI: [P2][Sev2][policy-grc] Test create policy multi-select acts correctly Verify Standard NIST-CSF has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check cluster acmqe-225-23-hive-before-upgrade violations |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1626776620 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1626776620 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1626776620 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1626776620 using the form |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1626776620 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Edit policy test-pod-policy-1626776620 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1626776620 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1626776620 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1626776620 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1626776620 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1626776620 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1626776620 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1626776620 cluster acmqe-225-23-hive-before-upgrade template test-pod-policy-1626776620-nginx-pod |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1626776620 status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check cluster acmqe-225-23-hive-before-upgrade violations |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy t-imp-1626776620 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy t-imp-1626776620 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy t-imp-1626776620 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy t-imp-1626776620 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy t-imp-1626776620 using the form |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy t-imp-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy t-imp-1626776620 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Edit policy t-imp-1626776620 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy t-imp-1626776620 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy t-imp-1626776620 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy t-imp-1626776620 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1626776620 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1626776620 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy t-imp-1626776620 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1626776620 cluster acmqe-225-23-hive-before-upgrade template t-imp-1626776620-image-vulnerability |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy t-imp-1626776620 cluster acmqe-225-23-hive-before-upgrade template t-imp-1626776620-subscription |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy t-imp-1626776620 status to become available |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Namespace policy to create template ns as duplicatetest |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with default as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Create Pod policy with duplicatetest as namespace |
| :white_check_mark: | passed | RHACM4K-2342 - GRC UI: [P1][Sev1][policy-grc] Verify create policy with different NS Delete created policies |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-1-1626776620 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-2-1626776620 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Create new policy test-policy-3-1626776620 using the form |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-1-1626776620 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-2-1626776620 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Policy test-policy-3-1626776620 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Categories card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify the content of Standards card |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Verify toggle button does work |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-1-1626776620 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-2-1626776620 status to become available |
| :white_check_mark: | passed | RHACM4K-2343 - [P1][Sev1][policy-grc] All policies page: Verify summary table Wait for policy test-policy-3-1626776620 status to become available |
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
| :x: | failed | RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1626776620 into YAML editor" |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy policy-create-credential-1626776620 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy policy-create-subscription-1626776620 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Check that policy to-automate-1626776620 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create a subscription to install the Ansible operator |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Create the credential policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Creates the policy to automate using the YAML |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-create-credential-1626776620 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-create-subscription-1626776620 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy policy-delete-subscription-1626776620 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Delete policy to-automate-1626776620 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Enforce policy-create-credential-1626776620 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Enforce policy-create-subscription-1626776620 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Enforce policy-delete-subscription-1626776620 |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Prompts the user to install the ansible operator |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Skips install prompt if the ansible operator is installed |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "manual" automation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a "run once" automation |
| :x: | failed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a disabled automation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verifies successful job history with mock |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-create-credential-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-create-subscription-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy policy-delete-subscription-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Verify that policy to-automate-1626776620 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-credential-1626776620 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-credential-1626776620 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-subscription-1626776620 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-create-subscription-1626776620 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-delete-subscription-1626776620 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for policy-delete-subscription-1626776620 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Wait for to-automate-1626776620 status to become available |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal verifies sidebar credentials after creation |
| :white_check_mark: | passed | RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal verifies sidebar credentials not existing |


---

### Failed Test Details

#### :x: @extended RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance "before all" hook for "Create new policy test-role-policy-1626776620 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance "before all" hook for "Create new policy test-role-binding-policy-1626776620 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @extended RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance "before all" hook for "Create new policy test-security-context-constraints-policy-1626776620 using the form"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests "after each" hook for "Logout"

```
CypressError: Cypress command timeout of `30000ms` exceeded.

Because this error occurred during a `after each` hook we are skipping all of the remaining tests.
    at cypressErr (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:156009:18)
    at Object.errByPath (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:156078:10)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:157820:29
```

#### :x: @rbac RHACM4K-2584 - GRC UI: [P1][Sev1][policy-grc] Role Based Access Control tests Logout

```
CypressError: Timed out after waiting `60000ms` for your remote page to load.

Your page did not fire its `load` event within `60000ms`.

You can try increasing the `pageLoadTimeout` value in `/opt/app-root/src/grc-ui/cypress.json` to wait longer.

Browsers will not fire the `load` event until all stylesheets and scripts are done downloading.

When this `load` event occurs, Cypress will continue running commands.
    at timedOutWaitingForPageLoad (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:139487:13)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:139783:16
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5920:41
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11654:31)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] Welcome page "before all" hook for "[P1][Sev1][policy-grc] should load"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2354 - GRC UI: [P1][Sev1][policy-grc] Check existent and non-existent URLs for the policy "before all" hook for "Create policy for the URL visit"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-2509 - GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML "before all" hook for "Paste raw YAML of policy policy-gatekeeper-1626776620 into YAML editor"

```
CypressError: `cy.visit()` failed trying to load:

https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/multicloud/policies

We attempted to make an http request to this URL but the request failed without a response.

We received this error at the network level:

  > Error: Client network socket disconnected before secure TLS connection was established

Common situations why this would fail:
  - you don't have internet access
  - you forgot to run / boot your web server
  - your web server isn't accessible
  - you have weird network configuration settings on your computer

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140471:23
    at visitFailedByErr (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:139830:12)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:140470:11
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8911:18)
    at _drainQueueStep (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5505:12)
    at _drainQueue (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5498:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5514:5)
    at Async.drainQueues (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:5384:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11554:6)

From Node.js Internals:
  Error: Client network socket disconnected before secure TLS connection was established
      at connResetException (internal/errors.js:617:14)
      at TLSSocket.onConnectEnd (_tls_wrap.js:1544:19)
      at TLSSocket.emit (events.js:327:22)
      at endReadableNT (_stream_readable.js:1327:12)
      at processTicksAndRejections (internal/process/task_queues.js:80:21)
  From previous event:
      at ServerE2E._onResolveUrl (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/server-e2e.js:151:41)
      at backendRequest (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:258:44)
  From previous event:
      at Socket.<anonymous> (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/server/lib/socket-base.js:291:46)
      at Socket.emit (events.js:315:20)
      at Socket.emitUntyped (/root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/typed-events.js:69:22)
      at /root/.cache/Cypress/7.7.0/Cypress/resources/app/packages/socket/node_modules/socket.io/dist/socket.js:428:39
      at processTicksAndRejections (internal/process/task_queues.js:75:11)
```

#### :x: RHACM4K-3471 - [P1][Sev1][policy-grc] All policies page: Verify automation modal Successfully can schedule a disabled automation

```
CypressError: Timed out retrying after 180050ms: `cy.click()` failed because this element is detached from the DOM.

`<a aria-disabled="false" class="pf-c-button pf-m-link automationButton" data-ouia-component-type="PF4/Button" data-ouia-safe="true" data-ouia-component-id="OUIA-Generated-Button-link-17">Configure</a>`

Cypress requires elements be attached in the DOM to interact with them.

The previous command that ran was:

  > `cy.get()`

This DOM element likely became detached somewhere between the previous and current command.

Common situations why this happens:
  - Your JS framework re-rendered asynchronously
  - Your app code reacted to an event firing and removed the element

You typically need to re-query for the element or add 'guards' which delay Cypress from running new commands.

https://on.cypress.io/element-has-detached-from-dom
    at $Cy.ensureAttached (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:144001:24)
    at runAllChecks (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:132602:12)
    at retryActionability (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:132679:16)
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Function.Promise.attempt.Promise.try (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8072:29)
    at tryFn (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:148807:21)
    at whenStable (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:148845:12)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:148337:16
    at tryCatcher (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10798:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8733:31)
    at Promise._settlePromise (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8790:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8835:10)
    at Promise._settlePromises (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8915:18)
    at Promise._fulfill (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:8859:18)
    at https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/runner/cypress_runner.js:10473:46
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13790:21)
```

