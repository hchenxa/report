# :red_circle: Failed when running regression on cluster ocp4-gcp-3 with test snapshot 2.3.0-SNAPSHOT-2021-04-17-07-15-32 

## Jenkins job URL: https://tests-jenkins-csb-rhacm.apps.ocp4.prod.psi.redhat.com/job/acmqe-e2e-automation/251/


ACM Version: v2.3.0

Hub Cluster Version: 4.8.2

Hub Cluster: https://multicloud-console.apps.ocp4-gcp-3.gcp.dev09.red-chesterfield.com

Managed Cluster Version: 4.8.2

Managed Cluster: https://console-openshift-console.apps.tn-aws-sno.dev09.red-chesterfield.com

Detailed test result on S3: https://s3.console.aws.amazon.com/s3/buckets/acmqe-regression/?region=ap-southeast-1&prefix=data/202108041125/

## Tests:

|Status|Results|Test|
|---|---|---|
| :x: | failed | Discoveryconfig controller Archived clusters Should not create DiscoveredClusters out of archived clusters |
| :x: | failed | Discoveryconfig controller Creating a DiscoveryConfig Should create discovered clusters  |
| :x: | failed | Discoveryconfig controller Credentials become invalid Should delete discovered clusters after secret is deleted |
| :x: | failed | Discoveryconfig controller Credentials become invalid Should delete discovered clusters when secret changes to an invalid one |
| :x: | failed | Discoveryconfig controller Deleting a DiscoveryConfig Should delete all discovered clusters via garbage collection |
| :x: | failed | Discoveryconfig controller Tracking ManagedClusters Should mark matching discovered clusters as being managed |
| :x: | failed | Discoveryconfig controller Tracking ManagedClusters Should unmark discovered clusters when they are no longer managed |
| :x: | failed | Discoveryconfig controller Unchanged DiscoveryConfig Should update discovered clusters when the OCM responses change |


---

### Failed Test Details

#### :x: Discoveryconfig controller Archived clusters Should not create DiscoveredClusters out of archived clusters

```
/workspace/test/e2e/discoveryconfig_controller.go:259
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario.func1(0x0)
	/workspace/test/e2e/discoveryconfig_controller.go:397 +0x1b8
reflect.Value.call(0x1464600, 0xc000580c78, 0x13, 0x1645490, 0x4, 0xc00070ee10, 0x0, 0x0, 0x1464600, 0x1, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x1464600, 0xc000580c78, 0x13, 0xc00070ee10, 0x0, 0x0, 0xc000091400, 0xc0000536d8, 0xc000051000)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000b636c0, 0xc000b2ea50, 0x21e0ae0, 0x7f08a6303a68, 0x70)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000b636c0, 0x1825898, 0x2210458, 0x40d401, 0xc00079f7b0, 0x1, 0x1, 0xc00079f7c0)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000b636c0, 0x1825898, 0x2210458, 0xc00079f7b0, 0x1, 0x1, 0x67)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario(0x1653899, 0x10)
	/workspace/test/e2e/discoveryconfig_controller.go:402 +0x3d4
github.com/open-cluster-management/discovery/test/e2e.glob..func1.7.1.1()
	/workspace/test/e2e/discoveryconfig_controller.go:261 +0x36
github.com/onsi/ginkgo.By(0x166a17e, 0x24, 0xc00070f1c0, 0x1, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:463 +0x122
github.com/open-cluster-management/discovery/test/e2e.glob..func1.7.1()
	/workspace/test/e2e/discoveryconfig_controller.go:260 +0x6b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc000329bc0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc000329bc0, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:64 +0x15c
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc0002626e0, 0x1803aa0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/it_node.go:26 +0x87
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc0003725a0, 0x0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:215 +0x72f
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc0003725a0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc00031e9a0, 0xc0003725a0, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:200 +0x111
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc00031e9a0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:170 +0x147
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc00031e9a0, 0xc000448f58)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc00015e9a0, 0x7f08a61ba2c8, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b80, 0x2, 0x2, 0x18381b8, 0xc00003c980, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/suite/suite.go:79 +0x546
github.com/onsi/ginkgo.runSpecsWithCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b60, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:238 +0x218
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc000502720, 0x1, 0x1, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:221 +0x136
github.com/open-cluster-management/discovery/test/e2e.RunE2ETests(0xc000093800)
	/workspace/test/e2e/e2e.go:69 +0x119
github.com/open-cluster-management/discovery/test/e2e.TestE2E(0xc000093800)
	/workspace/test/e2e/e2e_test.go:12 +0x51
testing.tRunner(0xc000093800, 0x16f9718)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Discoveryconfig controller Creating a DiscoveryConfig Should create discovered clusters 

```
/workspace/test/e2e/discoveryconfig_controller.go:107
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario.func1(0x0)
	/workspace/test/e2e/discoveryconfig_controller.go:397 +0x1b8
