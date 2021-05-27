# :warning: Had some failures when running regression on cluster acmqeosd with test snapshot 2.2.3-SNAPSHOT-2021-04-22-06-59-29 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/122/


ACM Version: v2.2.3

Hub Cluster Version: 4.5.30

Hub Cluster: https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com

Managed Cluster Version: v1.18.3+65bd32d

Managed Cluster: https://console-openshift-console.apps.acmqeosd.y0wn.p1.openshiftapps.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202105270309/

## Tests:

|Status|Results|Test|
|---|---|---|
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
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Check that policy policy-clusterrolebinding-delete-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Delete policy policy-clusterrolebinding-delete-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Verify that policy policy-clusterrolebinding-delete-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - cleanup Wait for policy-clusterrolebinding-delete-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Check that policy policy-clusterrolebinding-test-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Delete policy policy-clusterrolebinding-test-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Verify that policy policy-clusterrolebinding-test-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] IamPolicy governance - setup Wait for policy-clusterrolebinding-test-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Check that policy imagespec-cleanup-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Delete policy imagespec-cleanup-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Verify that policy imagespec-cleanup-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] ImageManifest governance - cleanup Wait for imagespec-cleanup-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Check that policy limitspec-setup-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Delete policy limitspec-setup-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Verify that policy limitspec-setup-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - clean up Wait for limitspec-setup-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Check that policy limitspec-setup-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Delete policy limitspec-setup-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Verify that policy limitspec-setup-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance - setup Wait for limitspec-setup-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Check that policy ns-spec-cleanup-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Delete policy ns-spec-cleanup-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Verify that policy ns-spec-cleanup-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - clean up Wait for ns-spec-cleanup-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Check that policy ns-spec-setup-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Delete policy ns-spec-setup-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Verify that policy ns-spec-setup-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Namespace policy governance - setup Wait for ns-spec-setup-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Check that policy pod-spec-cleanup-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Delete policy pod-spec-cleanup-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Verify that policy pod-spec-cleanup-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] Pod policy governance - clean up Wait for pod-spec-cleanup-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Check that policy pod-security-policy-cleanup-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Delete policy pod-security-policy-cleanup-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Verify that policy pod-security-policy-cleanup-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance - clean up Wait for pod-security-policy-cleanup-1622085082 status to become available |
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
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Check that policy role-binding-cleanup-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Delete policy role-binding-cleanup-policy-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Verify that policy role-binding-cleanup-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance - clean up Wait for role-binding-cleanup-policy-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Check that policy role-specification-cleanup-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Delete policy role-specification-cleanup-policy-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Verify that policy role-specification-cleanup-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] RolePolicy governance - clean up Wait for role-specification-cleanup-policy-1622085082 status to become available |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Check that policy scc-cleanup-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Create the clean up policy using the YAML |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Delete policy scc-cleanup-policy-1622085082 |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Verify that policy scc-cleanup-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance - clean up Wait for scc-cleanup-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check disabled policy test-iam-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check enabled policy test-iam-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that enforced policy test-iam-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Check that policy test-iam-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Create new policy test-iam-policy-1622085082 using the form |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Deleted policy test-iam-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Disable policy test-iam-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enable policy test-iam-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Enforce policy test-iam-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Policy test-iam-policy-1622085082 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 details at the detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 template details at the detailed page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1622085082 cluster local-cluster template test-iam-policy-1622085082-limit-clusteradmin |
| :x: | failed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1622085082 cluster rhacmqeosd template test-iam-policy-1622085082-limit-clusteradmin |
| :white_check_mark: | passed | RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Wait for policy test-iam-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check disabled policy test-pod-security-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check enabled policy test-pod-security-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that enforced policy test-pod-security-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Check that policy test-pod-security-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Create new policy test-pod-security-policy-1622085082 using the form |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Deleted policy test-pod-security-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Disable policy test-pod-security-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enable policy test-pod-security-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Enforce policy test-pod-security-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Policy test-pod-security-policy-1622085082 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 details at the detailed page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 template details at the detailed page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1622085082 cluster local-cluster template test-pod-security-policy-1622085082-restricted-psp |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify the History page for policy test-pod-security-policy-1622085082 cluster rhacmqeosd template test-pod-security-policy-1622085082-restricted-psp |
| :white_check_mark: | passed | RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Wait for policy test-pod-security-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check disabled policy test-role-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check enabled policy test-role-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that enforced policy test-role-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Check that policy test-role-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Create new policy test-role-policy-1622085082 using the form |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Deleted policy test-role-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Disable policy test-role-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enable policy test-role-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Enforce policy test-role-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Policy test-role-policy-1622085082 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 details at the detailed page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 template details at the detailed page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 violations at the Status - Templates page |
| :x: | failed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1622085082 cluster local-cluster template test-role-policy-1622085082-deployments-role |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1622085082 cluster rhacmqeosd template test-role-policy-1622085082-deployments-role |
| :white_check_mark: | passed | RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Wait for policy test-role-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check disabled policy test-role-binding-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check enabled policy test-role-binding-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that enforced policy test-role-binding-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Check that policy test-role-binding-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Create new policy test-role-binding-policy-1622085082 using the form |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Deleted policy test-role-binding-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Disable policy test-role-binding-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enable policy test-role-binding-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Enforce policy test-role-binding-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Policy test-role-binding-policy-1622085082 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 details at the detailed page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 template details at the detailed page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1622085082 cluster local-cluster template test-role-binding-policy-1622085082-operatoruser-rolebinding |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify the History page for policy test-role-binding-policy-1622085082 cluster rhacmqeosd template test-role-binding-policy-1622085082-operatoruser-rolebinding |
| :white_check_mark: | passed | RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Wait for policy test-role-binding-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check disabled policy test-security-context-constraints-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check enabled policy test-security-context-constraints-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that enforced policy test-security-context-constraints-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Check that policy test-security-context-constraints-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Create new policy test-security-context-constraints-policy-1622085082 using the form |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Deleted policy test-security-context-constraints-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Disable policy test-security-context-constraints-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enable policy test-security-context-constraints-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Enforce policy test-security-context-constraints-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Policy test-security-context-constraints-policy-1622085082 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 details at the detailed page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 template details at the detailed page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1622085082 cluster local-cluster template test-security-context-constraints-policy-1622085082-restricted-scc |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify the History page for policy test-security-context-constraints-policy-1622085082 cluster rhacmqeosd template test-security-context-constraints-policy-1622085082-restricted-scc |
| :white_check_mark: | passed | RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Wait for policy test-security-context-constraints-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check disabled policy test-pod-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check enabled policy test-pod-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that enforced policy test-pod-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Check that policy test-pod-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Create new policy test-pod-policy-1622085082 using the form |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Deleted policy test-pod-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Disable policy test-pod-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enable policy test-pod-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Enforce policy test-pod-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Policy test-pod-policy-1622085082 can be deleted in the policy listing |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 details at the detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 template details at the detailed page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1622085082 cluster local-cluster template test-pod-policy-1622085082-nginx-pod |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify the History page for policy test-pod-policy-1622085082 cluster rhacmqeosd template test-pod-policy-1622085082-nginx-pod |
| :white_check_mark: | passed | RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Wait for policy test-pod-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check disabled policy test-namespace-policy-1622085082 |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that enforced policy test-namespace-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check that policy test-namespace-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Create new policy test-namespace-policy-1622085082 using the form |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Deleted policy test-namespace-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Disable policy test-namespace-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enable policy test-namespace-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Enforce policy test-namespace-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Policy test-namespace-policy-1622085082 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy details & templates on cluster local-cluster detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 details at the detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 template details at the detailed page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1622085082 cluster local-cluster template test-namespace-policy-1622085082-prod-ns |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1622085082 cluster rhacmqeosd template test-namespace-policy-1622085082-prod-ns |
| :x: | failed | RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check disabled policy test-limitrange-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check enabled policy test-limitrange-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that enforced policy test-limitrange-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Check that policy test-limitrange-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Create new policy test-limitrange-policy-1622085082 using the form |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Deleted policy test-limitrange-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Disable policy test-limitrange-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enable policy test-limitrange-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Enforce policy test-limitrange-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Policy test-limitrange-policy-1622085082 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 details at the detailed page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 placement binding details at the detailed page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 template details at the detailed page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 violations at the Status - Clusters page |
| :x: | failed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1622085082 cluster local-cluster template test-limitrange-policy-1622085082-container-mem-limit-range |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify the History page for policy test-limitrange-policy-1622085082 cluster rhacmqeosd template test-limitrange-policy-1622085082-container-mem-limit-range |
| :white_check_mark: | passed | RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Wait for policy test-limitrange-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check disabled policy test-imagemanifest-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check enabled policy test-imagemanifest-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that enforced policy test-imagemanifest-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Check that policy test-imagemanifest-policy-1622085082 is present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Create new policy test-imagemanifest-policy-1622085082 using the form |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Deleted policy test-imagemanifest-policy-1622085082 is not present in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Disable policy test-imagemanifest-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enable policy test-imagemanifest-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Enforce policy test-imagemanifest-policy-1622085082 |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Policy test-imagemanifest-policy-1622085082 can be deleted in the policy listing |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy details & templates on cluster local-cluster detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy details & templates on cluster rhacmqeosd detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622085082 details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622085082 placement binding details at the detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622085082 placement rule at the detailed page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622085082 template details at the detailed page |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622085082 violations at the Status - Clusters page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622085082 violations at the Status - Templates page |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622085082 cluster local-cluster template test-imagemanifest-policy-1622085082-image-vulnerability |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622085082 cluster local-cluster template test-imagemanifest-policy-1622085082-image-vulnerability-sub |
| :x: | failed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622085082 cluster rhacmqeosd template test-imagemanifest-policy-1622085082-image-vulnerability |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622085082 cluster rhacmqeosd template test-imagemanifest-policy-1622085082-image-vulnerability-sub |
| :white_check_mark: | passed | RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Wait for policy test-imagemanifest-policy-1622085082 status to become available |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance "Govern risk" page can be launched. |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-1622085082 status becomes available |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy-create-certificate-1622085082 status becomes available |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created certificate policy-create-certificate-1622085082 is not present |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-1622085082 is not present |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-1622085082 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create an expiring certificate policy-create-certificate-1622085082 in the managed cluster. |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-1622085082 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-1622085082 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Navigated to "Govern risk" page and clicked at "Create policy" |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created certificate policy-create-certificate-1622085082 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-1622085082 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-1622085082 |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-1622085082 |
| :x: | failed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1622085082 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1622085082 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate yaml of created policy policy-certificatepolicy-1622085082 from edit YAML action |
| :white_check_mark: | passed | RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-1622085082 on the "Govern and risk" page |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance "Govern risk" page can be launched. |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy policy-certificatepolicy-rhacm4k-1205-1622085082 status becomes available |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Certificate policy-create-certificate-1622085082 status becomes available |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created certificate policy-create-certificate-1622085082 is not present |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check created policy policy-certificatepolicy-rhacm4k-1205-1622085082 is not present |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check disabled policy |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check enabled policy policy-certificatepolicy-rhacm4k-1205-1622085082 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Check violations stay reported but not remediated |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create an expiring certificate policy-create-certificate-1622085082 in the managed cluster. |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Create policy policy-certificatepolicy-rhacm4k-1205-1622085082 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Edit policy policy-certificatepolicy-rhacm4k-1205-1622085082 and change "remediateAction" to "enforce" |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Navigated to "Govern risk" page and clicked at "Create policy" |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created certificate policy-create-certificate-1622085082 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Remove created policy policy-certificatepolicy-rhacm4k-1205-1622085082 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate disable of the policy policy-certificatepolicy-rhacm4k-1205-1622085082 |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate enable of the policy policy-certificatepolicy-rhacm4k-1205-1622085082 |
| :x: | failed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1622085082 on the detailed policy page |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1622085082 on the policy status/history page |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate yaml of created policy policy-certificatepolicy-rhacm4k-1205-1622085082 from edit YAML action |
| :white_check_mark: | passed | RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Verify all information about the created certificate policy policy-certificatepolicy-rhacm4k-1205-1622085082 on the "Govern and risk" page |


