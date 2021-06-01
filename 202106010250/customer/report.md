# :warning: Had some failures when running regression on cluster acmqeosd with test snapshot 2.2.3-SNAPSHOT-2021-04-22-06-59-29 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/125/


ACM Version: v2.2.3

Hub Cluster Version: 4.5.30

Hub Cluster: https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com

Managed Cluster Version: v1.18.3+65bd32d

Managed Cluster: https://console-openshift-console.apps.acmqeosd.y0wn.p1.openshiftapps.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202106010250/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator |
| :white_check_mark: | passed |  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-sample |
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
| :x: | failed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be compliant |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on hub |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be created on managed cluster |
| :white_check_mark: | passed |  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator community/policy-gatekeeper-operator should be noncompliant |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Validate invalid input Test "before all" hook for "Verify invalid input is rejected" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table "before all" hook for "get the number of the managed OCP clusters" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "[P1][Sev1][app-lifecycle-ui] Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Verify that the apps ui-git subscription and placementrule no longer exist - git: ui-git" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Verify it deletes namespace ui-git-ns on hub cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before all" hook for "[P2][Sev2][app-lifecycle-ui] Try to delete channel with insecureSkipVerify option for application ui-git" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before all" hook for "Verify first subscription can be deleted for app ui-git" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before all" hook for "get the name of the managed OCP cluster" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before all" hook for "Verify that settings for application ui-git are properly shown in the app Editor" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test "before all" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`" |
| :x: | failed | Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation" |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Check nonexistent URLs |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Create, Search, Verify details of policy |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Delete test policy |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Verify duplicate policy creation in different NS |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Verify stability of YAML |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] All policy page: Verify summary table |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] Create policy page: Check policy name RegEx |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] Create policy page: Updating YAML in editor |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] Disable policy: test policy disable + enable |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1622521176 status to become available |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Clean up |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide admin user |
| :x: | failed | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide cluster-admin user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide edit user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide view user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide view user in a group |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced admin user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced cluster-admin user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced edit user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced view user |
| :large_blue_circle: | skipped | GRC UI: [P1][Sev1][policy-grc] RBAC: Namespaced view user in a group |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Check that policy role-binding-cleanup-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Delete policy role-binding-cleanup-policy-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Verify that policy role-binding-cleanup-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Wait for role-binding-cleanup-policy-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Check that policy role-specification-cleanup-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Delete policy role-specification-cleanup-policy-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Verify that policy role-specification-cleanup-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Wait for role-specification-cleanup-policy-1622521176 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Check that policy scc-cleanup-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Delete policy scc-cleanup-policy-1622521176 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Verify that policy scc-cleanup-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Wait for scc-cleanup-policy-1622521176 status to become available |
| :x: | failed | Observability: [P1][Sev1][Observability] Checking default value of PVC and StorageClass (config/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Checking metrics default values on managed cluster (config/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability] Checking node selector for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Checking podAntiAffinity for all pods (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO CR for reconciling (reconcile/g0) |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Modifying MCO cr to enable observabilityaddon |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Should have endpoint-operator and metrics-collector being deployed |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Should not have the expected MCO addon pods when disable observabilityaddon |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying MCO cr to disable observabilityaddon (addon/g0) - Waiting for check no metric data in grafana console |
| :white_check_mark: | passed | Observability: [P1][Sev1][Observability] Modifying retentionResolutionRaw (reconcile/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability] Revert MCO CR changes (reconcile/g0) |
| :x: | failed | Observability: [P1][Sev1][Observability] Should have custom alert generated (alert/g0) |
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
| :x: | failed | RHACM4K-1695: Search - verify managed cluster info in the search page Search - verify managed cluster info in the search page. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind application on specific namespace. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod and namespace open-cluster-management. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind pod on specific cluster. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:certpolicycontroller. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Search kind:iampolicycontroller. |
| :white_check_mark: | passed | RHACM4K-1696: Search - Verify search result with common filter and conditions Verify a deleted pod is recreated. |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by active |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by apigroup |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by apiversion |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by architecture |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by available |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by capacity |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by claimRef |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by cluster |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by clusterIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by completions |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by consoleURL |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by container |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by cpu |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by created |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by current |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by desired |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by hostIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by kubernetesVersion |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by lastSchedule |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by memory |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by nodes |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by osImage |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by parallelism |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by podIP |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by port |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by ready |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by reclaimPolicy |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by request |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by restarts |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by startedAt |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by successful |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by suspend |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by type |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by updated |
| :white_check_mark: | passed | RHACM4K-1709: Search - Search using filters should filter by volumeName |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1622521176 using the form |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1622521176 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 details at the detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 template details at the detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1622521176 cluster local-cluster template test-iam-policy-1622521176-limit-clusteradmin |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1622521176 cluster rhacmqeosd template test-iam-policy-1622521176-limit-clusteradmin |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1622521176 status to become available |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1622521176 using the form |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1622521176 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 details at the detailed page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 template details at the detailed page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1622521176 cluster local-cluster template test-pod-security-policy-1622521176-restricted-psp |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1622521176 cluster rhacmqeosd template test-pod-security-policy-1622521176-restricted-psp |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1622521176 status to become available |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check disabled policy test-role-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that enforced policy test-role-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that policy test-role-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Create new policy test-role-policy-1622521176 using the form |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Deleted policy test-role-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Disable policy test-role-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enable policy test-role-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enforce policy test-role-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Policy test-role-policy-1622521176 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 details at the detailed page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 template details at the detailed page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 violations at the Status - Templates page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1622521176 cluster local-cluster template test-role-policy-1622521176-deployments-role |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1622521176 cluster rhacmqeosd template test-role-policy-1622521176-deployments-role |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1622521176 status to become available |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check disabled policy test-role-binding-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that enforced policy test-role-binding-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that policy test-role-binding-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Create new policy test-role-binding-policy-1622521176 using the form |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Deleted policy test-role-binding-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Disable policy test-role-binding-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enable policy test-role-binding-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enforce policy test-role-binding-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Policy test-role-binding-policy-1622521176 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 details at the detailed page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 template details at the detailed page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1622521176 cluster local-cluster template test-role-binding-policy-1622521176-operatoruser-rolebinding |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1622521176 cluster rhacmqeosd template test-role-binding-policy-1622521176-operatoruser-rolebinding |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for policy test-role-binding-policy-1622521176 status to become available |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check disabled policy test-security-context-constraints-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that enforced policy test-security-context-constraints-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that policy test-security-context-constraints-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Create new policy test-security-context-constraints-policy-1622521176 using the form |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Deleted policy test-security-context-constraints-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Disable policy test-security-context-constraints-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enable policy test-security-context-constraints-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enforce policy test-security-context-constraints-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Policy test-security-context-constraints-policy-1622521176 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 details at the detailed page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 template details at the detailed page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 violations at the Status - Templates page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1622521176 cluster local-cluster template test-security-context-constraints-policy-1622521176-restricted-scc |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1622521176 cluster rhacmqeosd template test-security-context-constraints-policy-1622521176-restricted-scc |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for policy test-security-context-constraints-policy-1622521176 status to become available |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1622521176 using the form |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1622521176 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 details at the detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 template details at the detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1622521176 cluster local-cluster template test-pod-policy-1622521176-nginx-pod |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1622521176 cluster rhacmqeosd template test-pod-policy-1622521176-nginx-pod |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1622521176 status to become available |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1622521176 |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1622521176 using the form |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1622521176 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy details & templates on cluster local-cluster detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 details at the detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 template details at the detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1622521176 cluster local-cluster template test-namespace-policy-1622521176-prod-ns |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1622521176 cluster rhacmqeosd template test-namespace-policy-1622521176-prod-ns |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1622521176 status to become available |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1622521176 using the form |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1622521176 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 details at the detailed page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 template details at the detailed page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 violations at the Status - Templates page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1622521176 cluster local-cluster template test-limitrange-policy-1622521176-container-mem-limit-range |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1622521176 cluster rhacmqeosd template test-limitrange-policy-1622521176-container-mem-limit-range |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1622521176 status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy test-imagemanifest-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy test-imagemanifest-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy test-imagemanifest-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy test-imagemanifest-policy-1622521176 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy test-imagemanifest-policy-1622521176 using the form |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy test-imagemanifest-policy-1622521176 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy test-imagemanifest-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy test-imagemanifest-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy test-imagemanifest-policy-1622521176 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy test-imagemanifest-policy-1622521176 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622521176 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622521176 placement binding details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622521176 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622521176 template details at the detailed page |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622521176 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622521176 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622521176 cluster local-cluster template test-imagemanifest-policy-1622521176-image-vulnerability |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622521176 cluster local-cluster template test-imagemanifest-policy-1622521176-image-vulnerability-sub |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622521176 cluster rhacmqeosd template test-imagemanifest-policy-1622521176-image-vulnerability |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622521176 cluster rhacmqeosd template test-imagemanifest-policy-1622521176-image-vulnerability-sub |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy test-imagemanifest-policy-1622521176 status to become available |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance operator |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up after all clean up compliance scan e8 |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance operator |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Clean up before all clean up compliance scan e8 |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Compliance operator pod should be running |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Enforcing stable/policy-comp-operator |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Informing stable/policy-comp-operator |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator Profile bundle pods should be running |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator clean up in case the last build failed |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be compliant |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on hub |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be created on managed cluster |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-comp-operator stable/policy-comp-operator should be noncompliant |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceCheckResult should be created |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be AGGREGATING |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 scan results should be DONE |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan ComplianceSuite e8 should be created |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Enforcing stable/policy-e8-scan |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan Informing stable/policy-e8-scan |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on hub |
| :large_blue_circle: | skipped | RHACM4K-2222 GRC: [P1][Sev1][policy-grc] Test compliance operator and scan Test stable/policy-e8-scan stable/policy-e8-scan should be created on managed cluster |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance "Govern risk" page can be launched. |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-1622521176 status becomes available |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy-create-certificate-1622521176 status becomes available |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created certificate policy-create-certificate-1622521176 is not present |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1622521176 is not present |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1622521176 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create an expiring certificate policy-create-certificate-1622521176 in the managed cluster. |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-1622521176 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1622521176 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Navigated to "Govern risk" page and clicked at "Create policy" |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created certificate policy-create-certificate-1622521176 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-1622521176 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1622521176 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1622521176 |
| :x: | failed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1622521176 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1622521176 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate yaml of created policy policy-certificatepolicy-1622521176 from edit YAML action |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1622521176 on the "Govern and risk" page |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance "Govern risk" page can be launched. |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1622521176 status becomes available |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy-create-certificate-1622521176 status becomes available |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created certificate policy-create-certificate-1622521176 is not present |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1622521176 is not present |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1622521176 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create an expiring certificate policy-create-certificate-1622521176 in the managed cluster. |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1622521176 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1622521176 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Navigated to "Govern risk" page and clicked at "Create policy" |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created certificate policy-create-certificate-1622521176 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-rhacm4k-1205-1622521176 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1622521176 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1622521176 |
| :x: | failed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1622521176 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1622521176 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate yaml of created policy policy-certificatepolicy-rhacm4k-1205-1622521176 from edit YAML action |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1622521176 on the "Govern and risk" page |
| :white_check_mark: | passed | Search API: Validate autocomplete [P3][Sev3][search][PLACEHOLDER] This test not yet implemented. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][search] should get 401 if authorization header is incorrect. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][search] should get 401 if authorization header is not present. |
| :white_check_mark: | passed | Search API: Verify access: [P1][Sev1][search] should return results when searching for kind:pod. |
| :white_check_mark: | passed | [P0][sev1][kui]Visual Web Terminal: Verify user path for rbash |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify KUI multiple tabs |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify kubectl |
| :x: | failed | [P1][sev1][kui]Visual Web Terminal: Verify oc |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify supported CLIs can execute |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify user home folder permissions |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify KUI getting started command |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify commands are disabled - rbash |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify product header |
| :x: | failed | [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus |
| :white_check_mark: | passed | [P2][sev3][kui]Visual Web Terminal: Verify supported themes |


---

### Failed Test Details

#### :x:  GRC: [P1][Sev1][policy-grc] Clean up after all Clean up community/policy-gatekeeper-operator

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:305
Expected
    <string>: Error from server (NotFound): namespaces "openshift-gatekeeper-operator" not found
    
to contain substring
    <string>: namespace "openshift-gatekeeper-operator" deleted
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:316
```

