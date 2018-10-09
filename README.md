# openfaas-on-conoha
Ansible playbook to create a Conoha(Openstack VM)  deploy OpenFaaS onto it


```
$ansible-playbook --version
ansible-playbook 2.6.3
```

```
ansible-playbook -i ./hosts.yml ./site.yml -l "<IP address>" -k
```


### to do
Install k8s and Opnefaas on a server that can login with ssh

### Future work
Multi-stage Serverless on Kubernetes with OpenFaaS and Conoha
