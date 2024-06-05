--> Developers put code in GitHub it’s a Java based code

--> I have designed Jenkins pipeline to  download the code from Git-Hub

-->	Jenkins created artifact using Maven

-->	 Then Jenkins taking this artifact and based on this artifact Jenkins is designing dockerfile to create  customised docker image 

-->	After Jenkins  will upload image in to Docker Hub 

-->Now design ansible playbook to deploy this image in to multiple severs

-->	Creating Ansible playbooks in Ansible servers

-->	This ansible playbooks are designed to download image from docker hub and create its container in all testing servers

-->	This Ansible playbook will be trigged from Jenkins.

-->	Then Jenkins Execute selenium programmes, selenium program checks whether this application working properly is not.

-->	IF is working correctly. deploy in to prod

-->	Now create Kubernetes deployment and service definition files. Then Jenkins should create these files
