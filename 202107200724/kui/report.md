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
| :white_check_mark: | passed | [P0][sev1][kui]Visual Web Terminal: Verify user path for rbash |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify KUI multiple tabs |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify kubectl |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify oc |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify subctl |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify supported CLIs can execute |
| :white_check_mark: | passed | [P1][sev1][kui]Visual Web Terminal: Verify user home folder permissions |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify core support commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify core support commands for window are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev1][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify KUI getting started command |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify bash like commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify commands are disabled - rbash |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify k8s commands are disabled - plugin-kui-addons |
| :white_check_mark: | passed | [P2][sev2][kui]Visual Web Terminal: Verify product header |
| :x: | failed | [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus |
| :white_check_mark: | passed | [P2][sev3][kui]Visual Web Terminal: Verify supported themes |


---

### Failed Test Details

#### :x: [P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus

```
    at Page.clear (/usr/src/app/tests/page-objects/Prometheus.js:121:10)
    at Page.queryMetric (/usr/src/app/tests/page-objects/Prometheus.js:98:30)
    at Object.[P2][sev2][kui]Visual Web Terminal: Verify visual_web_terminal_sessions_total metric in hub Prometheus (/usr/src/app/tests/e2e/verifyMetricsInPrometheus.test.js:19:18)
```