#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample Creating an invalid ns should generate a violation message

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:250
Timed out after 60.134s.
Expected
    <string>: Error from server (AlreadyExists): namespaces "e2etestfail" already exists
    
to contain substring
    <string>: denied by ns-must-have-gk
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:256
```

#### :x:  RHACM4K-1274/RHACM4K-1282 GRC: [P1][Sev1][policy-grc] Test community/policy-gatekeeper-sample community/policy-gatekeeper-sample should be compliant

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:220
Timed out after 180.000s.
Expected
    <v1.ComplianceState>: NonCompliant
to equal
    <v1.ComplianceState>: Compliant
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:234
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper audit pod should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:158
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 1
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:164
```

#### :x:  RHACM4K-1692 GRC: [P1][Sev1][policy-grc] Test installing gatekeeper operator Gatekeeper controller manager pods should be running

```
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:173
Timed out after 60.000s.
Expected
    <int>: 0
to equal
    <int>: 2
/go/src/github.com/open-cluster-management/governance-policy-framework/test/policy-collection/policy_gatekeeper_operator_test.go:179
```

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

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Test "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Creation Validate invalid input Test "before all" hook for "Verify invalid input is rejected"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for advanced configuration tables "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for applications table "before all" hook for "get the number of the managed OCP clusters"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application Validation Test for single application page, topology  "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application application backend resources exist "before all" hook for "[P1][Sev1][app-lifecycle-ui] Verify that the apps ui-git channels, subscription and placementrule are valid - git: ui-git"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Application backend validation that app hub resources have been removed "before all" hook for "Verify that the apps ui-git subscription and placementrule no longer exist - git: ui-git"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Cleanup resouces Test "before all" hook for "Verify it deletes namespace ui-git-ns on hub cluster"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Delete application Test "before all" hook for "[P2][Sev2][app-lifecycle-ui] Try to delete channel with insecureSkipVerify option for application ui-git"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application delete subscription Test "before all" hook for "Verify first subscription can be deleted for app ui-git"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application insert new subscription Test "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate delete first subscription "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Edit application validate insert new subscription "before all" hook for "get the name of the managed OCP cluster"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui] Verify application settings on Editor "before all" hook for "Verify that settings for application ui-git are properly shown in the app Editor"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Application Creation Test "before all" hook for "Skipping RBAC Test as of Now to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Delete application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Edit application subscription Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P1][Sev1][app-lifecycle-ui][RBAC] Validate view application Test "before all" hook for "Skipping RBAC Test to execute test set export CYPRESS_RBAC_TEST=`true`"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: Application UI: [P2][Sev2][app-lifecycle-ui] Application UI Tables "before all" hook for "maintain their state across SPA navigation"

