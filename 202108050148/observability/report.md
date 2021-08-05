# :white_check_mark: Passed when running regression on cluster ocp4-gcp-2 with test snapshot 2.2.6-SNAPSHOT-2021-07-24-01-04-04 

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
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Checking default value of PVC and StorageClass (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Checking metrics default values on managed cluster (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Checking podAntiAffinity for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO CR for reconciling (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Modifying MCO cr to enable observabilityaddon |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Should have endpoint-operator and metrics-collector being deployed |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Should not have the expected MCO addon pods when disable observabilityaddon |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Waiting for check no metric data in grafana console |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying retentionResolutionRaw (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Revert MCO CR changes (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should have custom alert generated (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should have custom alert updated (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should have custom dashboard which defined in configmap (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should have metric data in grafana console (grafana/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability] Should have metrics collector pod restart if cert secret re-generated (certrenew/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should have metrics which defined in custom metrics allowlist (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should have no custom dashboard in grafana after related configmap removed (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should have no metrics after custom metrics allowlist deleted (metricslist/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should have the expected statefulsets (alert/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should have update custom dashboard after configmap updated (dashboard/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should modify the SECRET: alertmanager-config (alert/g0) |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - Modifying managedcluster cr to disable observability |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability] Should not have the expected MCO addon pods when disable observability from managedcluster (addon/g0) - Modifying managedcluster cr to enable observability |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should not set interval to values beyond scope (addon/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should recreate on metrics-collector-serving-certs-ca-bundle configmap if deleted (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - Deleting metrics-collector deployment |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on metrics-collector deployment (endpoint_preserve/g0) - Updating metrics-collector deployment |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on metrics-collector-view clusterolebinding (endpoint_preserve/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Should revert any manual changes on observatorium cr (observatorium_preserve/g0) - Updating observatorium cr (spec.rule.replicas) should be automatically reverted |
| :large_blue_circle: | skipped | Observability: [P1][Sev1][Observability] Should verify that the alerts are created (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should delete the created configmap (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should have the expected configmap (alert/g0) |
| :white_check_mark: | passed | Observability: [P2][Sev2][Observability] Should have the expected secret (alert/g0) |
| :white_check_mark: | passed | Observability: [P3][Sev3][Observability] Should not have the CM: thanos-ruler-custom-rules (alert/g0) |


---

