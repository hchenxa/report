# :red_circle: Failed when running regression on cluster ocp4-azgov-3 with test snapshot 2.3.0-SNAPSHOT-2021-07-13-04-59-11 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/232/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.16

Hub Cluster: https://multicloud-console.apps.ocp4-azgov-3.groupfmag.azure.devcluster.openshift.com

Managed Cluster Version: 4.7.19

Managed Cluster: https://console-openshift-console.apps.dh-az4.acm-dev06.azure.devcluster.openshift.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107130709/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | BeforeSuite |


---

### Failed Test Details

#### :x: BeforeSuite

```
/opt/e2e/client/canary/e2e_canary_app_backend_suite_test.go:52
Timed out
/opt/e2e/client/canary/e2e_canary_app_backend_suite_test.go:52
```