```
CypressError: `cy.exec('oc login --server=https://api.acmqeosd.y0wn.p1.openshiftapps.com:6443 -u kubeadmin -p Acm22QEOSD')` failed because the command exited with a non-zero code.

Pass `{failOnNonZeroExit: false}` to ignore exit code failures.

Information about the failure:
Code: 1

Stderr:
Error from server (InternalError): Internal error occurred: unexpected response: 500

https://on.cypress.io/exec

Because this error occurred during a `before all` hook we are skipping all of the remaining tests.

Although you have test retries enabled, we do not retry tests when `before all` or `after all` hooks fail
    at https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:157540:26
    at tryCatcher (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:10765:23)
    at Promise._settlePromiseFromHandler (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8700:31)
    at Promise._settlePromise (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8757:18)
    at Promise._settlePromise0 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8802:10)
    at Promise._settlePromises (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:8882:18)
    at _drainQueueStep (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5472:12)
    at _drainQueue (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5465:9)
    at Async.../../node_modules/bluebird/js/release/async.js.Async._drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5481:5)
    at Async.drainQueues (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/runner/cypress_runner.js:5351:14)
From Your Spec Code:
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=cypress/support/index.js:1363:6)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates

```
    at NightwatchAPI.<anonymous> (/opt/app-root/src/grc-ui/tests/page-objects/AllPolicyPage.js:335:12)
    at processTicksAndRejections (internal/process/task_queues.js:97:5)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] Disable policy: test policy disable + enable

