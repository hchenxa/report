# :warning: Had some failures when running regression on cluster slot-00 with test snapshot 2.3.0-SNAPSHOT-2021-07-26-18-43-26 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/244/


ACM Version: v2.3.0

Hub Cluster Version: 4.8.2

Hub Cluster: https://multicloud-console.apps.slot-00.dev09.red-chesterfield.com

Managed Cluster Version: 4.7.21

Managed Cluster: https://console-openshift-console.apps.slot-04.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107280205/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | channel-test chn-001 |
| :white_check_mark: | passed | channel-test chn-002 |
| :x: | failed | channel-test chn-003 |
| :x: | failed | channel-test chn-004 |
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
Timed out after 108.091s.
Expected success, but got an error:
    <*errors.errorString | 0xc0004de040>: {
        s: "failed test on chn-003, with status failed err: failed",
    }
    failed test on chn-003, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:57
```

#### :x: channel-test chn-004

```
/opt/e2e/client/e2e_client/e2e_client_test.go:59
Timed out after 108.067s.
Expected success, but got an error:
    <*errors.errorString | 0xc0000c2800>: {
        s: "failed test on chn-004, with status failed err: failed",
    }
    failed test on chn-004, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:60
```

#### :x: helmrelease-test RHACM4K-1680

```
/opt/e2e/client/e2e_client/e2e_client_test.go:12
Timed out after 108.057s.
Expected success, but got an error:
    <*errors.errorString | 0xc0004df040>: {
        s: "failed test on RHACM4K-1680, with status failed err: failed",
    }
    failed test on RHACM4K-1680, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:13
```

