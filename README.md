# ansible-bootstrap

A simple Ansible bootstrap for my Ubuntu 14.04 build.


## Ubuntu

    # apt-get update ; apt-get -y dist-upgrade 
    # apt-get -y install ansible git-core zsh
    # ansible-pull -U https://github.com/pfarmer/ansible-bootstrap.git -i hosts
    

Or the one liner:

    apt-get update ; apt-get -y dist-upgrade ; apt-get update ; apt-get -y install ansible git-core zsh ; ansible-pull -U https://github.com/pfarmer/ansible-bootstrap.git -i hosts

