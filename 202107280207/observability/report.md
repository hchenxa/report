# :warning: Had some failures when running regression on cluster ocp4-aws-3 with test snapshot 2.3.0-SNAPSHOT-2021-07-26-18-43-26 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/245/


ACM Version: v2.3.0

Hub Cluster Version: 4.8.2

Hub Cluster: https://multicloud-console.apps.ocp4-aws-3.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.2

Managed Cluster: https://console-openshift-console.apps.acmqe-23-ocp4-aws-3-hive-azure.acm-dev06.azure.devcluster.openshift.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107280207/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Integration] Checking replicas in advanced config for each component (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana-dev/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Stable] Checking default value of PVC and StorageClass (config/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Stable] Should have the alertmanager configured in rule (alert/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0) |
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
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Integration] Checking resources in advanced config (config/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have metrics which defined in custom metrics allowlist (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics after custom metrics allowlist deleted (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in matches section (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in names section (metricslist/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check compact args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check receive args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check rule args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check store args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0) |
| :x: | failed | Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |
| :white_check_mark: | passed | Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0) |


---

### Failed Test Details

#### :x: Observability: [P1][Sev1][Observability][Stable] Should have the alertmanager configured in rule (alert/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:242
Unexpected error:
    <*errors.errorString | 0xc0004e56e0>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:243
```

#### :x: Observability: [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:242
Unexpected error:
    <*errors.errorString | 0xc000459930>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:243
```

#### :x: Observability: [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:242
Unexpected error:
    <*errors.errorString | 0xc000952690>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:243
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement defined in CR

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:67
Unexpected error:
    <*errors.errorString | 0xc0005bffd0>: {
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
    <*errors.errorString | 0xc00028b6f0>: {
        s: "metrics-collector-deployment resource <{map[] map[cpu:{{100 -3} {<nil>} 100m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{209715200 0} {<nil>}  BinarySI}]}>",
    }
    metrics-collector-deployment resource <{map[] map[cpu:{{100 -3} {<nil>} 100m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{209715200 0} {<nil>}  BinarySI}]}>
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_addon_test.go:83
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check compact args (retention/g0):

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:156
Unexpected error:
    <*errors.errorString | 0xc00049d200>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:157
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check receive args (retention/g0):

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:156
Unexpected error:
    <*errors.errorString | 0xc00054a550>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:157
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check rule args (retention/g0):

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:156
Unexpected error:
    <*errors.errorString | 0xc00028b630>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:157
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check store args (retention/g0):

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:156
Unexpected error:
    <*errors.errorString | 0xc0005dace0>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_retention_test.go:157
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:131
Expected
    <int>: 0
not to equal
    <int>: 0
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:136
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:198
Unexpected error:
    <*errors.errorString | 0xc000085990>: {
        s: "should have statefulset created with label app=multicluster-observability-alertmanager",
    }
    should have statefulset created with label app=multicluster-observability-alertmanager
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:199
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:242
Unexpected error:
    <*errors.errorString | 0xc0005dad30>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:243
```

#### :x: Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:242
Unexpected error:
    <*errors.errorString | 0xc000176d90>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:243
```

