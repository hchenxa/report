# :warning: Had some failures when running regression on cluster ocp4-awsgov-01 with test snapshot 2.4.0-SNAPSHOT-2021-10-02-11-10-03 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/282/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-rc.1

Hub Cluster: https://multicloud-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com

Managed Cluster Version: 4.9.0-rc.1

Managed Cluster: https://console-openshift-console.apps.ocp4-awsgov-01.aws-gov.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110041639/

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
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: | failed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: | passed | RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |


---

### Failed Test Details

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:317
Timed out after 60.001s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:319
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:313
Timed out after 60.001s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:315
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:378
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:381 +0x245
reflect.Value.call(0x13348e0, 0x15b1be8, 0x13, 0x150b494, 0x4, 0xc000578f48, 0x0, 0x0, 0x203000, 0x203000, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x13348e0, 0x15b1be8, 0x13, 0xc000578f48, 0x0, 0x0, 0x2, 0x18, 0x7f6035f6e8c8)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal.NewAsyncAssertion.func1(0xc5ff2671d2f9, 0xc00038cf58, 0xc5ff2671d2f9, 0xc00005e800, 0xc000050ed8)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/async_assertion.go:48 +0xaa
github.com/onsi/gomega/internal.(*AsyncAssertion).pollActual(0xc00038cf00, 0xc00038cf50, 0x1fbbf80, 0x0, 0xc0000b4378)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/async_assertion.go:117 +0x4f
github.com/onsi/gomega/internal.(*AsyncAssertion).match(0xc00038cf00, 0x16c1468, 0xc000582c50, 0x410101, 0x0, 0x0, 0x0, 0xc000582c50)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/async_assertion.go:147 +0x92
github.com/onsi/gomega/internal.(*AsyncAssertion).Should(0xc00038cf00, 0x16c1468, 0xc000582c50, 0x0, 0x0, 0x0, 0xc00038cf00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/async_assertion.go:92 +0x74
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:382 +0x13d
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002f5e00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:38 +0xe5
testing.tRunner(0xc0002f5e00, 0x15b18d8)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:367
Timed out after 61.746s.
Expected
    <string>: I1004 18:45:03.508206   11486 request.go:668] Waited for 1.079356654s due to client-side throttling, not priority and fairness, request: GET:https://api.ocp4-awsgov-01.aws-gov.red-chesterfield.com:6443/apis/wgpolicyk8s.io/v1alpha2?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:372
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:259
Timed out after 240.000s.
Expected
    <string>: Error from server (NotFound): customresourcedefinitions.apiextensions.k8s.io "assign.mutations.gatekeeper.sh" not found
    
to contain substring
    <string>: CREATED AT
    assign.mutations.gatekeeper.sh
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:263
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:281
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:284 +0x245
reflect.Value.call(0x13348e0, 0x15b1b70, 0x13, 0x150b494, 0x4, 0xc0006b0f40, 0x0, 0x0, 0x203000, 0x203000, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x13348e0, 0x15b1b70, 0x13, 0xc0006b0f40, 0x0, 0x0, 0x1, 0x18, 0x7f6035f6e8c8)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal.NewAsyncAssertion.func1(0xc5a771421712, 0xc00038c828, 0xc5a771421712, 0xc00005f000, 0xc0000536d8)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/async_assertion.go:48 +0xaa
github.com/onsi/gomega/internal.(*AsyncAssertion).pollActual(0xc00038c7d0, 0xc00038c820, 0x1fbbf80, 0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/async_assertion.go:117 +0x4f
github.com/onsi/gomega/internal.(*AsyncAssertion).match(0xc00038c7d0, 0x16c1468, 0xc000418ed0, 0x410101, 0x0, 0x0, 0x0, 0xc000418ed0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/async_assertion.go:147 +0x92
github.com/onsi/gomega/internal.(*AsyncAssertion).Should(0xc00038c7d0, 0x16c1468, 0xc000418ed0, 0x0, 0x0, 0x0, 0xc00038c7d0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/async_assertion.go:92 +0x74
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:285 +0x13d
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002f5e00)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:38 +0xe5
testing.tRunner(0xc0002f5e00, 0x15b18d8)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:270
Timed out after 61.859s.
Expected
    <string>: I1004 18:38:46.795262   10521 request.go:668] Waited for 1.055558681s due to client-side throttling, not priority and fairness, request: GET:https://api.ocp4-awsgov-01.aws-gov.red-chesterfield.com:6443/apis/work.open-cluster-management.io/v1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:275
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:255
Timed out after 60.001s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:257
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:325
Timed out after 180.001s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:332
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:115
Timed out after 60.001s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:121
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:130
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:136
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:78
Timed out after 120.035s.
Expected
    <string>: nil
to equal
    <string>: Running
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:101
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:104
Timed out after 61.862s.
Expected
    <string>: I1004 18:21:35.993770    7545 request.go:668] Waited for 1.075153972s due to client-side throttling, not priority and fairness, request: GET:https://api.ocp4-awsgov-01.aws-gov.red-chesterfield.com:6443/apis/build.openshift.io/v1?timeout=32s
    Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:109
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:144
Timed out after 180.001s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:146
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:196
Timed out after 180.156s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: validation.gatekeeper.sh
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:201
```

#### :x: RHACM4K-3055 GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:179
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:181
```

