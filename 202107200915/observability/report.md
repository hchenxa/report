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
| :x: | failed | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted |
| :x: | failed | Observability: [P1][Sev1][Observability][Integration] Checking replicas in advanced config for each component (config/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana-dev/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Stable] Checking default value of PVC and StorageClass (config/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the alertmanager configured in rule (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Integration] Modifying MCO cr to enable observabilityaddon |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Integration] Should not have the expected MCO addon pods when disable observabilityaddon |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have endpoint-operator and metrics-collector being deployed |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement defined in CR |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement in metrics-collector |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Waiting for check no metric data in grafana console |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Integration] Modifying managedcluster cr to enable observability |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Stable] Modifying managedcluster cr to disable observability |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Deleting metrics-collector deployment |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Updating metrics-collector deployment |
| :x: | failed | Observability: [P2][Sev2][Observability][Integration] Checking resources in advanced config (config/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Integration] Should have metrics which defined in custom metrics allowlist (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics after custom metrics allowlist deleted (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in matches section (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in names section (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Check compact args (retention/g0): |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Check receive args (retention/g0): |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Check rule args (retention/g0): |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Check store args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0) |
| :white_check_mark: | passed | Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |
| :white_check_mark: | passed | Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0) |


---

### Failed Test Details

#### :x: Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_observatorium_preserve_test.go:30
Timed out after 60.000s.
Expected success, but got an error:
    <*errors.StatusError | 0xc000cb08c0>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "observatoria.core.observatorium.io \"observability\" not found",
            Reason: "NotFound",
            Details: {
                Name: "observability",
                Group: "core.observatorium.io",
                Kind: "observatoria",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    observatoria.core.observatorium.io "observability" not found
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_observatorium_preserve_test.go:43
```

#### :x: Observability: [P1][Sev1][Observability][Integration] Checking replicas in advanced config for each component (config/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_advanced_config_test.go:86
Test Panicked
/usr/local/go/src/runtime/iface.go:260

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/observability-e2e-test/pkg/tests.glob..func4.2()
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_advanced_config_test.go:105 +0xd32
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc0000ad260, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc0000ad260, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:64 +0xcf
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc000401580, 0x1aa88c0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/it_node.go:26 +0x64
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc00045e2d0, 0x0, 0x1aa88c0, 0xc0000ae900)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:215 +0x638
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc00045e2d0, 0x1aa88c0, 0xc0000ae900)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc0003c9b80, 0xc00045e2d0, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:200 +0x10f
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc0003c9b80, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:170 +0x120
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc0003c9b80, 0xc000409748)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc0000fa070, 0x7fac6fe20208, 0xc00067dd40, 0x1879298, 0x17, 0xc000401420, 0x2, 0x2, 0x1af7260, 0xc0000ae900, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/suite/suite.go:79 +0x586
github.com/onsi/ginkgo.RunSpecsWithCustomReporters(0x1aa9de0, 0xc00067dd40, 0x1879298, 0x17, 0xc000401400, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:229 +0x217
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1aa9de0, 0xc00067dd40, 0x1879298, 0x17, 0xc000141f60, 0x1, 0x1, 0xc000141f70)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:217 +0xad
github.com/open-cluster-management/observability-e2e-test/pkg/tests.TestObservabilityE2E(0xc00067dd40)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:94 +0x117
testing.tRunner(0xc00067dd40, 0x191c3e0)
	/usr/local/go/src/testing/testing.go:991 +0xdc
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1042 +0x357
```

#### :x: Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_cert_renew_test.go:30
Timed out after 300.000s.
Expected
    <bool>: false
to be true
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_cert_renew_test.go:120
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement defined in CR

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:67
Unexpected error:
    <*errors.errorString | 0xc000743200>: {
        s: "the MCO CR did not have observabilityAddonSpec.resources spec configed",
    }
    the MCO CR did not have observabilityAddonSpec.resources spec configed
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:70
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement in metrics-collector

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:79
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc000293e00>: {
        s: "metrics-collector-deployment resource <{map[] map[cpu:{{100 -3} {<nil>} 100m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{209715200 0} {<nil>}  BinarySI}]}>",
    }
    metrics-collector-deployment resource <{map[] map[cpu:{{100 -3} {<nil>} 100m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{209715200 0} {<nil>}  BinarySI}]}>
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:83
```

#### :x: Observability: [P2][Sev2][Observability][Integration] Checking resources in advanced config (config/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_advanced_config_test.go:122
Test Panicked
/usr/local/go/src/runtime/iface.go:260

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/observability-e2e-test/pkg/tests.glob..func4.3()
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_advanced_config_test.go:137 +0x18a8
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc0000ad320, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc0000ad320, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:64 +0xcf
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc000401680, 0x1aa88c0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/it_node.go:26 +0x64
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc00045e3c0, 0x0, 0x1aa88c0, 0xc0000ae900)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:215 +0x638
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc00045e3c0, 0x1aa88c0, 0xc0000ae900)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc0003c9b80, 0xc00045e3c0, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:200 +0x10f
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc0003c9b80, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:170 +0x120
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc0003c9b80, 0xc000409748)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc0000fa070, 0x7fac6fe20208, 0xc00067dd40, 0x1879298, 0x17, 0xc000401420, 0x2, 0x2, 0x1af7260, 0xc0000ae900, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/suite/suite.go:79 +0x586
github.com/onsi/ginkgo.RunSpecsWithCustomReporters(0x1aa9de0, 0xc00067dd40, 0x1879298, 0x17, 0xc000401400, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:229 +0x217
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1aa9de0, 0xc00067dd40, 0x1879298, 0x17, 0xc000141f60, 0x1, 0x1, 0xc000141f70)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:217 +0xad
github.com/open-cluster-management/observability-e2e-test/pkg/tests.TestObservabilityE2E(0xc00067dd40)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:94 +0x117
testing.tRunner(0xc00067dd40, 0x191c3e0)
	/usr/local/go/src/testing/testing.go:991 +0xdc
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1042 +0x357
```

#### :x: Observability: [P2][Sev2][Observability][Integration] Should have metrics which defined in custom metrics allowlist (metricslist/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_metricslist_test.go:32
Timed out after 600.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0007d7170>: {
        s: "Failed to find metric name from response",
    }
    Failed to find metric name from response
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_metricslist_test.go:42
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:131
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc00069b9f0>: {
        s: "the storage size of statefulset alertmanager should have 2Gi but got {{10737418240 0} {<nil>} 10Gi BinarySI}",
    }
    the storage size of statefulset alertmanager should have 2Gi but got {{10737418240 0} {<nil>} 10Gi BinarySI}
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:144
```

