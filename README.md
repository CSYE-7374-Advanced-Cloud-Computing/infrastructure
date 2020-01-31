# infrastructure

Branch: -- Assignment 2

Team Details:

a) Hemal Gadhiya -- 001460577
b) Paavan Gopala -- 001813403

Make sure you follow the steps as mentioned below:

1) Check your current working directory. Make sure you are in infrastructure local repository directory.

2) Make sure all the required setup and software's are in place.

3) To run the Ansible playbook to create EC2, VPC, Security Groups etc, run the following command:
   --> ansible-playbook create_playbook.yaml -i inventory -vvvv

4) To run the Ansible playbook to delete the EC2, VPC and Security Groups etc, run the following command:
   --> ansible-playbook delete_playbook.yaml -i inventory -vvvv --extra-vars '{"tag_value":"jenkins"}'
