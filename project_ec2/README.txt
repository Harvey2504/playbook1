sudo apt update
sudo apt install ansible
sudo apt install python3-pip
pip3 install boto boto3
sudo apt install awscli
sudo aws configure

ansible-playbook -i inventory.ini sample_playbook.yml
(same for ec2 and s3)