reflect.Value.call(0x1464600, 0xc000580180, 0x13, 0x1645490, 0x4, 0xc00070ee10, 0x0, 0x0, 0x1464600, 0x1, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x1464600, 0xc000580180, 0x13, 0xc00070ee10, 0x0, 0x0, 0xc000404000, 0xc0000536d8, 0xc000051000)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000454100, 0xc00007e140, 0x21e0ae0, 0x7f08a6303a68, 0x70)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000454100, 0x1825898, 0x2210458, 0x40d401, 0xc0005aa170, 0x1, 0x1, 0xc0005aa190)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000454100, 0x1825898, 0x2210458, 0xc0005aa170, 0x1, 0x1, 0x62)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario(0x164e293, 0xb)
	/workspace/test/e2e/discoveryconfig_controller.go:402 +0x3d4
github.com/open-cluster-management/discovery/test/e2e.glob..func1.3.1.1()
	/workspace/test/e2e/discoveryconfig_controller.go:109 +0x36
github.com/onsi/ginkgo.By(0x1666691, 0x21, 0xc00070f1c0, 0x1, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:463 +0x122
github.com/open-cluster-management/discovery/test/e2e.glob..func1.3.1()
	/workspace/test/e2e/discoveryconfig_controller.go:108 +0x6b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc000329440, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc000329440, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:64 +0x15c
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc0002f9f40, 0x1803aa0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/it_node.go:26 +0x87
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc0003720f0, 0x0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:215 +0x72f
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc0003720f0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc00031e9a0, 0xc0003720f0, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:200 +0x111
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc00031e9a0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:170 +0x147
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc00031e9a0, 0xc000448f58)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc00015e9a0, 0x7f08a61ba2c8, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b80, 0x2, 0x2, 0x18381b8, 0xc00003c980, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/suite/suite.go:79 +0x546
github.com/onsi/ginkgo.runSpecsWithCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b60, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:238 +0x218
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc000502720, 0x1, 0x1, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:221 +0x136
github.com/open-cluster-management/discovery/test/e2e.RunE2ETests(0xc000093800)
	/workspace/test/e2e/e2e.go:69 +0x119
github.com/open-cluster-management/discovery/test/e2e.TestE2E(0xc000093800)
	/workspace/test/e2e/e2e_test.go:12 +0x51
testing.tRunner(0xc000093800, 0x16f9718)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Discoveryconfig controller Credentials become invalid Should delete discovered clusters after secret is deleted

```
/workspace/test/e2e/discoveryconfig_controller.go:320
Timed out after 60.000s.
Testserver should reach a running state with its entrypoint argument set to --scenario=tenClusters
Expected
    <bool>: false
to be true
/workspace/test/e2e/discoveryconfig_controller.go:402
```

#### :x: Discoveryconfig controller Credentials become invalid Should delete discovered clusters when secret changes to an invalid one

```
/workspace/test/e2e/discoveryconfig_controller.go:285
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario.func1(0x0)
	/workspace/test/e2e/discoveryconfig_controller.go:397 +0x1b8
reflect.Value.call(0x1464600, 0xc0000a05d0, 0x13, 0x1645490, 0x4, 0xc00070ee10, 0x0, 0x0, 0x1464600, 0x1, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x1464600, 0xc0000a05d0, 0x13, 0xc00070ee10, 0x0, 0x0, 0xc00005ec00, 0xc0000536d8, 0xc000051000)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000a60b00, 0xc0004fe5a0, 0x21e0ae0, 0x7f08a6303a68, 0x70)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000a60b00, 0x1825898, 0x2210458, 0x40d401, 0xc00074eb70, 0x1, 0x1, 0xc00074eb80)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000a60b00, 0x1825898, 0x2210458, 0xc00074eb70, 0x1, 0x1, 0x62)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario(0x164e293, 0xb)
	/workspace/test/e2e/discoveryconfig_controller.go:402 +0x3d4
github.com/open-cluster-management/discovery/test/e2e.glob..func1.8.2.1()
	/workspace/test/e2e/discoveryconfig_controller.go:287 +0x36
github.com/onsi/ginkgo.By(0x1666691, 0x21, 0xc00070f1c0, 0x1, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:463 +0x122
github.com/open-cluster-management/discovery/test/e2e.glob..func1.8.2()
	/workspace/test/e2e/discoveryconfig_controller.go:286 +0x6b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc000329e60, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc000329e60, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:64 +0x15c
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc000262980, 0x1803aa0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/it_node.go:26 +0x87
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc000372690, 0x0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:215 +0x72f
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc000372690, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc00031e9a0, 0xc000372690, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:200 +0x111
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc00031e9a0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:170 +0x147
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc00031e9a0, 0xc000448f58)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc00015e9a0, 0x7f08a61ba2c8, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b80, 0x2, 0x2, 0x18381b8, 0xc00003c980, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/suite/suite.go:79 +0x546
github.com/onsi/ginkgo.runSpecsWithCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b60, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:238 +0x218
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc000502720, 0x1, 0x1, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:221 +0x136
github.com/open-cluster-management/discovery/test/e2e.RunE2ETests(0xc000093800)
	/workspace/test/e2e/e2e.go:69 +0x119
github.com/open-cluster-management/discovery/test/e2e.TestE2E(0xc000093800)
	/workspace/test/e2e/e2e_test.go:12 +0x51
testing.tRunner(0xc000093800, 0x16f9718)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Discoveryconfig controller Deleting a DiscoveryConfig Should delete all discovered clusters via garbage collection

```
/workspace/test/e2e/discoveryconfig_controller.go:236
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario.func1(0x0)
	/workspace/test/e2e/discoveryconfig_controller.go:397 +0x1b8
