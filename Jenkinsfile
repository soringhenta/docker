node {
checkout scm
def customImage = docker.build("sorin_alpine-jenkins_teste:${env.BUILD_ID}")

customImage.inside {
echo "Building: ${env.BUILD_ID}"
}
}
