# :red_circle: Failed when running regression on cluster ocp-bm-f16-h18-0 with test snapshot 2.4.0-SNAPSHOT-2021-09-23-08-29-45 

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
| :x: | failed | Observability: [P1][Sev1][Observability] Cannot enable observability service successfully |
| :x: | failed | Observability: [P1][Sev1][Observability] Cannot uninstall observability service completely |


---

### Failed Test Details

#### :x: Observability: [P1][Sev1][Observability] Cannot enable observability service successfully

```
/workspace/tests/pkg/tests/observability-e2e-test_suite_test.go:101
Timed out after 1.003s.
Expected success, but got an error:
    <*errors.StatusError | 0xc0006a6000>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "the server could not find the requested resource",
            Reason: "NotFound",
            Details: {Name: "", Group: "", Kind: "", UID: "", Causes: nil, RetryAfterSeconds: 0},
            Code: 404,
        },
    }
    the server could not find the requested resource
/workspace/tests/pkg/tests/observability_install_test.go:69
```

#### :x: Observability: [P1][Sev1][Observability] Cannot uninstall observability service completely

```
/workspace/tests/pkg/tests/observability-e2e-test_suite_test.go:106
Unexpected error:
    <*errors.StatusError | 0xc0003c23c0>: {
        ErrStatus: {
            TypeMeta: {Kind: "", APIVersion: ""},
            ListMeta: {
                SelfLink: "",
                ResourceVersion: "",
                Continue: "",
                RemainingItemCount: nil,
            },
            Status: "Failure",
            Message: "clusterrolebindings.rbac.authorization.k8s.io \"mco-e2e-testing-crb\" not found",
            Reason: "NotFound",
            Details: {
                Name: "mco-e2e-testing-crb",
                Group: "rbac.authorization.k8s.io",
                Kind: "clusterrolebindings",
                UID: "",
                Causes: nil,
                RetryAfterSeconds: 0,
            },
            Code: 404,
        },
    }
    clusterrolebindings.rbac.authorization.k8s.io "mco-e2e-testing-crb" not found
occurred
/workspace/tests/pkg/tests/observability_uninstall_test.go:34
```

