# :warning: Had some failures when running regression on cluster ocp4-gcp-3 with test snapshot 2.3.0-SNAPSHOT-2021-04-17-07-15-32 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/257/


ACM Version: v2.3.0

Hub Cluster Version: 4.8.2

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.2

Managed Cluster: https://console-openshift-console.apps.ocp2.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202108050730/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up mutation policies |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up stable/policy-gatekeeper-sample |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Install mutation policy Creating mutation policy on hub |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been removed |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Disabling mutation feature through policy |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Informing stable/policy-gatekeeper-operator |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enabling mutation feature through policy |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Enforcing policy-gatekeeper-operator to enable mutation feature |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Enforcing stable/policy-gatekeeper-operator |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Informing stable/policy-gatekeeper-operator |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator stable/policy-gatekeeper-operator should be noncompliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating a valid ns should not be blocked by gatekeeper |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message |
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be created on hub |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be noncompliant |
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
| :white_check_mark: | passed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :x: | failed | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
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


---

### Failed Test Details

#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-annotation-owner should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:371
Timed out after 60.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:385
```

#### :x:  GRC: [P1][Sev1][policy-grc] Install mutation policy policy-gatekeeper-image-pull-policy should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:355
Timed out after 60.001s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:369
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag off

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:444
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:447 +0x237
reflect.Value.call(0x1309bc0, 0x15a9670, 0x13, 0x1502683, 0x4, 0xc0005dd0e0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a9670, 0x13, 0xc0005dd0e0, 0x0, 0x0, 0x54d78c22f89ac, 0xc0005409b8, 0x54d78c22f89ac)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0002fc980, 0xc0005409b0, 0x23dca80, 0x203000, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0002fc980, 0x16f8720, 0xc0004b5f80, 0x412f01, 0x0, 0x0, 0x0, 0xc0004b5f80)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0002fc980, 0x16f8720, 0xc0004b5f80, 0x0, 0x0, 0x0, 0x16ecfa0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.7.4()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:448 +0x124
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002e5e60)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002e5e60, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test disabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:433
Timed out after 60.935s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:438
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if Assign/AssingnMetadata CRDs have been created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:306
Timed out after 240.001s.
Expected
    <string>: Error from server (NotFound): customresourcedefinitions.apiextensions.k8s.io "assign.mutations.gatekeeper.sh" not found
    
to contain substring
    <string>: CREATED AT
    assign.mutations.gatekeeper.sh
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:310
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Checking if gatekeeper controller manager has mutation flag on

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:328
Test Panicked
/usr/lib/golang/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:331 +0x237
reflect.Value.call(0x1309bc0, 0x15a95c8, 0x13, 0x1502683, 0x4, 0xc0005750b0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a95c8, 0x13, 0xc0005750b0, 0x0, 0x0, 0x54d1ca483db63, 0xc000541db8, 0x54d1ca483db63)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000081240, 0xc000541db0, 0x23dca80, 0x203000, 0xc0005751c8)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000081240, 0x16f8720, 0xc000446d40, 0x412f01, 0x0, 0x0, 0x0, 0xc000446d40)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000081240, 0x16f8720, 0xc000446d40, 0x0, 0x0, 0x0, 0x16ecfa0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.4.6()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:332 +0x147
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002e5e60)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002e5e60, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:317
Timed out after 60.588s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:322
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test enabling gatekeeper mutation feature policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:335
Timed out after 60.020s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:349
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test gatekeeper mutation feature Verify mutation feature

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:391
Timed out after 180.000s.
Expected
    <string>: 
to equal
    <string>: admin
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:398
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:20
Test Panicked
/usr/lib/golang/src/runtime/panic.go:212

Panic: runtime error: invalid memory address or nil pointer dereference

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.isOCP44(0xc0003b13c8)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:27 +0x106
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func3.1()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:21 +0x22
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002e5e60)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002e5e60, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:134
Timed out after 60.002s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:140
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:82
Timed out after 120.000s.
Expected
    <string>: Pending
to equal
    <string>: Running
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:105
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:108
Timed out after 60.001s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:113
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample Creating an invalid ns should generate a violation message

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:224
Timed out after 180.000s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:229
```

