# :warning: Had some failures when running regression on cluster ocp-edge-e25-h13-0 with test snapshot 2.4.0-SNAPSHOT-2021-11-01-21-39-01 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/407/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.4

Hub Cluster: https://multicloud-console.apps.ocp-edge-e25-h13-0.qe.lab.redhat.com

Managed Cluster Version: 4.9.4

Managed Cluster: https://console-openshift-console.apps.ocp-edge-e25-h13-1.qe.lab.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202111021603/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :x: | failed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :x: | failed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :x: | failed | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |
| :x: | failed | e2e-subscription-admin-test [P1][Sev1][app-lifecycle] Test nested subscriptions with subscription admin |


---

### Failed Test Details

#### :x: RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication

```
/opt/e2e/client/canary/e2e_canary_helmrepo_basicath_test.go:10
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_helmrepo_basicath_test.go:13
```

#### :x: e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit

```
/opt/e2e/client/canary/e2e_subscription_test.go:12
Timed out after 48.421s.
Expected success, but got an error:
    <*errors.errorString | 0xc00058a6b0>: {
        s: "failed test on sub-004, with status failed err: failed",
    }
    failed test on sub-004, with status failed err: failed
/opt/e2e/client/canary/e2e_subscription_test.go:13
```

#### :x: e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag

```
/opt/e2e/client/canary/e2e_subscription_test.go:9
Timed out after 48.507s.
Expected success, but got an error:
    <*errors.errorString | 0xc0003ee4a0>: {
        s: "failed test on sub-003, with status failed err: failed",
    }
    failed test on sub-003, with status failed err: failed
/opt/e2e/client/canary/e2e_subscription_test.go:10
```

#### :x: e2e-server [P1][Sev1][app-lifecycle] Test argocd integration

```
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:10
Expected
    <int>: -1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:13
```

#### :x: e2e-subscription-admin-test [P1][Sev1][app-lifecycle] Test nested subscriptions with subscription admin

```
/opt/e2e/client/canary/e2e_canary_subscription_admin_test.go:10
Expected
    <int>: -1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_subscription_admin_test.go:12
```

