# :warning: Had some failures when running regression on cluster ocp4-gcp-2 with test snapshot 2.2.6-SNAPSHOT-2021-07-24-01-04-04 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/254/


ACM Version: v2.2.6

Hub Cluster Version: 4.7.21

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-2.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.2

Managed Cluster: https://console-openshift-console.apps.acmqe-22-ocp4-gcp-2-aws-hive.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202108050148/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: | passed |  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be noncompliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Clean up before all |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing community/policy-gatekeeper-operator |
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
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


---

### Failed Test Details

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:139
Timed out after 60.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:145
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:123
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:137
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:353
Expected
    <string>: Error from server (NotFound): namespaces "openshift-compliance" not found
    
to contain substring
    <string>: namespace "openshift-compliance" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:360
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:332
Expected
    <string>: Error from server (NotFound): scansettingbindings.compliance.openshift.io "e8" not found
    
to contain substring
    <string>: scansettingbinding.compliance.openshift.io "e8" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:338
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:56
Expected
    <string>: Error from server (NotFound): scansettingbindings.compliance.openshift.io "e8" not found
    
to contain substring
    <string>: scansettingbinding.compliance.openshift.io "e8"
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:65
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:178
Timed out after 360.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:191
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:199
Timed out after 120.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:205
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:162
Timed out after 120.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:176
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:308
Timed out after 120.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:314
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:316
Timed out after 30.000s.
Expected
    <*errors.StatusError | 0xc0000ca8c0>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "compliancesuites.compliance.openshift.io \"e8\" not found",
            Reason: "NotFound",
            Details: {
                Name: "e8",
                Group: "compliance.openshift.io",
                Kind: "compliancesuites",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:323
Timed out after 30.001s.
Expected
    <*errors.StatusError | 0xc0000bc460>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "compliancesuites.compliance.openshift.io \"e8\" not found",
            Reason: "NotFound",
            Details: {
                Name: "e8",
                Group: "compliance.openshift.io",
                Kind: "compliancesuites",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:277
Timed out after 120.000s.
Expected
    <*errors.StatusError | 0xc0000c3180>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "compliancesuites.compliance.openshift.io \"e8\" not found",
            Reason: "NotFound",
            Details: {
                Name: "e8",
                Group: "compliance.openshift.io",
                Kind: "compliancesuites",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/open-cluster-management/governance-policy-propagator/test/utils/utils.go:79
```

