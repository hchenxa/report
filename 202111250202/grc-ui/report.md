# :warning: Had some failures when running regression on cluster ocp4-acm24-aws-01 with test snapshot 2.4.1-SNAPSHOT-2021-11-23-15-19-17 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/430/


ACM Version: v2.4.1

Hub Cluster Version: 4.8.19

Hub Cluster: https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com

Managed Cluster Version: 4.9.8

Managed Cluster: https://console-openshift-console.apps.hchen-aws-clc.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202111250202/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | Cleanup - delete a certificate and an issuer @bvt @svt Check that policy policy-create-certificate-1637805913 is present in the policy listing |
| :white_check_mark: | passed | Cleanup - delete a certificate and an issuer @bvt @svt Check that policy policy-create-issuer-1637805913 is present in the policy listing |
| :white_check_mark: | passed | Cleanup - delete a certificate and an issuer @bvt @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | Cleanup - delete a certificate and an issuer @bvt @svt Delete policy policy-create-certificate-1637805913 |
| :white_check_mark: | passed | Cleanup - delete a certificate and an issuer @bvt @svt Delete policy policy-create-issuer-1637805913 |
| :white_check_mark: | passed | Cleanup - delete a certificate and an issuer @bvt @svt Verify that policy policy-create-certificate-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | Cleanup - delete a certificate and an issuer @bvt @svt Verify that policy policy-create-issuer-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | Cleanup - delete a certificate and an issuer @bvt @svt Wait for policy-create-certificate-1637805913 status to become available |
| :white_check_mark: | passed | Cleanup - delete a certificate and an issuer @bvt @svt Wait for policy-create-issuer-1637805913 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P1][Sev1][policy-grc] should load |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P1][Sev1][policy-grc] should redirect from base and /multicloud |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should not show perspective switcher on kube >1.2 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should open left navigation |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] should show perspective switcher on kube 1.2 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Create page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Info page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to Search page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should navigate to User page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using header icons - should properly format apps dropdown |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Applications page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Clusters page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to GRC page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Home page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to Overview page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page [P3][Sev3][policy-grc] using left navigation - should navigate to credentials page |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Welcome page validate links on Welcome page |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Certificate policy policy-certificatepolicy-rhacm4k-1205-1637805913 status becomes available |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Check created policy policy-certificatepolicy-rhacm4k-1205-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Check enabled policy policy-certificatepolicy-rhacm4k-1205-1637805913 |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Check violations stay reported but not remediated |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Create policy policy-certificatepolicy-rhacm4k-1205-1637805913 |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Delete created policy policy-certificatepolicy-rhacm4k-1205-1637805913 |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Edit policy policy-certificatepolicy-rhacm4k-1205-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1637805913 |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1637805913 |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-1205: GRC: Test certificate policy governance with enhanced certificate checks for issuers and SAN pattern @bvt @svt Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1637805913 on the "Govern and risk" page |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Check created policy policy-certificatepolicy-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Check enabled policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Check violations stay reported but not remediated |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Create certificate policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Delete created policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Edit policy policy-certificatepolicy-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Validate disable of the policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Validate enable of the policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Validate violations/status of created policy policy-certificatepolicy-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Validate violations/status of created policy policy-certificatepolicy-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Verify all information about the created certificate policy policy-certificatepolicy-1637805913 on the "Govern and risk" page |
| :white_check_mark: | passed | RHACM4K-1567: GRC: CertificatePolicy governance on local-cluster @svt Wait for certificate policy policy-certificatepolicy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Check created policy policy-check-localcluster-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Check enabled policy policy-check-localcluster-1637805913 |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Check remediated the violations |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Check that policy policy-check-clean-localcluster-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Check that policy policy-check-localcluster-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Creates the policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Delete created policy policy-check-localcluster-1637805913 |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Delete policy policy-check-clean-localcluster-1637805913 |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Edit policy policy-check-localcluster-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Validate disable of the policy policy-check-localcluster-1637805913 |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Validate enable of the policy policy-check-localcluster-1637805913 |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Validate violations/status of created policy policy-check-localcluster-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Validate violations/status of created policy policy-check-localcluster-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Verify that policy policy-check-clean-localcluster-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Wait for policy-check-clean-localcluster-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1568: GRC: Test configuration policy governance in a hub-self-imported managed cluster @svt Wait for policy-check-localcluster-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1648: GRC: CertPolicy with wrong namespace selector Check that policy test-issue3677-cert-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1648: GRC: CertPolicy with wrong namespace selector Create a customized policy |
| :white_check_mark: | passed | RHACM4K-1648: GRC: CertPolicy with wrong namespace selector Delete policy test-issue3677-cert-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1648: GRC: CertPolicy with wrong namespace selector Deleted policy test-issue3677-cert-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1648: GRC: CertPolicy with wrong namespace selector Prefill a new policy test-issue3677-cert-policy-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1648: GRC: CertPolicy with wrong namespace selector Replace namespaceSelector value with "no-such-namespace" |
| :white_check_mark: | passed | RHACM4K-1648: GRC: CertPolicy with wrong namespace selector Verify policy test-issue3677-cert-policy-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1648: GRC: CertPolicy with wrong namespace selector Wait for policy test-issue3677-cert-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1650: GRC: configurationPoicy controller: not matching namespaceSelector issues a violation @svt Create Pod policy issue2444-1637805913-pod-policy from YAML, expecting a compliance |
| :white_check_mark: | passed | RHACM4K-1650: GRC: configurationPoicy controller: not matching namespaceSelector issues a violation @svt Delete Pod policy issue2444-1637805913-pod-policy |
| :white_check_mark: | passed | RHACM4K-1650: GRC: configurationPoicy controller: not matching namespaceSelector issues a violation @svt Verify the violation is listed on a policy Status page |
| :white_check_mark: | passed | RHACM4K-1671: GRC: Test create policy multi-select acts correctly @svt Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-1671: GRC: Test create policy multi-select acts correctly @svt Check Specifications CertificatePolicy,EtcdEncryption |
| :white_check_mark: | passed | RHACM4K-1671: GRC: Test create policy multi-select acts correctly @svt Verify Category PR.DS Data Security has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671: GRC: Test create policy multi-select acts correctly @svt Verify Controls PR.DS-1 Data-at-rest,PR.DS-2 Data-in-transit have been pre-selected |
| :white_check_mark: | passed | RHACM4K-1671: GRC: Test create policy multi-select acts correctly @svt Verify Specifications CertificatePolicy,EtcdEncryption are selected |
| :white_check_mark: | passed | RHACM4K-1671: GRC: Test create policy multi-select acts correctly @svt Verify Standard NIST-CSF has been pre-selected |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Check that policy issue7520-1637805913-create-cert-ns1 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Check that policy issue7520-1637805913-create-cert-ns2 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Check that policy issue7520-1637805913-create-issuer-ns1 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Check that policy issue7520-1637805913-create-issuer-ns2 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Check that policy issue7520-1637805913-create-ns1 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Check that policy issue7520-1637805913-create-ns2 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Check that policy issue7520-1637805913-delete-ns1 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Check that policy issue7520-1637805913-delete-ns2 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Delete cert policy issue7520-1637805913-cert-policy |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Delete policy issue7520-1637805913-create-cert-ns1 |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Delete policy issue7520-1637805913-create-cert-ns2 |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Delete policy issue7520-1637805913-create-issuer-ns1 |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Delete policy issue7520-1637805913-create-issuer-ns2 |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Delete policy issue7520-1637805913-create-ns1 |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Delete policy issue7520-1637805913-create-ns2 |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Delete policy issue7520-1637805913-delete-ns1 |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Delete policy issue7520-1637805913-delete-ns2 |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Verify detailed template/cluster status |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Verify that policy issue7520-1637805913-create-cert-ns1 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Verify that policy issue7520-1637805913-create-cert-ns2 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Verify that policy issue7520-1637805913-create-issuer-ns1 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Verify that policy issue7520-1637805913-create-issuer-ns2 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Verify that policy issue7520-1637805913-create-ns1 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Verify that policy issue7520-1637805913-create-ns2 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Verify that policy issue7520-1637805913-delete-ns1 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Verify that policy issue7520-1637805913-delete-ns2 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for issue7520-1637805913-create-cert-ns1 status to become available |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for issue7520-1637805913-create-cert-ns2 status to become available |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for issue7520-1637805913-create-issuer-ns1 status to become available |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for issue7520-1637805913-create-issuer-ns2 status to become available |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for issue7520-1637805913-create-ns1 status to become available |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for issue7520-1637805913-create-ns2 status to become available |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for issue7520-1637805913-delete-ns1 status to become available |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for issue7520-1637805913-delete-ns2 status to become available |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for the cert policy status to show compliance again |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt Wait for the cert policy status to show violation |
| :white_check_mark: | passed | RHACM4K-1691: GRC: Certificate policy controller: with wildcard, added or removed namespaces are not detected @svt create certPolicy issue7520-1637805913-cert-policy, expecting a compliance |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Check cluster hchen-aws-clc violations |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Check disabled policy test-iam-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Check enabled policy test-iam-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Check that enforced policy test-iam-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Check that policy policy-clusterrolebinding-delete-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Check that policy policy-clusterrolebinding-test-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Check that policy test-iam-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Create new policy test-iam-policy-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Delete policy policy-clusterrolebinding-delete-1637805913 |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Delete policy policy-clusterrolebinding-test-1637805913 |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Deleted policy test-iam-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Disable policy test-iam-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Edit policy test-iam-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Enable policy test-iam-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Enforce policy test-iam-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Policy test-iam-policy-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Verify policy test-iam-policy-1637805913 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Verify policy test-iam-policy-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Verify policy test-iam-policy-1637805913 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Verify that policy policy-clusterrolebinding-delete-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Verify that policy policy-clusterrolebinding-test-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Verify the History page for policy test-iam-policy-1637805913 cluster hchen-aws-clc template test-iam-policy-1637805913-limit-clusteradmin |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Wait for policy test-iam-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Wait for policy-clusterrolebinding-delete-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1719: GRC: IamPolicy governance @bvt @svt Wait for policy-clusterrolebinding-test-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Check cluster hchen-aws-clc violations |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Check disabled policy test-pod-security-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Check enabled policy test-pod-security-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Check that enforced policy test-pod-security-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Check that policy pod-security-policy-cleanup-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Check that policy test-pod-security-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Create new policy test-pod-security-policy-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Delete policy pod-security-policy-cleanup-1637805913 |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Deleted policy test-pod-security-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Disable policy test-pod-security-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Edit policy test-pod-security-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Enable policy test-pod-security-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Enforce policy test-pod-security-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Policy test-pod-security-policy-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Verify policy test-pod-security-policy-1637805913 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Verify policy test-pod-security-policy-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Verify policy test-pod-security-policy-1637805913 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Verify that policy pod-security-policy-cleanup-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Verify the History page for policy test-pod-security-policy-1637805913 cluster hchen-aws-clc template test-pod-security-policy-1637805913-restricted-psp |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Wait for pod-security-policy-cleanup-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1720: GRC: PodSecurityPolicy governance @svt Wait for policy test-pod-security-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Check cluster hchen-aws-clc violations |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Check disabled policy test-role-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Check enabled policy test-role-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Check that enforced policy test-role-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Check that policy role-specification-cleanup-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Check that policy test-role-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Create new policy test-role-policy-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Delete policy role-specification-cleanup-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Deleted policy test-role-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Disable policy test-role-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Edit policy test-role-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Enable policy test-role-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Enforce policy test-role-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Policy test-role-policy-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Verify policy test-role-policy-1637805913 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Verify policy test-role-policy-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Verify policy test-role-policy-1637805913 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Verify that policy role-specification-cleanup-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Verify the History page for policy test-role-policy-1637805913 cluster hchen-aws-clc template test-role-policy-1637805913-deployments-role |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Wait for policy test-role-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1721: GRC: RolePolicy governance @svt Wait for role-specification-cleanup-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Check cluster hchen-aws-clc violations |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Check disabled policy test-role-binding-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Check enabled policy test-role-binding-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Check that enforced policy test-role-binding-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Check that policy role-binding-cleanup-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Check that policy test-role-binding-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Create new policy test-role-binding-policy-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Delete policy role-binding-cleanup-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Deleted policy test-role-binding-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Disable policy test-role-binding-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Edit policy test-role-binding-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Enable policy test-role-binding-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Enforce policy test-role-binding-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Policy test-role-binding-policy-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Verify policy test-role-binding-policy-1637805913 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Verify policy test-role-binding-policy-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Verify policy test-role-binding-policy-1637805913 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Verify that policy role-binding-cleanup-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Verify the History page for policy test-role-binding-policy-1637805913 cluster hchen-aws-clc template test-role-binding-policy-1637805913-operatoruser-rolebinding |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Wait for policy test-role-binding-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1722: GRC: RoleBindingPolicy governance @svt Wait for role-binding-cleanup-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Check cluster hchen-aws-clc violations |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Check disabled policy test-security-context-constraints-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Check enabled policy test-security-context-constraints-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Check that enforced policy test-security-context-constraints-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Check that policy scc-cleanup-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Check that policy test-security-context-constraints-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Create new policy test-security-context-constraints-policy-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Delete policy scc-cleanup-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Deleted policy test-security-context-constraints-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Disable policy test-security-context-constraints-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Edit policy test-security-context-constraints-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Enable policy test-security-context-constraints-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Enforce policy test-security-context-constraints-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Policy test-security-context-constraints-policy-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Verify policy test-security-context-constraints-policy-1637805913 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Verify policy test-security-context-constraints-policy-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Verify policy test-security-context-constraints-policy-1637805913 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Verify that policy scc-cleanup-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Verify the History page for policy test-security-context-constraints-policy-1637805913 cluster hchen-aws-clc template test-security-context-constraints-policy-1637805913-restricted-scc |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Wait for policy test-security-context-constraints-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1723: GRC: SecurityContextConstraintsPolicy governance @svt Wait for scc-cleanup-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Check cluster hchen-aws-clc violations |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Check disabled policy test-pod-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Check enabled policy test-pod-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Check that enforced policy test-pod-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Check that policy pod-spec-cleanup-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Check that policy test-pod-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Create new policy test-pod-policy-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Delete policy pod-spec-cleanup-1637805913 |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Deleted policy test-pod-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Disable policy test-pod-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Edit policy test-pod-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Enable policy test-pod-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Enforce policy test-pod-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Policy test-pod-policy-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Verify policy test-pod-policy-1637805913 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Verify policy test-pod-policy-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Verify policy test-pod-policy-1637805913 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Verify that policy pod-spec-cleanup-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Verify the History page for policy test-pod-policy-1637805913 cluster hchen-aws-clc template test-pod-policy-1637805913-nginx-pod |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Wait for pod-spec-cleanup-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1724: GRC: Pod policy governance @svt Wait for policy test-pod-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Check cluster hchen-aws-clc violations |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Check disabled policy test-namespace-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Check enabled policy test-namespace-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Check that enforced policy test-namespace-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Check that policy ns-spec-cleanup-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Check that policy ns-spec-setup-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Check that policy test-namespace-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Create new policy test-namespace-policy-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Delete policy ns-spec-cleanup-1637805913 |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Delete policy ns-spec-setup-1637805913 |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Deleted policy test-namespace-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Disable policy test-namespace-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Edit policy test-namespace-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Enable policy test-namespace-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Enforce policy test-namespace-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Policy test-namespace-policy-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Verify policy test-namespace-policy-1637805913 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Verify policy test-namespace-policy-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Verify policy test-namespace-policy-1637805913 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Verify that policy ns-spec-cleanup-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Verify that policy ns-spec-setup-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Verify the History page for policy test-namespace-policy-1637805913 cluster hchen-aws-clc template test-namespace-policy-1637805913-prod-ns |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Wait for ns-spec-cleanup-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Wait for ns-spec-setup-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1725: GRC: Namespace policy governance @bvt @svt Wait for policy test-namespace-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Check cluster hchen-aws-clc violations |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Check disabled policy test-limitrange-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Check enabled policy test-limitrange-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Check that enforced policy test-limitrange-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Check that policy limitspec-setup-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Check that policy test-limitrange-policy-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Create new policy test-limitrange-policy-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Delete policy limitspec-setup-1637805913 |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Deleted policy test-limitrange-policy-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Disable policy test-limitrange-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Edit policy test-limitrange-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Enable policy test-limitrange-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Enforce policy test-limitrange-policy-1637805913 |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Policy test-limitrange-policy-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Verify policy test-limitrange-policy-1637805913 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Verify policy test-limitrange-policy-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Verify policy test-limitrange-policy-1637805913 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Verify that policy limitspec-setup-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Verify the History page for policy test-limitrange-policy-1637805913 cluster hchen-aws-clc template test-limitrange-policy-1637805913-container-mem-limit-range |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Wait for limitspec-setup-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1726: GRC: LimitRange policy governance @svt Wait for policy test-limitrange-policy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Check cluster hchen-aws-clc violations |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Check disabled policy t-imp-1637805913 |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Check enabled policy t-imp-1637805913 |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Check that enforced policy t-imp-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Check that policy imagespec-cleanup-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Check that policy t-imp-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Create new policy t-imp-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Delete policy imagespec-cleanup-1637805913 |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Deleted policy t-imp-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Disable policy t-imp-1637805913 |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Edit policy t-imp-1637805913 |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Enable policy t-imp-1637805913 |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Enforce policy t-imp-1637805913 |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Policy t-imp-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Verify policy t-imp-1637805913 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Verify policy t-imp-1637805913 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Verify policy t-imp-1637805913 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Verify that policy imagespec-cleanup-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Verify the History page for policy t-imp-1637805913 cluster hchen-aws-clc template t-imp-1637805913-image-vulnerability |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Verify the History page for policy t-imp-1637805913 cluster hchen-aws-clc template t-imp-1637805913-subscription |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Wait for cluster violation status to become available |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Wait for imagespec-cleanup-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-1727: GRC: ImageManifest policy governance @svt Wait for policy t-imp-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Check created policy policy-certificatepolicy-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Check enabled policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Check violations stay reported but not remediated |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Create certificate policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Delete created policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Edit policy policy-certificatepolicy-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Validate disable of the policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Validate enable of the policy policy-certificatepolicy-1637805913 |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Validate violations/status of created policy policy-certificatepolicy-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Validate violations/status of created policy policy-certificatepolicy-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Verify all information about the created certificate policy policy-certificatepolicy-1637805913 on the "Govern and risk" page |
| :white_check_mark: | passed | RHACM4K-2294: GRC: CertificatePolicy governance @bvt @svt Wait for certificate policy policy-certificatepolicy-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-2342: GRC: Verify create policy with different NS @svt Create Namespace policy to create template ns as duplicatetest |
| :white_check_mark: | passed | RHACM4K-2342: GRC: Verify create policy with different NS @svt Create Pod policy with default as namespace |
| :white_check_mark: | passed | RHACM4K-2342: GRC: Verify create policy with different NS @svt Create Pod policy with duplicatetest as namespace |
| :white_check_mark: | passed | RHACM4K-2342: GRC: Verify create policy with different NS @svt Delete created policies |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Create new policy test-policy-1-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Create new policy test-policy-2-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Create new policy test-policy-3-1637805913 using the form |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Policy test-policy-1-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Policy test-policy-2-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Policy test-policy-3-1637805913 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Verify the content of Categories card |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Verify the content of Standards card |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Verify toggle button does work |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Wait for policy test-policy-1-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Wait for policy test-policy-2-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-2343: GRC: All policies page: Verify summary table Wait for policy test-policy-3-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-2349: GRC: Create policy page: Check policy field validations @svt Check long but valid policy name pattern |
| :white_check_mark: | passed | RHACM4K-2349: GRC: Create policy page: Check policy field validations @svt Check that invalid policy name pattern issues an error |
| :white_check_mark: | passed | RHACM4K-2349: GRC: Create policy page: Check policy field validations @svt Check warning about a policy with a duplicate name |
| :white_check_mark: | passed | RHACM4K-2349: GRC: Create policy page: Check policy field validations @svt Cleanup: delete previously created policy |
| :white_check_mark: | passed | RHACM4K-2351: GRC: Create policy page: Updating YAML in editor @svt Access the Create policy page |
| :white_check_mark: | passed | RHACM4K-2351: GRC: Create policy page: Updating YAML in editor @svt Check form is updated when whole policy YAML is pasted into YAML editor |
| :white_check_mark: | passed | RHACM4K-2351: GRC: Create policy page: Updating YAML in editor @svt Individual YAML updates are reflected in a form |
| :white_check_mark: | passed | RHACM4K-2354: GRC: Check existent and non-existent URLs for the policy Create policy for the URL visit |
| :white_check_mark: | passed | RHACM4K-2354: GRC: Check existent and non-existent URLs for the policy Delete the policy |
| :white_check_mark: | passed | RHACM4K-2354: GRC: Check existent and non-existent URLs for the policy Verify URLs for Namespace and policy that do exist |
| :white_check_mark: | passed | RHACM4K-2354: GRC: Check existent and non-existent URLs for the policy Verify URLs for Namespace and policy that dont exist |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for CertificatePolicy specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for ComplianceOperator specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for EtcdEncryption specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for GatekeeperOperator specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for IamPolicy specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for ImageManifestVulnPolicy specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for LimitRange specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for Namespace specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for Pod specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for PodSecurityPolicy specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for Role specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for RoleBinding specification |
| :white_check_mark: | passed | RHACM4K-2357: GRC: Create policy page: Verify templates @svt Verify YAML template for SecurityContextConstraints specification |
| :white_check_mark: | passed | RHACM4K-247: GRC: Create policy with invalid yaml Create policy should fail with invalid indentation in yaml |
| :white_check_mark: | passed | RHACM4K-247: GRC: Create policy with invalid yaml Create policy should fail with invalid policy name in yaml |
| :white_check_mark: | passed | RHACM4K-247: GRC: Create policy with invalid yaml Create policy should fail with missing namespace in yaml |
| :white_check_mark: | passed | RHACM4K-2509: GRC: All policy page: Verify stability of YAML Paste raw YAML of policy policy-gatekeeper-1637805913 into YAML editor |
| :white_check_mark: | passed | RHACM4K-2509: GRC: All policy page: Verify stability of YAML Paste raw YAML of policy policy-limitrange-1637805913 into YAML editor |
| :white_check_mark: | passed | RHACM4K-2509: GRC: All policy page: Verify stability of YAML Set policy-gatekeeper-1637805913 to an Enforced state and then back to Inform |
| :white_check_mark: | passed | RHACM4K-2509: GRC: All policy page: Verify stability of YAML Set policy-limitrange-1637805913 to an Enforced state and then back to Inform |
| :white_check_mark: | passed | RHACM4K-2509: GRC: All policy page: Verify stability of YAML Verify that YAML editor content matches the template |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Check that policy policy-create-credential-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Check that policy policy-create-subscription-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Create a subscription to install the Ansible operator |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Create the credential policy using the YAML |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Delete policy policy-create-credential-1637805913 |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Delete policy policy-create-subscription-1637805913 |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Enforce policy-create-credential-1637805913 |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Wait for policy-create-credential-1637805913 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Wait for policy-create-credential-1637805913 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: Wait for policy-create-subscription-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Ansible setup: verifies sidebar credentials after creation |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check All policies listing page content as e2e-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check All policies listing page content as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check All policies listing page content as e2e-cluster-admin-ns |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check All policies listing page content as e2e-edit-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check All policies listing page content as e2e-group-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check All policies listing page content as e2e-view-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-edit-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-group-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-view-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check policy creation as e2e-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check policy creation as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check policy creation as e2e-cluster-admin-ns |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check policy creation as e2e-edit-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check policy creation as e2e-group-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check policy creation as e2e-view-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check policy removal as e2e-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check policy removal as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check policy removal as e2e-cluster-admin-ns |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-edit-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-group-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-view-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-cluster-admin-ns |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-edit-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-group-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-view-cluster |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Create policies used for the testing |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Login e2e-admin-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Login e2e-cluster-admin-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Login e2e-cluster-admin-ns user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Login e2e-edit-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Login e2e-group-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Login e2e-view-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Logout |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Logout e2e-admin-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Logout e2e-cluster-admin-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Logout e2e-cluster-admin-ns user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Logout e2e-edit-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Logout e2e-group-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Logout e2e-view-cluster user |
| :white_check_mark: | passed | RHACM4K-2584: GRC: Role Based Access Control tests @rbac Verify that CYPRESS_RBAC_PASS environment variable is defined |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt "Govern risk" page can be launched. |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Check created policy policy-check-fromsecret-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Check enabled policy policy-check-fromsecret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Check remediated the violations |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Check that policy policy-check-fromsecret-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Check that policy policy-clean-fromsecret-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Check that policy policy-create-secret-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Creates the policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Delete created policy policy-check-fromsecret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Delete policy policy-clean-fromsecret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Delete policy policy-create-secret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Edit policy policy-check-fromsecret-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Validate disable of the policy policy-check-fromsecret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Validate enable of the policy policy-check-fromsecret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Validate violations/status of created policy policy-check-fromsecret-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Validate violations/status of created policy policy-check-fromsecret-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Verify that policy policy-clean-fromsecret-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Verify that policy policy-create-secret-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Wait for policy-check-fromsecret-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Wait for policy-clean-fromsecret-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3345: GRC: Test fromSecret to customize the template for configuration policies @svt Wait for policy-create-secret-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt "Govern risk" page can be launched. |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Check created policy policy-check-fromconfigmap-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Check enabled policy policy-check-fromconfigmap-1637805913 |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Check remediated the violations |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Check that policy policy-check-fromconfigmap-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Check that policy policy-clean-fromconfigmap-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Check that policy policy-create-config-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Creates the policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Delete created policy policy-check-fromconfigmap-1637805913 |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Delete policy policy-clean-fromconfigmap-1637805913 |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Delete policy policy-create-config-1637805913 |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Edit policy policy-check-fromconfigmap-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Validate disable of the policy policy-check-fromconfigmap-1637805913 |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Validate enable of the policy policy-check-fromconfigmap-1637805913 |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Validate violations/status of created policy policy-check-fromconfigmap-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Validate violations/status of created policy policy-check-fromconfigmap-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Verify that policy policy-clean-fromconfigmap-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Verify that policy policy-create-config-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Wait for policy-check-fromconfigmap-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Wait for policy-clean-fromconfigmap-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3346: GRC: Test fromConfigmap to customize the template for configuration policies  @svt Wait for policy-create-config-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Check created policy policy-check-fromclusterclaim-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Check enabled policy policy-check-fromclusterclaim-1637805913 |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Check remediated the violations |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Check that policy policy-check-fromclusterclaim-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Check that policy policy-clean-fromclusterclaim-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Creates the policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Delete created policy policy-check-fromclusterclaim-1637805913 |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Delete policy policy-clean-fromclusterclaim-1637805913 |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Edit policy policy-check-fromclusterclaim-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Validate disable of the policy policy-check-fromclusterclaim-1637805913 |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Validate enable of the policy policy-check-fromclusterclaim-1637805913 |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Validate violations/status of created policy policy-check-fromclusterclaim-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Validate violations/status of created policy policy-check-fromclusterclaim-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Verify that policy policy-clean-fromclusterclaim-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Wait for policy-check-fromclusterclaim-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3347: GRC: Test fromClusterClaim to customize the template for configuration policies @svt Wait for policy-clean-fromclusterclaim-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Check created policy policy-check-lookup-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Check enabled policy policy-check-lookup-1637805913 |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Check remediated the violations |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Check that policy policy-check-lookup-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Check that policy policy-clean-lookup-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Creates the policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Delete created policy policy-check-lookup-1637805913 |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Delete policy policy-clean-lookup-1637805913 |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Edit policy policy-check-lookup-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Validate disable of the policy policy-check-lookup-1637805913 |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Validate enable of the policy policy-check-lookup-1637805913 |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Validate violations/status of created policy policy-check-lookup-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Validate violations/status of created policy policy-check-lookup-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Verify that policy policy-clean-lookup-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Wait for policy-check-lookup-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3348: GRC: Test lookup to customize the template for configuration policies @svt Wait for policy-clean-lookup-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt "Govern risk" page can be launched. |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Check created policy policy-check-testindent-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Check enabled policy policy-check-testindent-1637805913 |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Check remediated the violations |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Check that policy policy-check-testindent-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Check that policy policy-clean-testindent-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Check that policy policy-create-secret-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Check that policy policy-remove-secret-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Creates the policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Delete created policy policy-check-testindent-1637805913 |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Delete policy policy-clean-testindent-1637805913 |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Delete policy policy-create-secret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Delete policy policy-remove-secret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Edit policy policy-check-testindent-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Validate disable of the policy policy-check-testindent-1637805913 |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Validate enable of the policy policy-check-testindent-1637805913 |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Validate violations/status of created policy policy-check-testindent-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Validate violations/status of created policy policy-check-testindent-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Verify that policy policy-clean-testindent-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Verify that policy policy-create-secret-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Verify that policy policy-remove-secret-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Wait for policy-check-testindent-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Wait for policy-clean-testindent-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Wait for policy-create-secret-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3353: GRC: Test indent to customize the template for configuration policies @svt Wait for policy-remove-secret-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt "Govern risk" page can be launched. |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check created policy policy-check-testcert-fromsecret-1637805913 is not present |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check disabled policy |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check enabled policy policy-check-testcert-fromsecret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check remediated the violations |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check that policy policy-check-testcert-fromsecret-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check that policy policy-clean-testcert-1637805913 is present in the policy listing |
| :x: | failed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check that policy policy-create-certificate-1637805913 is present in the policy listing |
| :x: | failed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check that policy policy-create-issuer-1637805913 is present in the policy listing |
| :x: | failed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Creates the policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Delete created policy policy-check-testcert-fromsecret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Delete policy policy-clean-testcert-1637805913 |
| :x: | failed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Delete policy policy-create-certificate-1637805913 |
| :x: | failed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Delete policy policy-create-issuer-1637805913 |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Edit policy policy-check-testcert-fromsecret-1637805913 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Validate disable of the policy policy-check-testcert-fromsecret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Validate enable of the policy policy-check-testcert-fromsecret-1637805913 |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Validate violations/status of created policy policy-check-testcert-fromsecret-1637805913 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Validate violations/status of created policy policy-check-testcert-fromsecret-1637805913 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Verify that policy policy-clean-testcert-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Verify that policy policy-create-certificate-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Verify that policy policy-create-issuer-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Wait for policy-check-testcert-fromsecret-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Wait for policy-clean-testcert-1637805913 status to become available |
| :x: | failed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Wait for policy-create-certificate-1637805913 status to become available |
| :x: | failed | RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Wait for policy-create-issuer-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Check that policy policy-create-credential-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Check that policy policy-create-subscription-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Check that policy to-automate-1637805913 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Create a subscription to install the Ansible operator |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Create the credential policy using the YAML |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Creates the policy to automate using the YAML |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Delete policy policy-create-credential-1637805913 |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Delete policy policy-create-subscription-1637805913 |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Delete policy policy-delete-subscription-1637805913 |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Delete policy to-automate-1637805913 |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Enforce policy-create-credential-1637805913 |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Enforce policy-delete-subscription-1637805913 |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Prompts the user to install the ansible operator |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Skips install prompt if the ansible operator is installed |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Successfully can schedule a "manual" automation |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Successfully can schedule a "run once" automation |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Successfully can schedule a disabled automation |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Verifies successful job history with mock |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Verify that policy policy-create-credential-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Verify that policy policy-create-subscription-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Verify that policy policy-delete-subscription-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Verify that policy to-automate-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Wait for policy-create-credential-1637805913 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Wait for policy-create-credential-1637805913 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Wait for policy-create-subscription-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Wait for policy-delete-subscription-1637805913 status to be Compliant |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Wait for policy-delete-subscription-1637805913 status to become NonCompliant |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt Wait for to-automate-1637805913 status to become available |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt verifies sidebar credentials after creation |
| :white_check_mark: | passed | RHACM4K-3471: GRC: All policies page Verify automation modal @bvt @svt verifies sidebar credentials not existing |
| :white_check_mark: | passed | RHACM4K-734: GRC: As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy @rbac Check All policies listing page content as e2e-cmgr-admin-cluster |
| :white_check_mark: | passed | RHACM4K-734: GRC: As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-cmgr-admin-cluster |
| :white_check_mark: | passed | RHACM4K-734: GRC: As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy @rbac Check policy creation as e2e-cmgr-admin-cluster |
| :white_check_mark: | passed | RHACM4K-734: GRC: As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy @rbac Check policy removal as e2e-cmgr-admin-cluster |
| :white_check_mark: | passed | RHACM4K-734: GRC: As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-cmgr-admin-cluster |
| :white_check_mark: | passed | RHACM4K-734: GRC: As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-cmgr-admin-cluster |
| :white_check_mark: | passed | RHACM4K-734: GRC: As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy @rbac Login e2e-cmgr-admin-cluster user |
| :white_check_mark: | passed | RHACM4K-734: GRC: As an user with cluster-wide-role-binding of open-cluster-management:cluster-manager-admin role to check policy @rbac Logout e2e-cmgr-admin-cluster user |
| :white_check_mark: | passed | RHACM4K-956: GRC: As an user with namespace-role-binding of default admin role to check policy @rbac Check All policies listing page content as e2e-admin-ns |
| :white_check_mark: | passed | RHACM4K-956: GRC: As an user with namespace-role-binding of default admin role to check policy @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-admin-ns |
| :white_check_mark: | passed | RHACM4K-956: GRC: As an user with namespace-role-binding of default admin role to check policy @rbac Check policy creation as e2e-admin-ns |
| :white_check_mark: | passed | RHACM4K-956: GRC: As an user with namespace-role-binding of default admin role to check policy @rbac Check policy removal as e2e-admin-ns |
| :white_check_mark: | passed | RHACM4K-956: GRC: As an user with namespace-role-binding of default admin role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-admin-ns |
| :white_check_mark: | passed | RHACM4K-956: GRC: As an user with namespace-role-binding of default admin role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-admin-ns |
| :white_check_mark: | passed | RHACM4K-956: GRC: As an user with namespace-role-binding of default admin role to check policy @rbac Login e2e-admin-ns user |
| :white_check_mark: | passed | RHACM4K-956: GRC: As an user with namespace-role-binding of default admin role to check policy @rbac Logout e2e-admin-ns user |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check All policies listing page content as e2e-group-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check All policies listing page content as e2e-view-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-group-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-view-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check policy creation as e2e-group-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check policy creation as e2e-view-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-group-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-view-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-group-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-view-ns |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Login e2e-group-ns user |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Login e2e-view-ns user |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Logout e2e-group-ns user |
| :white_check_mark: | passed | RHACM4K-957: GRC: As an user with namespace-role-binding of default view role to check policy @rbac Logout e2e-view-ns user |
| :white_check_mark: | passed | RHACM4K-958: GRC: As an user with namespace-role-binding of default edit role to check policy @rbac Check All policies listing page content as e2e-edit-ns |
| :white_check_mark: | passed | RHACM4K-958: GRC: As an user with namespace-role-binding of default edit role to check policy @rbac Check detailed test-1637805913-e2e-rbac-test-1 policy page as e2e-edit-ns |
| :white_check_mark: | passed | RHACM4K-958: GRC: As an user with namespace-role-binding of default edit role to check policy @rbac Check policy creation as e2e-edit-ns |
| :white_check_mark: | passed | RHACM4K-958: GRC: As an user with namespace-role-binding of default edit role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy Clusters page as e2e-edit-ns |
| :white_check_mark: | passed | RHACM4K-958: GRC: As an user with namespace-role-binding of default edit role to check policy @rbac Check test-1637805913-e2e-rbac-test-1 policy edit page as e2e-edit-ns |
| :white_check_mark: | passed | RHACM4K-958: GRC: As an user with namespace-role-binding of default edit role to check policy @rbac Login e2e-edit-ns user |
| :white_check_mark: | passed | RHACM4K-958: GRC: As an user with namespace-role-binding of default edit role to check policy @rbac Logout e2e-edit-ns user |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt "Govern risk" page can be launched. |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt Check that policy policy-create-certificate-1637805913 is present in the policy listing |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt Check that policy policy-create-issuer-1637805913 is present in the policy listing |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt Create the clean up policy using the YAML |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt Delete policy policy-create-certificate-1637805913 |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt Delete policy policy-create-issuer-1637805913 |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt Verify that policy policy-create-certificate-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt Verify that policy policy-create-issuer-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt Wait for policy-create-certificate-1637805913 status to become available |
| :white_check_mark: | passed | Setup - create a certificate expiring soon @bvt @svt Wait for policy-create-issuer-1637805913 status to become available |
| :white_check_mark: | passed | clean up rbac related @rbac Ansible cleanup: Create the clean up policy using the YAML |
| :white_check_mark: | passed | clean up rbac related @rbac Ansible cleanup: Delete policy policy-delete-subscription-1637805913 |
| :white_check_mark: | passed | clean up rbac related @rbac Ansible cleanup: Enforce policy-delete-subscription-1637805913 |
| :white_check_mark: | passed | clean up rbac related @rbac Ansible cleanup: Verify that policy policy-delete-subscription-1637805913 is not present in the policy listing |
| :white_check_mark: | passed | clean up rbac related @rbac Ansible cleanup: Wait for policy-delete-subscription-1637805913 status to be Compliant |
| :white_check_mark: | passed | clean up rbac related @rbac Ansible cleanup: Wait for policy-delete-subscription-1637805913 status to become NonCompliant |
| :white_check_mark: | passed | clean up rbac related @rbac Delete test policies |
| :white_check_mark: | passed | clean up rbac related @rbac Login again as kubeadmin |


---

### Failed Test Details

#### :x: RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check that policy policy-create-certificate-1637805913 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13278:8)
```

#### :x: RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Check that policy policy-create-issuer-1637805913 is present in the policy listing

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13278:8)
```

#### :x: RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Create the clean up policy using the YAML

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11939:27)
```

#### :x: RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Delete policy policy-create-certificate-1637805913

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11939:27)
```

#### :x: RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Delete policy policy-create-issuer-1637805913

```
AssertionError: Timed out retrying after 30000ms: expected '/multicloud/policies/create' to equal '/multicloud/policies/all'
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:11939:27)
```

#### :x: RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Wait for policy-create-certificate-1637805913 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13278:8)
```

#### :x: RHACM4K-3469: GRC: Test indent to support for retrieving certificates from a secret @svt Wait for policy-create-issuer-1637805913 status to become available

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `input[aria-label="Search input"]`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com/__cypress/tests?p=tests/cypress/support/index.js:13278:8)
```

