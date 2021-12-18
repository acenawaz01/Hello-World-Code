Devops Tool Installation:

https://github.com/acenawaz01/Hello-World-Code/blob/release_cicd/pom.xml

Nexus Download:
1. Download Nexus from below URL
https://www.sonatype.com/products/repository-oss-download

2. Copy it from local URL to the EC2 machine using below command.
scp -i cli-test.pem <tar-filename>.tar.gz  ec2-user@mec2-50-17-16-67.compute-1.amazonaws.com:~/.

3. Untar the nexus tar filename

4. Go inside the bin folder and run below command to get nexus up and running.

Note: that you should inbound traffic enabled on the port where you are the running Nexus


Ansible Setup: (Jenkins + AppServer1 and Appserve2)
$ sudo yum install epel-release
$ sudo yum install ansible
Create the ansible setup on all three servers

I had to configure the ssh keys to enable logging to other machines
