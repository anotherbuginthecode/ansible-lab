# Ansible Labs 01

These are Ansible Labs for the youtube Channel DevOps Journey.


Video Playlist:
https://www.youtube.com/watch?v=KuiAiUyuDY4&list=PLnFWJCugpwfzTlIJ-JtuATD2MBBD7_m3u

## How to use these Labs
1. Install Oracle Virtual Box:  https://www.virtualbox.org/

2. Install Vagrant: https://www.vagrantup.com/downloads.html

3. In a new Directory copy this respository:

``` shell
git clone https://github.com/anotherbuginthecode/ansible-labs.git
```

4. Start the vagrant instance.
``` shell
vagrant up
```

5. SSH into the ansible-control virtual machine.
``` shell
vagrant ssh ansible-control
```

6. Run ansible playbook
``` shell
cd /vagrant/ansible-lab01
ansible-playbook -i inventories/dev -K playbook.yml
```
