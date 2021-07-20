# :warning: Had some failures when running regression on cluster ocp4-az-3 with test snapshot 2.3.0-SNAPSHOT-2021-07-19-17-01-34 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/239/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.13

Hub Cluster: https://multicloud-console.apps.ocp4-az-3.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.7.3

Managed Cluster: https://console-openshift-console.apps.acmqe-225-23-hive-before-upgrade.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107200915/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


---

### Failed Test Details

#### :x: RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication

```
/opt/e2e/client/canary/e2e_canary_helmrepo_basicath_test.go:11
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_helmrepo_basicath_test.go:14
```

