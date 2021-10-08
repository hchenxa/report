# :warning: Had some failures when running regression on cluster ocp-rosa-4 with test snapshot 2.4.0-SNAPSHOT-2021-10-02-11-10-03 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/308/


ACM Version: v2.4.0

Hub Cluster Version: 4.8.11

Hub Cluster: https://multicloud-console.apps.ocp-rosa-4.3zxv.p1.openshiftapps.com

Managed Cluster Version: 4.7.32

Managed Cluster: https://console-openshift-console.apps.acmqe-24-hive-aws.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110080136/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :white_check_mark: | passed | channel-test chn-001 |
| :white_check_mark: | passed | channel-test chn-002 |
| :x: | failed | channel-test chn-003 |
| :x: | failed | channel-test chn-004 |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
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

#### :x: channel-test chn-003

```
/opt/e2e/client/e2e_client/e2e_client_test.go:56
Timed out after 114.623s.
Expected success, but got an error:
    <*errors.errorString | 0xc0007c1b20>: {
        s: "failed test on chn-003, with status failed err: failed",
    }
    failed test on chn-003, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:57
```

#### :x: channel-test chn-004

```
/opt/e2e/client/e2e_client/e2e_client_test.go:59
Timed out after 108.753s.
Expected success, but got an error:
    <*errors.errorString | 0xc000826f70>: {
        s: "failed test on chn-004, with status failed err: failed",
    }
    failed test on chn-004, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:60
```

#### :x: helmrelease-test RHACM4K-1680

```
/opt/e2e/client/e2e_client/e2e_client_test.go:12
Timed out after 108.550s.
Expected success, but got an error:
    <*errors.errorString | 0xc0007f41d0>: {
        s: "failed test on RHACM4K-1680, with status failed err: failed",
    }
    failed test on RHACM4K-1680, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:13
```

