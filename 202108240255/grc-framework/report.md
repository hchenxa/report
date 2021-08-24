# :white_check_mark: Passed when running regression on cluster dhwarptest5 with test snapshot 2.4.0-SNAPSHOT-2021-08-11-14-15-20 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/258/


ACM Version: v2.4.0

Hub Cluster Version: 4.7.15

Hub Cluster: https://multicloud-console.apps.dhwarptest5.dev09.red-chesterfield.com

Managed Cluster Version: 4.7.15

Managed Cluster: https://console-openshift-console.apps.dhwarptest5.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202108240255/

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


---

