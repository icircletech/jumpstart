**TODO:**

-Add WP-CLI

-Add SFTP Server

-Add Webmin Console


**Instructions**

Run the following command to install a LAMP + Wordpress Stack:

    ansible-playbook -i hosts lamp-wp-stack.yml -u remote-user

or

    ansible-playbook lamp-wp-stack.yml -i hosts -u username -K

Adjust the Variables in 

    "./vars/default.yml"
