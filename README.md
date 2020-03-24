# Using tinylog in a GraalVM native image

1. Ensure that the [local toolchain](https://www.graalvm.org/docs/reference-manual/native-image/#prerequisites) for native images is installed

2. Build the project and generate the configuration via `./gradlew generateConfiguration`

3. Create the native image via `./gradlew nativeImage`

4. You will find the executable in `build/graal`