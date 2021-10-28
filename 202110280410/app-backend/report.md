# :warning: Had some failures when running regression on cluster ocp4-az-01 with test snapshot 2.4.0-SNAPSHOT-2021-10-25-23-58-51 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/376/


ACM Version: v2.4.0

Hub Cluster Version: 4.6.46

Hub Cluster: https://multicloud-console.apps.ocp4-az-01.az.dev06.red-chesterfield.com

Managed Cluster Version: 4.9.0

Managed Cluster: https://console-openshift-console.apps.acmqe-24-rc-hive-ansible-azure.acm-dev06.azure.devcluster.openshift.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110280410/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | RHACM4K-2350: e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Helm repo with basic authentication |
| :white_check_mark: | passed | channel-test chn-001 |
| :white_check_mark: | passed | channel-test chn-002 |
| :white_check_mark: | passed | channel-test chn-003 |
| :white_check_mark: | passed | channel-test chn-004 |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git commit |
| :white_check_mark: | passed | e2e-git-subscription-test [P1][Sev1][app-lifecycle] Test subscription with Git release tag |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test argocd integration |
| :white_check_mark: | passed | e2e-server [P1][Sev1][app-lifecycle] Test subscribing to Git repo with custom certificate |
| :white_check_mark: | passed | e2e-subscription-admin-test [P1][Sev1][app-lifecycle] Test nested subscriptions with subscription admin |
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

#### :x: helmrelease-test RHACM4K-1680

```
/opt/e2e/client/e2e_client/e2e_client_test.go:12
Timed out after 108.984s.
Expected success, but got an error:
    <*errors.errorString | 0xc000204280>: {
        s: "failed test on RHACM4K-1680, with status failed err: failed",
    }
    failed test on RHACM4K-1680, with status failed err: failed
/opt/e2e/client/e2e_client/e2e_client_test.go:13
```

