# :warning: Had some failures when running regression on cluster ocp4-az-01 with test snapshot 2.4.0-SNAPSHOT-2021-10-25-23-58-51 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/362/


ACM Version: v2.4.0

Hub Cluster Version: 4.6.46

Hub Cluster: https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.8.11

Managed Cluster: https://console-openshift-console.apps.acmqe-24-rc-hive-aws.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110270148/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Observability: @BVT - [P1][Sev1][Observability][Integration] Checking replicas in advanced config for each component (config/g0) |
| :large_blue_circle: | skipped | Observability: @BVT - [P1][Sev1][Observability][Stable] Checking default value of PVC and StorageClass (config/g0) |
| :large_blue_circle: | skipped | Observability: @BVT - [P1][Sev1][Observability][Stable] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | passed | Observability: @BVT - [P1][Sev1][Observability][Stable] Should have metric data in grafana console (grafana/g0) |
| :white_check_mark: | passed | Observability: @BVT - [P1][Sev1][Observability][Stable] Should have the alertmanager configured in rule (alert/g0) |
| :white_check_mark: | passed | Observability: @BVT - [P1][Sev1][Observability][Stable] Should have the expected secret (alert/g0) |
| :white_check_mark: | passed | Observability: @BVT - [P1][Sev1][Observability][Stable] Should have the expected statefulsets (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - [Stable] Updating observatorium cr (spec.thanos.compact.retentionResolution1h) should be automatically reverted |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability][Integration] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana_dev/g0) |
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
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have metrics which defined in custom metrics allowlist (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics after custom metrics allowlist deleted (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in matches section (metrics/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Integration] Should have no metrics which have been marked for deletion in names section (metrics/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check compact args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check receive args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check rule args (retention/g0): |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Check store args (retention/g0): |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Checking alertmanager storage resize (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Checking podAntiAffinity for all pods (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Modifying MCO CR for reconciling (reconcile/g0) |
| :large_blue_circle: | skipped | Observability: [P2][Sev2][Observability][Stable] Revert MCO CR changes (reconcile/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert generated (alert/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have the expected configmap (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability][Stable] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :x: | failed | Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0) |
| :white_check_mark: | passed | Observability: [P3][Sev3][Observability][Stable] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |
| :x: | failed | Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0) |


---

### Failed Test Details

#### :x: Observability: @BVT - [P1][Sev1][Observability][Integration] Checking replicas in advanced config for each component (config/g0)

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
testing.tRunner(0xc00020ab60, 0x2155db8)
	/usr/local/go/src/testing/testing.go:1259 +0x102
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1306 +0x35a
```

#### :x: Observability: [P1][Sev1][Observability][Integration] Should run grafana-dev test successfully (grafana_dev/g0)

```
/workspace/tests/pkg/tests/observability_grafana_dev_test.go:21
Unexpected error:
    <*fs.PathError | 0xc00085a240>: {
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
Timed out after 60.000s.
Expected success, but got an error:
    <*errors.StatusError | 0xc000826960>: {
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
    <*errors.StatusError | 0xc00043a640>: {
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
Timed out after 300.001s.
Expected success, but got an error:
    <*errors.errorString | 0xc0008464e0>: {
        s: "metrics-collector-deployment resource <{map[] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}>",
    }
    metrics-collector-deployment resource <{map[] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}> is not equal <{map[cpu:{{200 -3} {<nil>} 200m DecimalSI} memory:{{734003200 0} {<nil>} 700Mi BinarySI}] map[cpu:{{10 -3} {<nil>} 10m DecimalSI} memory:{{104857600 0} {<nil>} 100Mi BinarySI}]}>
/workspace/tests/pkg/tests/observability_addon_test.go:52
```

#### :x: Observability: [P2][Sev2][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - [Stable] Should not have the expected MCO addon pods when disable observabilityaddon

```
/workspace/tests/pkg/tests/observability_addon_test.go:55
Timed out after 60.001s.
Expected success, but got an error:
    <*errors.StatusError | 0xc000826dc0>: {
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
Timed out after 300.002s.
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
testing.tRunner(0xc00020ab60, 0x2155db8)
	/usr/local/go/src/testing/testing.go:1259 +0x102
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1306 +0x35a
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
testing.tRunner(0xc00020ab60, 0x2155db8)
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
testing.tRunner(0xc00020ab60, 0x2155db8)
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
testing.tRunner(0xc00020ab60, 0x2155db8)
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
testing.tRunner(0xc00020ab60, 0x2155db8)
	/usr/local/go/src/testing/testing.go:1259 +0x102
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1306 +0x35a
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Checking node selector for all pods (reconcile/g0)

```
/workspace/tests/pkg/tests/observability_reconcile_test.go:99
Unexpected error:
    <*errors.StatusError | 0xc0006c8140>: {
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
    <*errors.StatusError | 0xc0008266e0>: {
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
    <*errors.errorString | 0xc0005d4560>: {
        s: "statefulset observability-thanos-rule should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-rule should have 3 but got 2 ready replicas
/workspace/tests/pkg/tests/observability_alert_test.go:156
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should have custom alert updated (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc000bdca70>: {
        s: "statefulset observability-thanos-rule should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-rule should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: [P2][Sev2][Observability][Stable] Should modify the SECRET: alertmanager-config (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:240
Unexpected error:
    <*errors.errorString | 0xc0005d46c0>: {
        s: "statefulset observability-thanos-rule should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-rule should have 3 but got 2 ready replicas
occurred
/workspace/tests/pkg/tests/observability_alert_test.go:241
```

#### :x: Observability: [P2][Sev2][Observability][Stable] delete the customized rules (alert/g0)

```
/workspace/tests/pkg/tests/observability_alert_test.go:201
Timed out after 600.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0006e9630>: {
        s: "statefulset observability-thanos-rule should have 3 but got 2 ready replicas",
    }
    statefulset observability-thanos-rule should have 3 but got 2 ready replicas
/workspace/tests/pkg/tests/observability_alert_test.go:235
```

#### :x: Observability: [P3][Sev3][Observability][Stable] Should not set interval to values beyond scope (addon/g0)

```
/workspace/tests/pkg/tests/observability_addon_test.go:117
Timed out after 60.000s.
Expected
    <bool>: false
to be true
/workspace/tests/pkg/tests/observability_addon_test.go:127
```