reflect.Value.call(0x1464600, 0xc0000a0240, 0x13, 0x1645490, 0x4, 0xc00070ed20, 0x0, 0x0, 0x1464600, 0x1, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x1464600, 0xc0000a0240, 0x13, 0xc00070ed20, 0x0, 0x0, 0xc000090400, 0xc00004e6d8, 0xc00004c000)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000a109c0, 0xc0002be320, 0x21e0ae0, 0x7f08a6303108, 0x70)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000a109c0, 0x1825898, 0x2210458, 0x40d401, 0xc000609320, 0x1, 0x1, 0xc000609330)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000a109c0, 0x1825898, 0x2210458, 0xc000609320, 0x1, 0x1, 0x62)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario(0x164e293, 0xb)
	/workspace/test/e2e/discoveryconfig_controller.go:402 +0x3d4
github.com/open-cluster-management/discovery/test/e2e.glob..func1.6.1.1()
	/workspace/test/e2e/discoveryconfig_controller.go:238 +0x4b
github.com/onsi/ginkgo.By(0x16805d9, 0x32, 0xc00070f1c0, 0x1, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:463 +0x122
github.com/open-cluster-management/discovery/test/e2e.glob..func1.6.1()
	/workspace/test/e2e/discoveryconfig_controller.go:237 +0x6b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc000329a40, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc000329a40, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:64 +0x15c
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc000262540, 0x1803aa0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/it_node.go:26 +0x87
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc0003724b0, 0x0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:215 +0x72f
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc0003724b0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc00031e9a0, 0xc0003724b0, 0x4)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:200 +0x111
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc00031e9a0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:170 +0x147
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc00031e9a0, 0xc000448f58)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc00015e9a0, 0x7f08a61ba2c8, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b80, 0x2, 0x2, 0x18381b8, 0xc00003c980, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/suite/suite.go:79 +0x546
github.com/onsi/ginkgo.runSpecsWithCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b60, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:238 +0x218
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc000502720, 0x1, 0x1, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:221 +0x136
github.com/open-cluster-management/discovery/test/e2e.RunE2ETests(0xc000093800)
	/workspace/test/e2e/e2e.go:69 +0x119
github.com/open-cluster-management/discovery/test/e2e.TestE2E(0xc000093800)
	/workspace/test/e2e/e2e_test.go:12 +0x51
testing.tRunner(0xc000093800, 0x16f9718)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Discoveryconfig controller Tracking ManagedClusters Should mark matching discovered clusters as being managed

