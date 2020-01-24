# infrastructure

Make sure your follow the steps mentioned below:

1) Check your current working directory. Make sure you are in infrastructure directory.

2) Make sure all the required setup and software's are in place.

3) To run the playbook to create EC2, VPC, Security Groups etc, run the following command:
   --> ansible-playbook create_playbook.yaml -i inventory -vvvv

4) To run the playbook to delete the EC2, VPC and Security Groups etc, run the following command:
   --> ansible-playbook delete_playbook.yaml -i inventory -vvvv --extra-vars '{"tag_value":"jenkins"}'
