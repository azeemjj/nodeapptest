This is the complete Integration of Trivy file scan sonarqube for code anylysis and OWASP for dependency check complete integration on the jenkins server.

These are the following steps you must do to configure whole stack.
Step No 1 Deploy Jensings self hosted server on Ubuntu VM.
Step No 2 : install Java on the Agent node of jenkins otherwise it will not work.
step no 3: after installation all the Plugins required for this installed them in Jenkins like
Build Pipeline Plugin
Command Agent Launcher Plugin
Docker Pipeline
Docker plugin
docker-build-step
Eclipse Temurin installer Plugin
Email Extension Plugin
GitHub Integration Plugin
Gradle Plugin
HTML Publisher plugin
JavaMail API
Kubernetes
Kubernetes :: Pipeline :: DevOps Steps
Kubernetes CLI Plugin
Kubernetes Continuous Deploy Plugin
Kubernetes Credentials Provider
LDAP Plugin
NodeJS Plugin
Oracle Java SE Development Kit Installer Plugin
OWASP Dependency-Check
PAM Authentication plugin
Pipeline
Pipeline Graph View
Pipeline: GitHub
Pipeline: GitHub Groovy Libraries
Sonargraph Integration Jenkins Plugin
SonarQube Scanner for Jenkins
SSH Agent Plugin
SSH Pipeline Steps
SSH server
Timestamper
Workspace Cleanup Plugin

Step No 4:
Deploy docker container for SonarQube for Static code anylysis it must be listen on port 9000
Step No 5:
Craete a new Project in Sonar Qube and also create  a new Project key and create a new token and this token must be added in the jenkins secrets.
Step no 6:
Just install OWASP plugin and configure it in Pipeline and in server configuration.
Step no 7:
Install trivi in the Agent machine of jenkins otherwise it will not work and htmlpublisher plugin must be installed.


