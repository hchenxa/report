# :warning: Had some failures when running regression on cluster ocp4-edge-bm-h29-0 with test snapshot 2.3.0-SNAPSHOT-2021-07-15-17-21-39 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/automation-sample-job-test/237/


ACM Version: v2.3.0

Hub Cluster Version: 4.7.16

Hub Cluster: https://multicloud-console.apps.ocp4-edge-bm-h29-0.qe.lab.redhat.com

Managed Cluster Version: 4.7.16

Managed Cluster: https://console-openshift-console.apps.ocp4-edge-bm-h29-1.qe.lab.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107200724/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :x: | failed | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |


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

#### :x: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate

```
/opt/e2e/client/canary/e2e_canary_git_custom_cert_test.go:10
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_git_custom_cert_test.go:12
```

