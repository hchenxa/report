# :warning: Had some failures when running regression on cluster qe1-vmware-pkt with test snapshot 2.4.0-SNAPSHOT-2021-10-02-11-10-03 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/287/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-rc.1

Hub Cluster: https://multicloud-console.apps.qe1-vmware-pkt.dev02.red-chesterfield.com

Managed Cluster Version: 4.9.0-rc.4

Managed Cluster: https://console-openshift-console.apps.qe4-vmware-pkt.dev02.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110041741/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted |
| :x: | failed | Observability: [P1][Sev1][Observability][Integration] Checking replicas in advanced config for each component (config/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana_dev/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Stable] Checking default value of PVC and StorageClass (config/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the alertmanager configured in rule (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Modifying MCO cr to enable observabilityaddon |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement defined in CR |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement in metrics-collector |
| :x: | failed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should not have the expected MCO addon pods when disable observabilityaddon |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Waiting for check no metric data in grafana console |
| :x: | failed | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Stable] Modifying managedcluster cr to disable observability |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Stable] Remove disable observability label from the managed cluster |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Deleting metrics-collector deployment |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - [Stable] Updating metrics-collector deployment |
| :x: | failed | Observability: [P2][Sev2][Observability][Integration] Checking resources in advanced config (config/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Integration] Should have metrics which defined in custom metrics allowlist (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics after custom metrics allowlist deleted (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in matches section (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in names section (metrics/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check compact args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check receive args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check rule args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check store args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0) |
| :x: | failed | Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |
| :x: | failed | Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0) |


---

### Failed Test Details

#### :x: Observability: [P1][Sev1][Observability][Integration] Checking replicas in advanced config for each component (config/g0)

```
/workspace/tests/pkg/tests/observability_config_test.go:146
Test Panicked
/workspace/tests/pkg/tests/observability_config_test.go:150

Panic: multiclusterobservabilities.observability.open-cluster-management.io "observability" not found

Full stack:
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.glob..func6.4()
	/workspace/tests/pkg/tests/observability_config_test.go:150 +0x9a9
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.TestObservabilityE2E(0x0)
	/workspace/tests/pkg/tests/observability-e2e-test_suite_test.go:98 +0xf9
testing.tRunner(0xc0000931e0, 0x2155a68)
	/usr/local/go/src/testing/testing.go:1259 +0x102
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1306 +0x35a
```

#### :x: Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0)

```
/workspace/tests/pkg/tests/observability_certrenew_test.go:30
Timed out after 300.001s.
Expected
    <bool>: false
to be true
/workspace/tests/pkg/tests/observability_certrenew_test.go:144
```

#### :x: Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana_dev/g0)

```
/workspace/tests/pkg/tests/observability_grafana_dev_test.go:21
Unexpected error:
    <*fs.PathError | 0xc00050f350>: {
        Op: "fork/exec",
        Path: "../../grafana-dev-test.sh",
        Err: <syscall.Errno>0x2,
    }
    fork/exec ../../grafana-dev-test.sh: no such file or directory
occurred
/workspace/tests/pkg/tests/observability_grafana_dev_test.go:27
```

#### :x: Observability: [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0)

```
/workspace/tests/pkg/tests/observability_grafana_test.go:28
Timed out after 360.234s.
Expected success, but got an error:
    <*errors.errorString | 0xc000752830>: {
        s: "Failed to find metric name from response",
    }
    Failed to find metric name from response
/workspace/tests/pkg/tests/observability_grafana_test.go:42
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Modifying MCO cr to enable observabilityaddon

```
/workspace/tests/pkg/tests/observability_addon_test.go:92
Timed out after 60.003s.
Expected success, but got an error:
    <*errors.StatusError | 0xc0007c5180>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "multiclusterobservabilities.observability.open-cluster-management.io \"observability\" not found",
            Reason: "NotFound",
            Details: {
                Name: "observability",
                Group: "observability.open-cluster-management.io",
                Kind: "multiclusterobservabilities",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    multiclusterobservabilities.observability.open-cluster-management.io "observability" not found
/workspace/tests/pkg/tests/observability_addon_test.go:95
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement defined in CR

```
/workspace/tests/pkg/tests/observability_addon_test.go:36
Unexpected error:
    <*errors.StatusError | 0xc00070e280>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "multiclusterobservabilities.observability.open-cluster-management.io \"observability\" not found",
            Reason: "NotFound",
            Details: {
                Name: "observability",
                Group: "observability.open-cluster-management.io",
                Kind: "multiclusterobservabilities",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    multiclusterobservabilities.observability.open-cluster-management.io "observability" not found
occurred
/workspace/tests/pkg/tests/observability_addon_test.go:39
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should have resource requirement in metrics-collector

```
/workspace/tests/pkg/tests/observability_addon_test.go:48
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc00071ea80>: {
        s: "metrics-collector-deployment resource <{map[] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}>",
    }
    metrics-collector-deployment resource <{map[] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}>
/workspace/tests/pkg/tests/observability_addon_test.go:52
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should not have the expected MCO addon pods when disable observabilityaddon

```
/workspace/tests/pkg/tests/observability_addon_test.go:55
Timed out after 60.000s.
Expected success, but got an error:
    <*errors.StatusError | 0xc00058b9a0>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "multiclusterobservabilities.observability.open-cluster-management.io \"observability\" not found",
            Reason: "NotFound",
            Details: {
                Name: "observability",
                Group: "observability.open-cluster-management.io",
                Kind: "multiclusterobservabilities",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    multiclusterobservabilities.observability.open-cluster-management.io "observability" not found
/workspace/tests/pkg/tests/observability_addon_test.go:58
```

#### :x: Observability: [P2][Sev2][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - [Stable] Modifying managedcluster cr to disable observability

```
/workspace/tests/pkg/tests/observability_addon_test.go:142
Timed out after 300.001s.
Expected
    <bool>: false
to be true
/workspace/tests/pkg/tests/observability_addon_test.go:154
```

#### :x: Observability: [P2][Sev2][Observability][Integration] Checking resources in advanced config (config/g0)

```
/workspace/tests/pkg/tests/observability_config_test.go:182
Test Panicked
/workspace/tests/pkg/tests/observability_config_test.go:185

Panic: multiclusterobservabilities.observability.open-cluster-management.io "observability" not found

Full stack:
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.glob..func6.5()
	/workspace/tests/pkg/tests/observability_config_test.go:185 +0x124a
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.TestObservabilityE2E(0x0)
	/workspace/tests/pkg/tests/observability-e2e-test_suite_test.go:98 +0xf9
testing.tRunner(0xc0000931e0, 0x2155a68)
	/usr/local/go/src/testing/testing.go:1259 +0x102
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1306 +0x35a
```

#### :x: Observability: [P2][Sev2][Observability][Integration] Should have metrics which defined in custom metrics allowlist (metrics/g0)

```
/workspace/tests/pkg/tests/observability_metrics_test.go:46
Timed out after 600.001s.
Expected success, but got an error:
    <*errors.errorString | 0xc00001c290>: {
        s: "Failed to find metric name from response",
    }
    Failed to find metric name from response
/workspace/tests/pkg/tests/observability_metrics_test.go:62
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check compact args (retention/g0):

```
/workspace/tests/pkg/tests/observability_retention_test.go:29
Test Panicked
/workspace/tests/pkg/tests/observability_retention_test.go:41

Panic: multiclusterobservabilities.observability.open-cluster-management.io "observability" not found

Full stack:
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.glob..func15.1()
	/workspace/tests/pkg/tests/observability_retention_test.go:41 +0x84a
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.TestObservabilityE2E(0x0)
	/workspace/tests/pkg/tests/observability-e2e-test_suite_test.go:98 +0xf9
testing.tRunner(0xc0000931e0, 0x2155a68)
	/usr/local/go/src/testing/testing.go:1259 +0x102
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1306 +0x35a
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check receive args (retention/g0):

```
/workspace/tests/pkg/tests/observability_retention_test.go:29
Test Panicked
/workspace/tests/pkg/tests/observability_retention_test.go:41

Panic: multiclusterobservabilities.observability.open-cluster-management.io "observability" not found

Full stack:
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.glob..func15.1()
	/workspace/tests/pkg/tests/observability_retention_test.go:41 +0x84a
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.TestObservabilityE2E(0x0)
	/workspace/tests/pkg/tests/observability-e2e-test_suite_test.go:98 +0xf9
testing.tRunner(0xc0000931e0, 0x2155a68)
	/usr/local/go/src/testing/testing.go:1259 +0x102
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1306 +0x35a
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check rule args (retention/g0):

```
/workspace/tests/pkg/tests/observability_retention_test.go:29
Test Panicked
/workspace/tests/pkg/tests/observability_retention_test.go:41

Panic: multiclusterobservabilities.observability.open-cluster-management.io "observability" not found

Full stack:
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.glob..func15.1()
	/workspace/tests/pkg/tests/observability_retention_test.go:41 +0x84a
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.TestObservabilityE2E(0x0)
	/workspace/tests/pkg/tests/observability-e2e-test_suite_test.go:98 +0xf9
testing.tRunner(0xc0000931e0, 0x2155a68)
	/usr/local/go/src/testing/testing.go:1259 +0x102
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1306 +0x35a
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Check store args (retention/g0):

```
/workspace/tests/pkg/tests/observability_retention_test.go:29
Test Panicked
/workspace/tests/pkg/tests/observability_retention_test.go:41

Panic: multiclusterobservabilities.observability.open-cluster-management.io "observability" not found

Full stack:
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.glob..func15.1()
	/workspace/tests/pkg/tests/observability_retention_test.go:41 +0x84a
github.com/open-cluster-management/multicluster-observability-operator/tests/pkg/tests.TestObservabilityE2E(0x0)
	/workspace/tests/pkg/tests/observability-e2e-test_suite_test.go:98 +0xf9
testing.tRunner(0xc0000931e0, 0x2155a68)
	/usr/local/go/src/testing/testing.go:1259 +0x102
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1306 +0x35a
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0)

```
/workspace/tests/pkg/tests/observability_reconcile_test.go:130
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc00070a840>: {
        s: "the storage size of statefulset observability-alertmanager should have 2Gi but got {{1073741824 0} {<nil>} 1Gi BinarySI}",
    }
    the storage size of statefulset observability-alertmanager should have 2Gi but got {{1073741824 0} {<nil>} 1Gi BinarySI}
/workspace/tests/pkg/tests/observability_reconcile_test.go:143
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0)

```
/workspace/tests/pkg/tests/observability_reconcile_test.go:99
Unexpected error:
    <*errors.StatusError | 0xc00058b040>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "multiclusterobservabilities.observability.open-cluster-management.io \"observability\" not found",
            Reason: "NotFound",
            Details: {
                Name: "observability",
                Group: "observability.open-cluster-management.io",
                Kind: "multiclusterobservabilities",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    multiclusterobservabilities.observability.open-cluster-management.io "observability" not found
occurred
/workspace/tests/pkg/tests/observability_reconcile_test.go:102
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0)

```
/workspace/tests/pkg/tests/observability_reconcile_test.go:43
Unexpected error:
    <*errors.StatusError | 0xc00042e280>: {
        ErrStatus: {
            TypeMeta: {Kind: "Status", APIVersion: "v1"},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "multiclusterobservabilities.observability.open-cluster-management.io \"observability\" not found",
            Reason: "NotFound",
            Details: {
                Name: "observability",
                Group: "observability.open-cluster-management.io",
                Kind: "multiclusterobservabilities",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    multiclusterobservabilities.observability.open-cluster-management.io "observability" not found
occurred
/workspace/tests/pkg/tests/observability_reconcile_test.go:46
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:122
Timed out after 600.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc00070b620>: {
        s: "The observability-thanos-rule is not being restarted in 10 minutes",
    }
    The observability-thanos-rule is not being restarted in 10 minutes
/workspace/tests/pkg/tests/observability_alert_test.go:156
```

#### :x: Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:73
Unexpected error:
    <*errors.errorString | 0xc0005500f0>: {
        s: "thanos-ruler-custom-rules exist within the namespace env",
    }
    thanos-ruler-custom-rules exist within the namespace env
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:79
```

#### :x: Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0)

```
/workspace/tests/pkg/tests/observability_addon_test.go:117
Timed out after 60.003s.
Expected
    <bool>: false
to be true
/workspace/tests/pkg/tests/observability_addon_test.go:127
```

