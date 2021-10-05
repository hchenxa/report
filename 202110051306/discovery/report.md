# :white_check_mark: Passed when running regression on cluster ocp-bm-f16-h18-0 with test snapshot 2.4.0-SNAPSHOT-2021-09-23-08-29-45 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/298/


ACM Version: v2.4.0

Hub Cluster Version: 4.9.0-rc.1

Hub Cluster: https://multicloud-console.apps.ocp-bm-f16-h18-0.qe.lab.redhat.com

Managed Cluster Version: 4.9.0-rc.1

Managed Cluster: https://console-openshift-console.apps.ocp-bm-f16-h18-0.qe.lab.redhat.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202110051306/

## Tests:

|Status|Results|Test|
|---|---|---|
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Archived clusters Should not create DiscoveredClusters out of archived clusters |
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Creating a DiscoveryConfig Should create discovered clusters  |
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Credentials become invalid Should delete discovered clusters after secret is deleted |
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Credentials become invalid Should delete discovered clusters when secret changes to an invalid one |
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Deleting a DiscoveryConfig Should delete all discovered clusters via garbage collection |
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Multiple DiscoveryConfigs across namespaces Should manage DiscoveredClusters across namespaces |
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Multiple DiscoveryConfigs across namespaces Should update DiscoveredClusters' managed status across namespaces |
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Tracking ManagedClusters Should mark matching discovered clusters as being managed |
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Tracking ManagedClusters Should unmark discovered clusters when they are no longer managed |
| :white_check_mark: | passed | [P1][Sev1][installer] Discoveryconfig controller Unchanged DiscoveryConfig Should update discovered clusters when the OCM responses change |


---