#### :x:  GRC: [P1][Sev1][policy-grc] Test stable/policy-gatekeeper-sample stable/policy-gatekeeper-sample should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:195
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_downstream_test.go:209
```

#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:269
Timed out after 180.026s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:274
```

#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:240
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:254
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:164
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:170
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:179
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:185
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:133
Timed out after 120.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:139
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Patching webhook check-ignore-label.gatekeeper.sh failurePolicy to ignore

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:153
Timed out after 60.197s.
Expected
    <string>: Error from server (NotFound): validatingwebhookconfigurations.admissionregistration.k8s.io "gatekeeper-validating-webhook-configuration" not found
    
to contain substring
    <string>: AGE
    gatekeeper-validating-webhook-configuration
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:158
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:193
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:207
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:327
Timed out after 120.000s.
Expected
    <int>: 1
to equal
    <int>: 3
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:346
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:176
Timed out after 60.000s.
Expected
    <string>: Pending
to equal
    <string>: Running
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:194
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:196
Timed out after 120.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:202
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:303
Timed out after 120.000s.
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:309
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:311
Test Panicked
/usr/lib/golang/src/runtime/iface.go:260

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.7.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:315 +0x149
reflect.Value.call(0x1309bc0, 0x15a93f0, 0x13, 0x1502683, 0x4, 0xc0003f50e0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a93f0, 0x13, 0xc0003f50e0, 0x0, 0x0, 0x54a6ee90f8331, 0xc0003c8698, 0x54a6ee90f8331)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000294200, 0xc0003c8690, 0x23dca80, 0x203000, 0xc00003c120)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000294200, 0x16f8720, 0xc0001fe750, 0x412f01, 0x0, 0x0, 0x0, 0xc0001fe750)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000294200, 0x16f8720, 0xc0001fe750, 0x0, 0x0, 0x0, 0x16ecfa0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.7()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:316 +0x148
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002e5e60)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002e5e60, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:318
Test Panicked
/usr/lib/golang/src/runtime/iface.go:260

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.8.1(0x0, 0x0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:322 +0x149
reflect.Value.call(0x1309bc0, 0x15a9400, 0x13, 0x1502683, 0x4, 0xc0003f50e0, 0x0, 0x0, 0x1309bc0, 0x1, ...)
	/usr/lib/golang/src/reflect/value.go:460 +0x8ab
reflect.Value.Call(0x1309bc0, 0x15a9400, 0x13, 0xc0003f50e0, 0x0, 0x0, 0x54a6ee98fb079, 0xc0003c8cd8, 0x54a6ee98fb079)
	/usr/lib/golang/src/reflect/value.go:321 +0xb4
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000295080, 0xc0003c8cd0, 0x23dca80, 0x203000, 0x80)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:78 +0xe9
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000295080, 0x16f8720, 0xc0001ffda0, 0x412f01, 0x0, 0x0, 0x0, 0xc0001ffda0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:112 +0x8f
github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000295080, 0x16f8720, 0xc0001ffda0, 0x0, 0x0, 0x0, 0x16ecfa0)
	/go/src/github.com/open-cluster-management/governance-policy-framework/vendor/github.com/onsi/gomega/internal/asyncassertion/async_assertion.go:51 +0x81
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.glob..func2.4.8()
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:323 +0x148
github.com/open-cluster-management/governance-policy-framework/test/policy-collection.TestE2e(0xc0002e5e60)
	/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_collection_suite_test.go:50 +0xf8
testing.tRunner(0xc0002e5e60, 0x15a92a0)
	/usr/lib/golang/src/testing/testing.go:1050 +0xdc
created by testing.(*T).Run
	/usr/lib/golang/src/testing/testing.go:1095 +0x28b
```

#### :x: RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:272
Timed out after 120.000s.
Expected
    <nil>: nil
not to be nil
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_comp_operator_test.go:280
```

