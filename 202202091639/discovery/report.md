# :warning: Had some failures when running regression on cluster rdr-acm-submariner-48 with test snapshot 2.4.2-DOWNSTREAM-2022-02-04-19-03-29 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/452/


ACM Version: v2.4.2

Hub Cluster Version: 4.9.9

Hub Cluster: https://multicloud-console.apps.rdr-acm-submariner-48.mon01.ibm-power-acm.com

Managed Cluster Version: 4.9.9

Managed Cluster: https://console-openshift-console.apps.rdr-acm-submariner-48.mon01.ibm-power-acm.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202202091639/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2553 - Add RHOCM credential in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2555 - Delete RHOCM credential in the namespace aut-disco-ns |
| :x: | failed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2556 - Create discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2557 - Update discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2558 - Delete discoveryConfig in the namespace aut-disco-ns |
| :white_check_mark: | passed | Discovery config - Error handling RHACM4K-2554 - Update RHOCM cred for invalid token |
| :white_check_mark: | passed | Discovery config - Error handling RHACM4K-3020 - No clusters discovered in case of invalid token |
| :white_check_mark: | passed | Discovery config - Import a discovered cluster in UI RHACM4K-2819 - Detach discovered clusters |
| :x: | failed | Discovery config - Import a discovered cluster in UI RHACM4K-3019 - Import a discovered cluster kubeconfig (UI only) |
| :x: | failed | Discovery config - Import a discovered cluster in UI RHACM4K-3174 - Import a discovered cluster apitoken (UI only) |
| :x: | failed | Discovery config - Import a discovered cluster in UI RHACM4K-7514 - Import a discovered cluster manual (UI only) |


---

### Failed Test Details

#### :x: Discovery config - Creating/Updating/Deleting discovery config in UI RHACM4K-2556 - Create discoveryConfig in the namespace aut-disco-ns

```
AssertionError: Timed out retrying after 30000ms: Expected to find content: 'Create cluster discovery' within the element: [ <td.pf-c-table__check>, 6 more... ] but never did.
    at navigate (https://multicloud-console.apps.rdr-acm-submariner-48.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/01_disco.spec.js:857:38)
    at createClusterDisco (https://multicloud-console.apps.rdr-acm-submariner-48.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/01_disco.spec.js:869:3)
    at Context.eval (https://multicloud-console.apps.rdr-acm-submariner-48.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/01_disco.spec.js:480:39)
```

#### :x: Discovery config - Import a discovered cluster in UI RHACM4K-3019 - Import a discovered cluster kubeconfig (UI only)

```
TypeError: Cannot read property 'split' of undefined
    at Context.eval (https://multicloud-console.apps.rdr-acm-submariner-48.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02_import.spec.js:1273:30)
```

#### :x: Discovery config - Import a discovered cluster in UI RHACM4K-3174 - Import a discovered cluster apitoken (UI only)

```
TypeError: Cannot read property 'split' of undefined
    at Context.eval (https://multicloud-console.apps.rdr-acm-submariner-48.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02_import.spec.js:1273:30)
```

#### :x: Discovery config - Import a discovered cluster in UI RHACM4K-7514 - Import a discovered cluster manual (UI only)

```
TypeError: Cannot read property 'split' of undefined
    at Context.eval (https://multicloud-console.apps.rdr-acm-submariner-48.mon01.ibm-power-acm.com/__cypress/tests?p=cypress/tests/02_import.spec.js:1273:30)
```

