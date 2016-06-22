# ansible_recepies

## Provisioning for Ruby On Rails applications

### For ansible 2.0

1. Ensure you can be ssh as a root
2. ssh-copy-id root@your_ip
3. install ansible
4. create hosts file or grab this example
5. ansible-playbook -i hosts setup.yml
6. wait
7. ssh root@your_ip
8. passwd deploy_user_name
9. ssh-copy-id deploy_user_name@your_ip

10. Provisioning done
