# :white_check_mark: Passed when running regression on cluster ocp4-gcp-3 with test snapshot 2.3.0-SNAPSHOT-2021-07-22-07-01-30 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/242/


ACM Version: v2.3.0

Hub Cluster Version: 4.6.23

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.0-fc.7

Managed Cluster: https://console-openshift-console.apps.dhrpatel-aws-sno-gcp-3-hive.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202107220742/

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