```
/workspace/test/e2e/discoveryconfig_controller.go:149
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario.func1(0x0)
	/workspace/test/e2e/discoveryconfig_controller.go:397 +0x1b8
reflect.Value.call(0x1464600, 0xc0000a0168, 0x13, 0x1645490, 0x4, 0xc00070ed50, 0x0, 0x0, 0x1464600, 0x1, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x1464600, 0xc0000a0168, 0x13, 0xc00070ed50, 0x0, 0x0, 0xc000090000, 0xc000050ed8, 0xc00004e800)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc000a380c0, 0xc0002be0a0, 0x21e0ae0, 0x7f08a63035b8, 0x70)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc000a380c0, 0x1825898, 0x2210458, 0x40d401, 0xc000914060, 0x1, 0x1, 0xc000914070)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc000a380c0, 0x1825898, 0x2210458, 0xc000914060, 0x1, 0x1, 0x62)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario(0x164e293, 0xb)
	/workspace/test/e2e/discoveryconfig_controller.go:402 +0x3d4
github.com/open-cluster-management/discovery/test/e2e.glob..func1.4.1.1()
	/workspace/test/e2e/discoveryconfig_controller.go:151 +0x48
github.com/onsi/ginkgo.By(0x166c433, 0x26, 0xc00070f1c0, 0x1, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:463 +0x122
github.com/open-cluster-management/discovery/test/e2e.glob..func1.4.1()
	/workspace/test/e2e/discoveryconfig_controller.go:150 +0x6b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc0003295c0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc0003295c0, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:64 +0x15c
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc0002620e0, 0x1803aa0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/it_node.go:26 +0x87
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc0003721e0, 0x0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:215 +0x72f
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc0003721e0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc00031e9a0, 0xc0003721e0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:200 +0x111
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc00031e9a0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:170 +0x147
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc00031e9a0, 0xc000448f58)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc00015e9a0, 0x7f08a61ba2c8, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b80, 0x2, 0x2, 0x18381b8, 0xc00003c980, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/suite/suite.go:79 +0x546
github.com/onsi/ginkgo.runSpecsWithCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b60, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:238 +0x218
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc000502720, 0x1, 0x1, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:221 +0x136
github.com/open-cluster-management/discovery/test/e2e.RunE2ETests(0xc000093800)
	/workspace/test/e2e/e2e.go:69 +0x119
github.com/open-cluster-management/discovery/test/e2e.TestE2E(0xc000093800)
	/workspace/test/e2e/e2e_test.go:12 +0x51
testing.tRunner(0xc000093800, 0x16f9718)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Discoveryconfig controller Tracking ManagedClusters Should unmark discovered clusters when they are no longer managed

```
/workspace/test/e2e/discoveryconfig_controller.go:174
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario.func1(0x0)
	/workspace/test/e2e/discoveryconfig_controller.go:397 +0x1b8
reflect.Value.call(0x1464600, 0xc000aa8318, 0x13, 0x1645490, 0x4, 0xc00070ed50, 0x0, 0x0, 0x1464600, 0x1, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x1464600, 0xc000aa8318, 0x13, 0xc00070ed50, 0x0, 0x0, 0xc000091400, 0xc000050ed8, 0xc00004e800)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0007c0200, 0xc000400280, 0x21e0ae0, 0x7f08a63035b8, 0x70)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0007c0200, 0x1825898, 0x2210458, 0x40d401, 0xc000914200, 0x1, 0x1, 0xc000914210)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0007c0200, 0x1825898, 0x2210458, 0xc000914200, 0x1, 0x1, 0x62)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario(0x164e293, 0xb)
	/workspace/test/e2e/discoveryconfig_controller.go:402 +0x3d4
github.com/open-cluster-management/discovery/test/e2e.glob..func1.4.2.2()
	/workspace/test/e2e/discoveryconfig_controller.go:184 +0x48
github.com/onsi/ginkgo.By(0x1660483, 0x1c, 0xc00070f1c0, 0x1, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:463 +0x122
github.com/open-cluster-management/discovery/test/e2e.glob..func1.4.2()
	/workspace/test/e2e/discoveryconfig_controller.go:183 +0xb5
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc0003296e0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc0003296e0, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:64 +0x15c
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc000262200, 0x1803aa0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/it_node.go:26 +0x87
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc0003722d0, 0x0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:215 +0x72f
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc0003722d0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc00031e9a0, 0xc0003722d0, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:200 +0x111
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc00031e9a0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:170 +0x147
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc00031e9a0, 0xc000448f58)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc00015e9a0, 0x7f08a61ba2c8, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b80, 0x2, 0x2, 0x18381b8, 0xc00003c980, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/suite/suite.go:79 +0x546
github.com/onsi/ginkgo.runSpecsWithCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b60, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:238 +0x218
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc000502720, 0x1, 0x1, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:221 +0x136
github.com/open-cluster-management/discovery/test/e2e.RunE2ETests(0xc000093800)
	/workspace/test/e2e/e2e.go:69 +0x119
github.com/open-cluster-management/discovery/test/e2e.TestE2E(0xc000093800)
	/workspace/test/e2e/e2e_test.go:12 +0x51
testing.tRunner(0xc000093800, 0x16f9718)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

#### :x: Discoveryconfig controller Unchanged DiscoveryConfig Should update discovered clusters when the OCM responses change

