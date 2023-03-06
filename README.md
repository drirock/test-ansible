# test-ansible
This is an example of ansible playbook.
It check freespace from 2 filesystem in configured in <b>test-ansible/roles/test/vars/main.yml</b> and set as variable the fs with more than 800Mb

Execute from path where is the folder test-ansible with following command:<br>
ansible-playbook -i inventory.txt test-ansible.yml
