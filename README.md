ansible-playbook haproxy_all.yaml keepalived_all.yaml -l loadbalancers
ansible-playbook nginx_all.yaml -l webservers
