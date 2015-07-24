# ansible-bootstrap

A simple Ansible bootstrap for my Ubuntu 14.04 build.

As root:

    # apt-get update ; apt-get -y dist-upgrade 
    # apt-get -y install software-properties-common git-core
    # apt-add-repository -y ppa:ansible/ansible ; apt-get update
    # apt-get -y install ansible
    # ansible-pull -U https://github.com/pfarmer/ansible-bootstrap.git -i hosts
    

Or the one liner:

    apt-get update ; apt-get -y dist-upgrade ; apt-get -y install software-properties-common git-core ; apt-add-repository -y ppa:ansible/ansible ; apt-get update ; apt-get -y install ansible ; ansible-pull -U https://github.com/pfarmer/ansible-bootstrap.git -i hosts
