# AmazonLinux-Hardeningscript
AmazonLinux-Hardening script with CIS Benchmark
•	Copy all the files provided to harden the AMI to home directory of ec2 –instance as shown below:
# scp -i pemkey -r scriptfolder ec2-user@ipaddress:/home/ec2-user/
•	Later, SSH to EC2 instance , then execute following command:
# sudo yum update
# sudo python ./scriptfolder  -v
