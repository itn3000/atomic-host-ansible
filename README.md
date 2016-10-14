# What's this

ansible playbooks for [atomic host getting started guide](http://www.projectatomic.io/docs/gettingstarted/)

# Files

* host-variables-example.ini
    * sample inventory file,you must edit before running ansible
* proxy-playbook.yml
    * proxy setting(docker service,login user,and yum)
* docker-registry-playbook.yml
    * setting for docker registry mirror service
* docker-storage-playbook.yml
    * setting for docker root storage
* local-registry.service
    * systemd unit file for local registry service using docker
* 10-flanneld-network.conf
    * docker service configuration file for enabling flanneld
* flanneld-conf.json
    * flanneld config file for setting via etcd
* flanneld-playbook.yml
    * setting flanneld service
* kubernates-playbook.yml
    * setting kubernetes master host
* kubehost-playbook.yml
    * setting kubernetes node
