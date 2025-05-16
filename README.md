Description:
Designed and implemented a fully automated deployment pipeline using Ansible to install Java, configure Apache Tomcat, and deploy a Java .war application on an AWS EC2 Linux instance. The project was completed using both flat playbook and role-based Ansible architecture to follow best practices and enhance modularity.

Key Responsibilities:

Automated installation of OpenJDK 11 on Amazon Linux using Ansible.

Configured Apache Tomcat 9 from scratch, including systemd service creation for startup automation.

Deployed a Java-based web application (app.war) by copying it to Tomcat's webapps/ directory using Ansible playbooks.

Implemented role-based Ansible structure (java, tomcat, deploy) to improve maintainability and reusability.

Restarted Tomcat service through Ansible to ensure WAR deployment was successful and live.

Configured EC2 security groups and tested web application accessibility via public IP on port 8080.

Validated deployment by accessing the web app at http://<EC2-IP>:8080/app.

Tools & Technologies:

Ansible, Apache Tomcat, Java (OpenJDK 11)

AWS EC2, Amazon Linux 2

Systemd, YAML, Linux CLI
