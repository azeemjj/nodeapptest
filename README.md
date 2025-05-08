This is the complete Integration of Trivy file scan, SonarQube for code analysis, and OWASP for dependency check, and complete integration on the Jenkins server.

The following steps are required to configure the whole stack.
Step No. 1: Deploy Jenkins' self-hosted server on Ubuntu VM.
Step No 2: install Java on the Agent node of Jenkins; otherwise,e it will not work.
Step no 3: After installation, all the Plugins required for this are installed in Jenkins like
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
Deploy a Docker container for SonarQube for Static code analysis, it must be listening on port 9000
Step No 5:
Create a new Project in Sonar Qube, create  a new Project key, and create a new token; this token must be added to the Jenkins secrets.
Step no 6:
Just install the OWASP plugin and configure it in the Pipeline and the server configuration.
Step no 7:
Install Trivi in the Agent machine of Jenkins; otherwise, it will not work, and the HTML Publisher plugin must be installed.


