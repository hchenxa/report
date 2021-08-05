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
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana-dev/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Checking default value of PVC and StorageClass (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Modifying MCO cr to enable observabilityaddon |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have endpoint-operator and metrics-collector being deployed |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should not have the expected MCO addon pods when disable observabilityaddon |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Waiting for check no metric data in grafana console |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Integration] Modifying managedcluster cr to disable observability |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Integration] Modifying managedcluster cr to enable observability |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Deleting metrics-collector deployment |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Updating metrics-collector deployment |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Customize the replicas for thanos query (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have metrics which defined in custom metrics allowlist (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have no metrics after custom metrics allowlist deleted (metricslist/g0) |
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

#### :x: Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana-dev/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_grafana_dev_test.go:19
Timed out after 600.000s.
Expected success, but got an error:
    <*os.PathError | 0xc00029e5a0>: {
        Op: "fork/exec",
        Path: "../../cicd-scripts/grafana-dev-test.sh",
        Err: 0x2,
    }
    fork/exec ../../cicd-scripts/grafana-dev-test.sh: no such file or directory
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_grafana_dev_test.go:29
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:115
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0004d2bd0>: {
        s: "the storage size of statefulset observability-alertmanager should have 2Gi but got {{3221225472 0} {<nil>} 3Gi BinarySI}",
    }
    the storage size of statefulset observability-alertmanager should have 2Gi but got {{3221225472 0} {<nil>} 3Gi BinarySI}
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:123
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:93
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0003846a0>: {
        s: "Failed to check node selector for pod: observability-alertmanager-0",
    }
    Failed to check node selector for pod: observability-alertmanager-0
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:101
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Customize the replicas for thanos query (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:126
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc000730bd0>: {
        s: "The replicas was not updated successfully",
    }
    The replicas was not updated successfully
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:133
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:51
Test Panicked
/usr/local/go/src/runtime/iface.go:260

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/observability-e2e-test/pkg/utils.ModifyMCOCR(0x0, 0x0, 0x0, 0x0, 0x0, 0xc000041350, 0x29, 0x0, 0x0, 0x0, ...)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/utils/mco_deploy.go:562 +0x4c9
github.com/open-cluster-management/observability-e2e-test/pkg/tests.glob..func14.2()
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:53 +0x9b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc00027c360, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc00027c360, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:64 +0xcf
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc00043ad40, 0x1a8f3e0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/it_node.go:26 +0x64
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc000360780, 0x0, 0x1a8f3e0, 0xc00011c900)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:215 +0x638
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc000360780, 0x1a8f3e0, 0xc00011c900)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc0000e5cc0, 0xc000360780, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:200 +0x10f
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc0000e5cc0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:170 +0x120
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc0000e5cc0, 0xc0005742c0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc000178070, 0x7f94db6e6220, 0xc0006b2000, 0x1868ab6, 0x17, 0xc0006a4400, 0x2, 0x2, 0x1addd00, 0xc00011c900, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/suite/suite.go:79 +0x586
github.com/onsi/ginkgo.RunSpecsWithCustomReporters(0x1a90900, 0xc0006b2000, 0x1868ab6, 0x17, 0xc0006a43e0, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:229 +0x217
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1a90900, 0xc0006b2000, 0x1868ab6, 0x17, 0xc000053f60, 0x1, 0x1, 0xc000053f70)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:217 +0xad
github.com/open-cluster-management/observability-e2e-test/pkg/tests.TestObservabilityE2E(0xc0006b2000)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:91 +0x117
testing.tRunner(0xc0006b2000, 0x190b000)
	/usr/local/go/src/testing/testing.go:991 +0xdc
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1042 +0x357
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:162
Test Panicked
/usr/local/go/src/runtime/iface.go:260

Panic: interface conversion: interface {} is nil, not map[string]interface {}

Full stack:
github.com/open-cluster-management/observability-e2e-test/pkg/utils.RevertMCOCRModification(0x0, 0x0, 0x0, 0x0, 0x0, 0xc000041350, 0x29, 0x0, 0x0, 0x0, ...)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/utils/mco_deploy.go:585 +0x3fa
github.com/open-cluster-management/observability-e2e-test/pkg/tests.glob..func14.7()
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:165 +0x9b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc00027c780, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc00027c780, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/runner.go:64 +0xcf
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc00043b200, 0x1a8f3e0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/leafnodes/it_node.go:26 +0x64
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc000360c30, 0x0, 0x1a8f3e0, 0xc00011c900)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:215 +0x638
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc000360c30, 0x1a8f3e0, 0xc00011c900)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc0000e5cc0, 0xc000360c30, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:200 +0x10f
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc0000e5cc0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:170 +0x120
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc0000e5cc0, 0xc0005742c0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc000178070, 0x7f94db6e6220, 0xc0006b2000, 0x1868ab6, 0x17, 0xc0006a4400, 0x2, 0x2, 0x1addd00, 0xc00011c900, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/internal/suite/suite.go:79 +0x586
github.com/onsi/ginkgo.RunSpecsWithCustomReporters(0x1a90900, 0xc0006b2000, 0x1868ab6, 0x17, 0xc0006a43e0, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:229 +0x217
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1a90900, 0xc0006b2000, 0x1868ab6, 0x17, 0xc000053f60, 0x1, 0x1, 0xc000053f70)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.14.2/ginkgo_dsl.go:217 +0xad
github.com/open-cluster-management/observability-e2e-test/pkg/tests.TestObservabilityE2E(0xc0006b2000)
	/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:91 +0x117
testing.tRunner(0xc0006b2000, 0x190b000)
	/usr/local/go/src/testing/testing.go:991 +0xdc
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1042 +0x357
```

