# gradle-bintray-deploy

> Deploy your package to JFrog's Bintray & Maven Central from Gradle easily

Blog post: https://medium.com/@ryanseys/publishing-to-maven-central-and-jcenter-2b6376424856

## Usage

1. Drop the `deploy.gradle` file into your project next to your top-level `build.gradle`.
2. Copy the configuration from this repo's `build.gradle` into yours and update the values to reflect your package.
3. Run `./gradlew bintrayUpload` and you're done! Log into [Bintray][bintray] to check out your new package.

## License

Apache 2.0 - See [LICENSE](LICENSE) for more information.

[bintray]: https://bintray.com
