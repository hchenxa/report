# :warning: Had some failures when running regression on cluster ocp4-az-01 with test snapshot 2.4.0-SNAPSHOT-2021-10-25-23-58-51 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/363/


ACM Version: v2.4.0

Hub Cluster Version: 4.6.46

Hub Cluster: https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.8.11

Managed Cluster: https://console-openshift-console.apps.acmqe-24-rc-hive-aws.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110270441/

## Tests:

|Status|Results|Test|
|---|---|---|
| :large_blue_circle: | skipped | Observability: @BVT - [P1][Sev1][Observability][Integration] Checking replicas in advanced config for each component (config/g0) |
| :large_blue_circle: | skipped | Observability: @BVT - [P1][Sev1][Observability][Stable] Checking default value of PVC and StorageClass (config/g0) |
| :large_blue_circle: | skipped | Observability: @BVT - [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | passed | Observability: @BVT - [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0) |
| :x: | failed | Observability: @BVT - [P1][Sev1][Observability][Stable] Should have the alertmanager configured in rule (alert/g0) |
| :x: | failed | Observability: @BVT - [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0) |
| :x: | failed | Observability: @BVT - [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted |
| :x: | failed | Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana_dev/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Modifying MCO cr to enable observabilityaddon |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement defined in CR |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement in metrics-collector |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should not have the expected MCO addon pods when disable observabilityaddon |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Waiting for check no metric data in grafana console |
| :x: | failed | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Stable] Modifying managedcluster cr to disable observability |
| :x: | failed | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Stable] Remove disable observability label from the managed cluster |
| :x: | failed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Deleting metrics-collector deployment |
| :x: | failed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Updating metrics-collector deployment |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Integration] Checking resources in advanced config (config/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Integration] Should have metrics which defined in custom metrics allowlist (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics after custom metrics allowlist deleted (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in matches section (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in names section (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Check compact args (retention/g0): |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Check receive args (retention/g0): |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Check rule args (retention/g0): |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Check store args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0) |
| :x: | failed | Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |
| :x: | failed | Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0) |


---

### Failed Test Details

#### :x: Observability: @BVT - [P1][Sev1][Observability][Stable] Should have the alertmanager configured in rule (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc000735f20>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: @BVT - [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc0009052b0>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: @BVT - [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc000525010>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0)

```
/workspace/tests/pkg/tests/observability_certrenew_test.go:147
Unexpected error:
    <*errors.errorString | 0xc000524670>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_certrenew_test.go:148
```

#### :x: Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana_dev/g0)

```
/workspace/tests/pkg/tests/observability_grafana_dev_test.go:21
Unexpected error:
    <*fs.PathError | 0xc000710b70>: {
        Op: "fork/exec",
        Path: "../../grafana-dev-test.sh",
        Err: <syscall.Errno>0x2,
    }
    fork/exec ../../grafana-dev-test.sh: no such file or directory
occurred
/workspace/tests/pkg/tests/observability_grafana_dev_test.go:27
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Modifying MCO cr to enable observabilityaddon

```
/workspace/tests/pkg/tests/observability_addon_test.go:92
Timed out after 1200.002s.
Expected success, but got an error:
    <*errors.errorString | 0xc0006a12c0>: {
        s: "observability-addon is not ready for managed cluster acmqe-24-rc-hive-aws",
    }
    observability-addon is not ready for managed cluster acmqe-24-rc-hive-aws
/workspace/tests/pkg/tests/observability_addon_test.go:113
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement defined in CR

```
/workspace/tests/pkg/tests/observability_addon_test.go:36
Unexpected error:
    <*errors.errorString | 0xc000904350>: {
        s: "the MCO CR did not have observabilityAddonSpec.resources spec configed",
    }
    the MCO CR did not have observabilityAddonSpec.resources spec configed
occurred
/workspace/tests/pkg/tests/observability_addon_test.go:39
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement in metrics-collector

```
/workspace/tests/pkg/tests/observability_addon_test.go:48
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc000124e60>: {
        s: "metrics-collector-deployment resource <{map[] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}>",
    }
    metrics-collector-deployment resource <{map[] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}>
/workspace/tests/pkg/tests/observability_addon_test.go:52
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should not have the expected MCO addon pods when disable observabilityaddon

```
/workspace/tests/pkg/tests/observability_addon_test.go:173
Unexpected error:
    <*errors.errorString | 0xc0002a8e20>: {
        s: "statefulset observability-alertmanager should have 3 but got 2 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_addon_test.go:174
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Waiting for check no metric data in grafana console

```
/workspace/tests/pkg/tests/observability_addon_test.go:173
Unexpected error:
    <*errors.errorString | 0xc0008f03f0>: {
        s: "statefulset observability-alertmanager should have 3 but got 2 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_addon_test.go:174
```

#### :x: Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Stable] Modifying managedcluster cr to disable observability

```
/workspace/tests/pkg/tests/observability_addon_test.go:142
Timed out after 300.000s.
Expected
    <bool>: false
to be true
/workspace/tests/pkg/tests/observability_addon_test.go:154
```

#### :x: Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Stable] Remove disable observability label from the managed cluster

```
/workspace/tests/pkg/tests/observability_addon_test.go:173
Unexpected error:
    <*errors.errorString | 0xc0009a3090>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_addon_test.go:174
```

#### :x: Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Deleting metrics-collector deployment

```
/workspace/tests/pkg/tests/observability_endpoint_preserve_test.go:152
Unexpected error:
    <*errors.errorString | 0xc00063b0c0>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_endpoint_preserve_test.go:153
```

#### :x: Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Updating metrics-collector deployment

```
/workspace/tests/pkg/tests/observability_endpoint_preserve_test.go:152
Unexpected error:
    <*errors.errorString | 0xc000650c80>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_endpoint_preserve_test.go:153
```

#### :x: Observability: [P2][Sev2][Observability][Integration] Should have metrics which defined in custom metrics allowlist (metrics/g0)

```
/workspace/tests/pkg/tests/observability_metrics_test.go:46
Timed out after 600.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0008f0e60>: {
        s: "Failed to find metric name from response",
    }
    Failed to find metric name from response
/workspace/tests/pkg/tests/observability_metrics_test.go:62
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0)

```
/workspace/tests/pkg/tests/observability_reconcile_test.go:196
Unexpected error:
    <*errors.errorString | 0xc0002a9bc0>: {
        s: "statefulset observability-alertmanager should have 3 but got 0 ready replicas",
    }
    statefulset observability-alertmanager should have 3 but got 0 ready replicas
occurred
/workspace/tests/pkg/tests/observability_reconcile_test.go:197
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0)

```
/workspace/tests/pkg/tests/observability_reconcile_test.go:196
Unexpected error:
    <*errors.errorString | 0xc000525bf0>: {
        s: "should have statefulset created with label app=multicluster-observability-alertmanager",
    }
    should have statefulset created with label app=multicluster-observability-alertmanager
occurred
/workspace/tests/pkg/tests/observability_reconcile_test.go:197
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc0005e95b0>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc000735b70>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0)

```
/workspace/tests/pkg/tests/observability_dashboard_test.go:67
Unexpected error:
    <*errors.errorString | 0xc000125070>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_dashboard_test.go:68
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0)

```
/workspace/tests/pkg/tests/observability_dashboard_test.go:67
Unexpected error:
    <*errors.errorString | 0xc000735590>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_dashboard_test.go:68
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc0008204d0>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should have update custom dashboard after configmap updated (dashboard/g0)

```
/workspace/tests/pkg/tests/observability_dashboard_test.go:67
Unexpected error:
    <*errors.errorString | 0xc0005e8a20>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_dashboard_test.go:68
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc0009a3360>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0)

```
/workspace/tests/pkg/tests/observability_endpoint_preserve_test.go:152
Unexpected error:
    <*errors.errorString | 0xc000125680>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_endpoint_preserve_test.go:153
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0)

```
/workspace/tests/pkg/tests/observability_endpoint_preserve_test.go:152
Unexpected error:
    <*errors.errorString | 0xc000145b10>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_endpoint_preserve_test.go:153
```

#### :x: Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc0006d19a0>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc000144a30>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0)

```
/workspace/tests/pkg/tests/observability_addon_test.go:173
Unexpected error:
    <*errors.errorString | 0xc0006d4120>: {
        s: "statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-receive-default should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_addon_test.go:174
```

