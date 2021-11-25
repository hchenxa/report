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
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:137
Timed out after 30.000s.
Error: RegExp matcher requires a string or stringer.
Got:    <*url.Error | 0xc000520060>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc000027fc0>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:154
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that a noncompliant policy reports a metric of 1

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:156
Timed out after 30.001s.
Error: RegExp matcher requires a string or stringer.
Got:    <*url.Error | 0xc0004a91d0>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc0002e4750>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:173
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that endpoint has a HELP comment for the metric

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:124
Timed out after 30.000s.
Error: ContainSubstring matcher requires a string or stringer.  Got:
    <*url.Error | 0xc000273800>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc00057b7c0>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:135
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policy_governance_info metric Checks that the endpoint does not expose metrics without auth

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:115
Timed out after 30.001s.
Error: ContainSubstring matcher requires a string or stringer.  Got:
    <*url.Error | 0xc0000fda70>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc000263be0>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_info_metric_test.go:122
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
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:150
Expected
    <*errors.errorString | 0xc000382e50>: {
        s: "error: the server doesn't have a resource type \"\"\n",
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:164
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Checks that changing the policy to compliant removes the metric

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:181
Expected
    <*errors.errorString | 0xc0001311c0>: {
        s: "error: the server doesn't have a resource type \"\"\n",
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:195
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Checks that the endpoint does not expose metrics without auth

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:141
Timed out after 30.000s.
Error: ContainSubstring matcher requires a string or stringer.  Got:
    <*url.Error | 0xc0000ef650>: {
        Op: "Get",
        URL: "",
        Err: <*errors.errorString | 0xc000071160>{
            s: "unsupported protocol scheme \"\"",
        },
    }
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:148
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Cleans up

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:212
Expected
    <*errors.errorString | 0xc000130000>: {
        s: "error: the server doesn't have a resource type \"\"\n",
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:218
```

#### :x: GRC: [P1][Sev1][policy-grc] Test policyreport_info metric Sets up the metrics service endpoint for tests

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:36
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [1] with length 1

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/integration.glob..func4.1()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/policy_report_metric_test.go:53 +0x1f65
github.com/open-cluster-management/governance-policy-framework/test/integration.TestIntegration(0xc000361b00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/integration/integration_suite_test.go:34 +0xe5
testing.tRunner(0xc000361b00, 0x15986c8)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

