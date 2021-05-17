# :red_circle: 2.3.0-SNAPSHOT-2021-05-04-05-27-18 Failed when running Regression on user environment

## Job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/104/


Hub Cluster Version: v2.3.0

Hub Cluster: https://multicloud-console.apps.acm-azgov-ocp4.groupfmag.azure.devcluster.openshift.com

Managed Cluster Version: 4.7.9

Managed Cluster: https://console-openshift-console.apps.acm-azgov-ocp4.groupfmag.azure.devcluster.openshift.com

## Tests:

|Results|Test|
|---|---|
| :x: | BeforeSuite |


---

### Failed Test Details

#### :x: BeforeSuite


```
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability-e2e-test_suite_test.go:95
Unexpected error:
    <*errors.StatusError | 0xc0001b5180>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "secrets \"multiclusterhub-operator-pull-secret\" already exists",
            Reason: "AlreadyExists",
            Details: {
                Name: "multiclusterhub-operator-pull-secret",
                Group: "",
                Kind: "secrets",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 409,
        },
    }
    secrets "multiclusterhub-operator-pull-secret" already exists
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_install_test.go:53
```
                        