---

### Failed Test Details

#### :x: GRC UI: [P1][Sev1][policy-grc] Create policy page: Verify templates

```
    at NightwatchAPI.<anonymous> (/opt/app-root/src/grc-ui/tests/page-objects/AllPolicyPage.js:335:12)
    at runMicrotasks (<anonymous>)
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

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy details & templates on cluster rhacmqeosd detailed page

```
AssertionError: expected 0 to equal 1
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16315:37)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:15587:24)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16026:26)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:15665:26)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/NonCompliant; Number of users with clusteradmin role is [0-9]+ above the specified limit/' within the element: <td.pf-m-break-word> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16134:34)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify policy test-iam-policy-1622085082 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16260:37)
```

#### :x: RHACM4K-1719 - GRC UI: [P1][Sev1][policy-grc] IamPolicy governance Verify the History page for policy test-iam-policy-1622085082 cluster rhacmqeosd template test-iam-policy-1622085082-limit-clusteradmin

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/Number of users with clusteradmin role is [0-9]+ above the specified limit/' within the element: [ <td.pf-m-break-word>, 5 more... ] but never did.
    at _loop10 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16448:22)
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/IamPolicy_governance.spec.js:16455:9)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1720 - GRC UI: [P1][Sev1][policy-grc] PodSecurityPolicy governance Verify policy test-pod-security-policy-1622085082 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/PodSecurityPolicy_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify policy test-role-policy-1622085082 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1721 - GRC UI: [P1][Sev1][policy-grc] RolePolicy governance Verify the History page for policy test-role-policy-1622085082 cluster local-cluster template test-role-policy-1622085082-deployments-role

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^(an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RolePolicy_governance.spec.js:16447:30)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy details & templates on cluster local-cluster detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:16414:32)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1722 - GRC UI: [P1][Sev1][policy-grc] RoleBindingPolicy governance Verify policy test-role-binding-policy-1622085082 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/RoleBindingPolicy_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1723 - GRC UI: [P1][Sev1][policy-grc] SecurityContextConstraintsPolicy governance Verify policy test-security-context-constraints-policy-1622085082 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/SCCPolicy_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy details & templates on cluster local-cluster detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:16414:32)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:15584:24)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:16023:26)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:15662:26)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:16135:35)
```

