# ansible-shieldy

## Usage
### Download the docker galaxy
````
ansible-galaxy collection install community.docker
````

### Add you SSH pub-key to the server
Connect to the lightsail instance:
https://lightsail.aws.amazon.com/ls/webapp/eu-central-1/instances/FyfyUbuntu01/connect

Append your id_rsa.pub to the file:
/home/ubuntu/.ssh/authorized_keys

## Running the playbook
Install requirements
```
ansible-playbook docker-setup.yml
```
Download the source and run 'docker-compose up'
```
ansible-playbook shieldly.yaml
```
