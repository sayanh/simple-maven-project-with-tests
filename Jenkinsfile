node('linux') {
  stage 'Build and Test'
  def mvnHome = tool 'M3'

  env.PATH = "${mvnHome}/bin:${env.PATH}"
  git url: "https://github.com/sayanh/simple-maven-project-with-tests.git"
  sh 'mvn clean package'

}
