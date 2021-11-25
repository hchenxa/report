# :warning: Had some failures when running regression on cluster ocp4-acm24-aws-01 with test snapshot v2.4.1-RC1 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/tests/job/thnguyen-e2e/36/


ACM Version: v2.4.1

Hub Cluster Version: 4.8.19

Hub Cluster: https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com

Managed Cluster Version: 4.9.8

Managed Cluster: https://console-openshift-console.apps.hchen-aws-clc.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202111251728/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2553 - Add RHOCM credential in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2555 - Delete RHOCM credential in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2556 - Create discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2557 - Update discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2558 - Delete discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Error handling RHACM4K-2554 - Update RHOCM cred for invalid token |
| :white_check_mark: | passed | Discovery config - Error handling RHACM4K-3020 - No clusters discovered in case of invalid token |
| :white_check_mark: | passed | Discovery config - Import a discovered cluster in UI RHACM4K-2819 - Detach discovered clusters |
| :white_check_mark: | passed | Discovery config - Import a discovered cluster in UI RHACM4K-3019 - Import a discovered cluster kubeconfig (UI only) |
| :x: | failed | Discovery config - Import a discovered cluster in UI RHACM4K-3174 - Import a discovered cluster apitoken (UI only) |
| :white_check_mark: | passed | Discovery config - Import a discovered cluster in UI RHACM4K-7514 - Import a discovered cluster manual (UI only) |


---

### Failed Test Details

#### :x: Discovery config - Import a discovered cluster in UI RHACM4K-3174 - Import a discovered cluster apitoken (UI only)

```
AssertionError: Timed out retrying after 30000ms: Expected to find element: `tbody > tr`, but never found it.
    at Context.eval (https://multicloud-console.apps.ocp4-acm24-aws-01.dev09.red-chesterfield.com/__cypress/tests?p=cypress/tests/02_import.spec.js:924:8)
```

