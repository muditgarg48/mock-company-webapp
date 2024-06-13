pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
   stages {
      stage("build") {
          steps {
            ./gradlew assemble
          }
      }
      stage("test") {
          steps {
            ./gradlew test
          }
      }
   }
}
