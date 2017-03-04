# ansible-local-provisioning

## Setup


```shell
sudo apt-get install curl
curl -L https://raw.githubusercontent.com/jbeurel/ansible-local-provisioning/master/setup.sh | sh
```

## Run

```shell
sudo ansible-galaxy install -r requirements.txt
ansible-playbook playbook.yml -vvvv -K -c local
```
