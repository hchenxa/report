# :red_circle: 2.3.0-SNAPSHOT-2021-05-04-05-27-18 Failed when running Regression on user environment

## Job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/105/


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
    <*errors.errorString | 0xc000468120>: {
        s: "failed to get s3 BUCKET env",
    }
    failed to get s3 BUCKET env
occurred
/go/src/github.com/open-cluster-management/observability-e2e-test/pkg/tests/observability_install_test.go:54
```
                        
