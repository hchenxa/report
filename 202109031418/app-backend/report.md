# :warning: Had some failures when running regression on cluster ocp49-interop with test snapshot 2.4.0-SNAPSHOT-2021-08-31-23-32-56 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/267/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-0.nightly-2021-09-01-193941

Hub Cluster: https://multicloud-console.apps.ocp49-interop.dev09.red-chesterfield.com

Managed Cluster Version: 4.9.0-fc.1

Managed Cluster: https://console-openshift-console.apps.clc-cluster-functional-49-fc1.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202109031418/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :x: | failed | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


---

### Failed Test Details

#### :x: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate

```
/opt/e2e/client/canary/e2e_canary_git_custom_cert_test.go:10
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_git_custom_cert_test.go:12
```

