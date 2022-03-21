# Spring Cloud Contract Producer for [Issue 1667](https://github.com/spring-cloud/spring-cloud-contract/issues/1667)

## Environment
OpenJDK 11

## How to

1. Specify the Spring Cloud Contract Version in `gradle.properties`
2. `./gradlew clean generateContractTests test`
3. `build/generated-test-sources/contracts/com/scc/issue1667/demo/ContractVerifierTest.java` is the generated test.

## Reference
- https://github.com/spring-cloud-samples/spring-cloud-contract-samples
- https://cloud.spring.io/spring-cloud-contract/reference/html/gradle-project.html
- https://github.com/spring-cloud/spring-cloud-contract/issues/1667
