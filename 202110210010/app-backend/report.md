# :warning: Had some failures when running regression on cluster ocp-bm-e20-h31-0 with test snapshot 2.4.0-SNAPSHOT-2021-09-23-08-29-45 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/352/


ACM Version: v2.4.0

Hub Cluster Version: 4.8.12

Hub Cluster: https://multicloud-console.apps.ocp-bm-e20-h31-0.qe.lab.redhat.com

Managed Cluster Version: 4.8.12

Managed Cluster: https://console-openshift-console.apps.ocp-bm-e20-h31-1.qe.lab.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110210010/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :white_check_mark: | passed | channel-test chn-001 |
| :white_check_mark: | passed | channel-test chn-002 |
| :x: | failed | channel-test chn-003 |
| :x: | failed | channel-test chn-004 |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :x: | failed | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |
| :x: | failed | helmrelease-test RHACM4K-1680 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-1701 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-1732 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-2346 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-2347 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-2348 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-2352 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-2566 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-2568 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-2569 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-2570 |
| :white_check_mark: | passed | helmrelease-test RHACM4K-2585 |
| :white_check_mark: | passed | subscription-test Test subscription with Git commit |
| :white_check_mark: | passed | subscription-test Test subscription with Git release tag |
| :white_check_mark: | passed | subscription-test sub-001 |
| :white_check_mark: | passed | subscription-test sub-002 |


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

#### :x: channel-test chn-003

```
/opt/e2e/client/e2e_client/e2e_client_test.go:56
Timed out after 108.417s.
Expected success, but got an error:
    <*errors.errorString | 0xc0007be1f0>: {
        s: "failed test on chn-003, with status failed err: failed",
    }
    failed test on chn-003, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:57
```

#### :x: channel-test chn-004

```
/opt/e2e/client/e2e_client/e2e_client_test.go:59
Timed out after 108.275s.
Expected success, but got an error:
    <*errors.errorString | 0xc0007bef80>: {
        s: "failed test on chn-004, with status failed err: failed",
    }
    failed test on chn-004, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:60
```

#### :x: e2e-server [P1][Sev1][app-lifecycle] Test argocd integration

```
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:10
Expected
    <int>: 1
to equal
    <int>: 0
/opt/e2e/client/canary/e2e_canary_argocd_integration_test.go:13
```

#### :x: helmrelease-test RHACM4K-1680

```
/opt/e2e/client/e2e_client/e2e_client_test.go:12
Timed out after 108.474s.
Expected success, but got an error:
    <*errors.errorString | 0xc000399930>: {
        s: "failed test on RHACM4K-1680, with status failed err: failed",
    }
    failed test on RHACM4K-1680, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:13
```