#### :x: RHACM4K-1724 - GRC UI: [P1][Sev1][policy-grc] Pod policy governance Verify policy test-pod-policy-1622085082 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Pod_governance.spec.js:16257:37)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Check enabled policy test-namespace-policy-1622085082

```
AssertionError: Timed out retrying after 30000ms: expected '1/2' to match /^0\/2$/
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:15251:41)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy details & templates on cluster rhacmqeosd detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/test-namespace-policy-1622085082-prod-ns: Compliant/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16331:30)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^0\/2$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:15532:29)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16026:26)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `svg[fill="#467f40"]`, but never found it. Queried from element: <div.table-status-row>
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:15652:82)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/Compliant/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16117:38)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify policy test-namespace-policy-1622085082 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/Compliant/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16241:40)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Verify the History page for policy test-namespace-policy-1622085082 cluster rhacmqeosd template test-namespace-policy-1622085082-prod-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/notification - namespaces \[prod\] found as specified, therefore this Object template is compliant/' within the element: [ <td.pf-m-break-word>, 8 more... ] but never did.
    at _loop10 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16448:22)
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/Namespace_governance.spec.js:16455:9)
```

#### :x: RHACM4K-1725 - GRC UI: [P1][Sev1][policy-grc] Namespace policy governance Wait for policy test-namespace-policy-1622085082 status to become available

