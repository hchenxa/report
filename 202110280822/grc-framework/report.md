# :warning: Had some failures when running regression on cluster ocp4-acm24-azgov-01 with test snapshot 2.4.0-SNAPSHOT-2021-10-25-23-58-51 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/380/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0

Hub Cluster: https://multicloud-console.apps.ocp4-acm24-azgov-01.qemag.azure.devcluster.openshift.com

Managed Cluster Version: 4.9.4

Managed Cluster: https://console-openshift-console.apps.qe2-vmware-pkt.dev02.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110280822/

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
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that a compliant policy reports a metric of 0 |
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that a noncompliant policy reports a metric of 1 |
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that endpoint has a HELP comment for the metric |
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that the endpoint does not expose metrics without auth |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Cleans up |
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Sets up the metrics service endpoint for tests |
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Checks that a noncompliant policy reports a metric |
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Checks that changing the policy to compliant removes the metric |
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Checks that the endpoint does not expose metrics without auth |
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Cleans up |
| :x: | failed | GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Sets up the metrics service endpoint for tests |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test the Policy Generator in an App subscription Cleans up |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test the Policy Generator in an App subscription Sets up the application subscription |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test the stable IAM policy Clean up stable/policy-limitclusteradmin |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test the stable IAM policy Make stable/policy-limitclusteradmin be compliant |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test the stable IAM policy Make the policy noncompliant |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test the stable IAM policy stable/policy-limitclusteradmin should be compliant |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test the stable IAM policy stable/policy-limitclusteradmin should be created on the hub |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test the stable IAM policy stable/policy-limitclusteradmin should be created on the managed cluster |
| :white_check_mark: | passed | GRC: [P1][Sev1][policy-grc] Test the stable IAM policy stable/policy-limitclusteradmin should be noncompliant |
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

### Failed Test Details

#### :x: GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that a compliant policy reports a metric of 0

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:129
Timed out after 30.001s.
Error: RegExp matcher requires a string or stringer.
Got:    <*url.Error | 0xc000110d20>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc0002f4cf0>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:146
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that a noncompliant policy reports a metric of 1

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:148
Timed out after 30.000s.
Error: RegExp matcher requires a string or stringer.
Got:    <*url.Error | 0xc0000e30b0>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc0005855a0>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:165
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that endpoint has a HELP comment for the metric

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:116
Timed out after 30.001s.
Error: ContainSubstring matcher requires a string or stringer.  Got:
    <*url.Error | 0xc00002ca50>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc00002b540>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:127
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that the endpoint does not expose metrics without auth

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:107
Timed out after 30.001s.
Error: ContainSubstring matcher requires a string or stringer.  Got:
    <*url.Error | 0xc00034bec0>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc0003642a0>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:114
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Sets up the metrics service endpoint for tests

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:38
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:53
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Checks that a noncompliant policy reports a metric

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:142
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: NonCompliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:149
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Checks that changing the policy to compliant removes the metric

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:180
Timed out after 120.000s.
Expected
    <nil>: nil
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:187
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Checks that the endpoint does not expose metrics without auth

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:133
Timed out after 30.000s.
Error: ContainSubstring matcher requires a string or stringer.  Got:
    <*url.Error | 0xc0002c6e70>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc000585990>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:140
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Cleans up

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:218
Expected
    <*errors.errorString | 0xc000239330>: {
        s: "error: the server doesn't have a resource type \"\"\n",
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:224
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Sets up the metrics service endpoint for tests

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:36
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [1] with length 1

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/integration.glob..func4.1()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:53 +0x20a5
github.com/open-cluster-management/governance-policy-framework/test/integration.TestIntegration(0xc00036d080)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/integration_suite_test.go:34 +0xe5
testing.tRunner(0xc00036d080, 0x1597ff8)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