```
    at Page.createPolicy (/opt/app-root/src/grc-ui/tests/page-objects/CommonPage.js:105:8)
    at Object.GRC UI: [P1][Sev1][policy-grc] Disable policy: test policy disable + enable (/opt/app-root/src/grc-ui/tests/e2e/disable.test.js:32:10)
```

#### :x: GRC UI: [P1][Sev1][policy-grc] RBAC: Cluster-wide cluster-admin user

```
    at Page.logout (/opt/app-root/src/grc-ui/tests/page-objects/LoginPage.js:114:8)
    at Object.beforeEach (/opt/app-root/src/grc-ui/tests/e2e/rbac.test.js:56:15)
    at new Promise (<anonymous>)
```

#### :x: Observability: [P1][Sev1][Observability] Checking default value of PVC and StorageClass (config/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_default_config_test.go:37
Timed out after 180.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc00059f190>: {
        s: "PVC check failed, pvcSize = 1Gi, sizeInCR = 10Gi, scName = gp2, expectedSC = gp2, statusPhase = Bound",
    }
    PVC check failed, pvcSize = 1Gi, sizeInCR = 10Gi, scName = gp2, expectedSC = gp2, statusPhase = Bound
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_default_config_test.go:78
```

#### :x: Observability: [P1][Sev1][Observability] Checking node selector for all pods (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:72
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc0001f7640>: {
        s: "Failed to check node selector for pod: observability-observatorium-thanos-query-66cc749d99-744nd",
    }
    Failed to check node selector for pod: observability-observatorium-thanos-query-66cc749d99-744nd
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:80
```