```
/workspace/test/e2e/discoveryconfig_controller.go:209
Test Panicked
/usr/local/go/src/runtime/panic.go:88

Panic: runtime error: index out of range [0] with length 0

Full stack:
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario.func1(0x0)
	/workspace/test/e2e/discoveryconfig_controller.go:397 +0x1b8
reflect.Value.call(0x1464600, 0xc000a33a58, 0x13, 0x1645490, 0x4, 0xc00070ed20, 0x0, 0x0, 0x1464600, 0x1, ...)
	/usr/local/go/src/reflect/value.go:476 +0x8e7
reflect.Value.Call(0x1464600, 0xc000a33a58, 0x13, 0xc00070ed20, 0x0, 0x0, 0xc000091400, 0xc000050ed8, 0xc00004e800)
	/usr/local/go/src/reflect/value.go:337 +0xb9
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).pollActual(0xc0007c0280, 0xc00007fb30, 0x21e0ae0, 0x7f08a63035b8, 0x70)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:78 +0xee
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).match(0xc0007c0280, 0x1825898, 0x2210458, 0x40d401, 0xc00078a6e0, 0x1, 0x1, 0xc00078a700)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:112 +0x92
github.com/onsi/gomega/internal/asyncassertion.(*AsyncAssertion).Should(0xc0007c0280, 0x1825898, 0x2210458, 0xc00078a6e0, 0x1, 0x1, 0x62)
	/go/pkg/mod/github.com/onsi/gomega@v1.10.2/internal/asyncassertion/async_assertion.go:51 +0x85
github.com/open-cluster-management/discovery/test/e2e.updateTestserverScenario(0x164e293, 0xb)
	/workspace/test/e2e/discoveryconfig_controller.go:402 +0x3d4
github.com/open-cluster-management/discovery/test/e2e.glob..func1.5.1.1()
	/workspace/test/e2e/discoveryconfig_controller.go:211 +0x4b
github.com/onsi/ginkgo.By(0x16805d9, 0x32, 0xc00070f1c0, 0x1, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:463 +0x122
github.com/open-cluster-management/discovery/test/e2e.glob..func1.5.1()
	/workspace/test/e2e/discoveryconfig_controller.go:210 +0x6b
github.com/onsi/ginkgo/internal/leafnodes.(*runner).runSync(0xc0003298c0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:113 +0xa3
github.com/onsi/ginkgo/internal/leafnodes.(*runner).run(0xc0003298c0, 0x3, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/runner.go:64 +0x15c
github.com/onsi/ginkgo/internal/leafnodes.(*ItNode).Run(0xc0002623a0, 0x1803aa0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, 0x0, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/leafnodes/it_node.go:26 +0x87
github.com/onsi/ginkgo/internal/spec.(*Spec).runSample(0xc0003723c0, 0x0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:215 +0x72f
github.com/onsi/ginkgo/internal/spec.(*Spec).Run(0xc0003723c0, 0x1803aa0, 0xc00003c980)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/spec/spec.go:138 +0xf2
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpec(0xc00031e9a0, 0xc0003723c0, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:200 +0x111
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).runSpecs(0xc00031e9a0, 0x1)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:170 +0x147
github.com/onsi/ginkgo/internal/specrunner.(*SpecRunner).Run(0xc00031e9a0, 0xc000448f58)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/specrunner/spec_runner.go:66 +0x117
github.com/onsi/ginkgo/internal/suite.(*Suite).Run(0xc00015e9a0, 0x7f08a61ba2c8, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b80, 0x2, 0x2, 0x18381b8, 0xc00003c980, ...)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/internal/suite/suite.go:79 +0x546
github.com/onsi/ginkgo.runSpecsWithCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc0002f9b60, 0x2, 0x2, 0x2)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:238 +0x218
github.com/onsi/ginkgo.RunSpecsWithDefaultAndCustomReporters(0x1804780, 0xc000093800, 0x16530f9, 0x10, 0xc000502720, 0x1, 0x1, 0x0)
	/go/pkg/mod/github.com/onsi/ginkgo@v1.16.1/ginkgo_dsl.go:221 +0x136
github.com/open-cluster-management/discovery/test/e2e.RunE2ETests(0xc000093800)
	/workspace/test/e2e/e2e.go:69 +0x119
github.com/open-cluster-management/discovery/test/e2e.TestE2E(0xc000093800)
	/workspace/test/e2e/e2e_test.go:12 +0x51
testing.tRunner(0xc000093800, 0x16f9718)
	/usr/local/go/src/testing/testing.go:1193 +0xef
created by testing.(*T).Run
	/usr/local/go/src/testing/testing.go:1238 +0x2b3
```