```
Error: Timed out retrying
    at Context.check (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/support/index.js:2249:13)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:15588:24)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 placement binding details at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:16027:26)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 placement rule at the detailed page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.bx--structured-list-td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:15666:26)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:16139:35)
```

#### :x: RHACM4K-1726 - GRC UI: [P1][Sev1][policy-grc] LimitRange policy governance Verify policy test-limitrange-policy-1622085082 violations at the Status - Templates page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/LimitRange_governance.spec.js:16261:37)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify policy test-imagemanifest-policy-1622085082 violations at the Status - Clusters page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <td> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/ImageManifest_governance.spec.js:16146:35)
```

#### :x: RHACM4K-1727 - GRC UI: [P1][Sev1][policy-grc] ImageManifest policy governance Verify the History page for policy test-imagemanifest-policy-1622085082 cluster rhacmqeosd template test-imagemanifest-policy-1622085082-image-vulnerability

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/violation - couldn't find mapping resource with kind ImageManifestVuln, please check if you have CRD deployed/' within the element: [ <td.pf-m-break-word>, 29 more... ] but never did.
    at _loop10 (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/ImageManifest_governance.spec.js:16456:22)
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/ImageManifest_governance.spec.js:16463:9)
```

#### :x: RHACM4K-523/524/525/526/527/528/563/659/663/893/894/895/1567 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-1622085082 on the detailed policy page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/CertPolicy_governance.spec.js:15422:24)
```

#### :x: RHACM4K_1205 - GRC UI: [P1][Sev1][policy-grc] - CertificatePolicy governance Validate violations/status of created policy policy-certificatepolicy-rhacm4k-1205-1622085082 on the detailed policy page

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: '/^((an?|[0-9]+) (days?|hours?|minutes?|few seconds) ago|in a few seconds)$/' within the element: <div.pf-c-description-list__text> but never did.
    at Context.eval (https://multicloud-console.apps.acmqeosd.y0wn.p1.openshiftapps.com/__cypress/tests?p=tests/cypress/tests/CertPolicy_governance.spec.js:15422:24)
```