#### :x: Observability: [P1][Sev1][Observability] Revert MCO CR changes (reconcile/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:94
Timed out after 600.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc000374730>: {
        s: "Expect 3 but got 2 ready replicas",
    }
    Expect 3 but got 2 ready replicas
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_reconcile_test.go:109
```

#### :x: Observability: [P1][Sev1][Observability] Should have custom alert generated (alert/g0)

```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:85
Timed out after 300.000s.
Expected success, but got an error:
    <*errors.errorString | 0xc000a40a00>: {
        s: "Failed to find metric name from response",
    }
    Failed to find metric name from response
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_alert_test.go:103
```

#### :x: RHACM4K-1695: Search - verify managed cluster info in the search page Search - verify managed cluster info in the search page.

```
Error: expect(received).toEqual(expected) // deep equality

Expected: "Running"
Received: "Pending"
    at forEach (/tests/api/search.test.js:45:30)
    at Array.forEach (<anonymous>)
    at Object.<anonymous> (/tests/api/search.test.js:44:10)
    at processTicksAndRejections (internal/process/task_queues.js:94:5)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy details & templates on cluster local-cluster detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16417:32)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page

```
AssertionError: expected 0 to equal 1
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16315:37)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:15587:24)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16026:26)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:15665:26)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/NonCompliant; Number of users with clusteradmin role is [0-9]+ above the specified limit/' within the element: <td.pf-m-break-word> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16134:34)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622521176 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16260:37)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1622521176 cluster rhacmqeosd template test-iam-policy-1622521176-limit-clusteradmin

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/Number of users with clusteradmin role is [0-9]+ above the specified limit/' within the element: [ <td.pf-m-break-word>, 5 more... ] but never did.
    at _loop10 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16448:22)
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16455:9)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy details & templates on cluster local-cluster detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:16414:32)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622521176 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622521176 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1622521176 cluster local-cluster template test-role-policy-1622521176-deployments-role

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:16447:30)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy details & templates on cluster local-cluster detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:16414:32)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622521176 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622521176 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1622521176 cluster local-cluster template test-security-context-constraints-policy-1622521176-restricted-scc

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:16447:30)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy details & templates on cluster local-cluster detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:16414:32)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622521176 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1622521176

```
AssertionError: Timed out retrying after 30000ms: expected '1/2' to match /^0\/2$/
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:15251:41)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy details & templates on cluster rhacmqeosd detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/test-namespace-policy-1622521176-prod-ns: Compliant/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16331:30)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^0\/2$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:15532:29)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16026:26)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `svg[fill="#467f40"]`, but never found it. Queried from element: <div.table-status-row>
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:15652:82)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/Compliant/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16117:38)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622521176 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/Compliant/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16241:40)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1622521176 cluster rhacmqeosd template test-namespace-policy-1622521176-prod-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/notification - namespaces \[prod\] found as specified, therefore this Object template is compliant/' within the element: [ <td.pf-m-break-word>, 8 more... ] but never did.
    at _loop10 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16448:22)
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16455:9)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1622521176 status to become available

```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2249:13)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:15588:24)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:16027:26)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:15666:26)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:16139:35)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622521176 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:16261:37)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1622521176 cluster local-cluster template test-limitrange-policy-1622521176-container-mem-limit-range

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:16451:30)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622521176 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/ImageManifest_governance.spec.js:16146:35)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622521176 cluster rhacmqeosd template test-imagemanifest-policy-1622521176-image-vulnerability

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/violation - couldn't find mapping resource with kind ImageManifestVuln, please check if you have CRD deployed/' within the element: [ <td.pf-m-break-word>, 29 more... ] but never did.
    at _loop10 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/ImageManifest_governance.spec.js:16456:22)
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/ImageManifest_governance.spec.js:16463:9)
```

#### :x: RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1622521176 on the detailed policy page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/CertPolicy_governance.spec.js:15422:24)
```

#### :x: RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1622521176 on the detailed policy page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/CertPolicy_governance.spec.js:15422:24)
```

#### :x: [P1][sev1][kui]Visual Web Terminal: Verify oc

```
    at Page.executeCommand (/usr/src/app/tests/page-objects/KUI.js:106:16)
    at Object.[P1][sev1][kui]Visual Web Terminal: Verify oc (/usr/src/app/tests/e2e/cli.test.js:59:9)
```

#### :x: [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus

```
    at Page.clear (/usr/src/app/tests/page-objects/Prometheus.js:115:10)
    at Page.queryMetric (/usr/src/app/tests/page-objects/Prometheus.js:92:30)
    at Object.[P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus (/usr/src/app/tests/e2e/verifyMetricsInPrometheus.test.js:22:18)
```

