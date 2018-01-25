Use the official Jenkins LTS image: jenkins/jenkins:lts

To run:

docker run -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts

For documentation, see https://github.com/jenkinsci/docker/blob/master/README.md
