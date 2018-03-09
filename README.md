# merrimackhistory-ansible

1) create a VM
2) In DNS, point merrimackhistory.org to the IP address
3) ssh-copy-id root@merrimackhistory.org (use password from #1)
4) ansible-playbook -i hosts site.yml -u root
5) verify http://merrimackhistory.org/ has content

