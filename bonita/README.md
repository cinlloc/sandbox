# Howto use this script
This Ansible script locally installs and starts Bonita CE Tomcat bundle with default configuration and a secure password. 

Prerequisite: Ansible 2.9> is installed locally, Java 8 is installed locally. 

To execute the script, copy `BonitaCommunity-7.9.4-tomcat.zip` into the same directory as the playbook then run: `ansible-playbook deploy-bonita.yml`.