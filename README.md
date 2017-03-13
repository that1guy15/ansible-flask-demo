# ansible-flask-demo
Demo used to deploy a Flask website from scratch 

# Vagrant servers  
Deployment server: CentOS/7 w/ Ansible 2.2.0  
Target server: ubuntu/trusty64  
  
#Setup Steps:  
  
Clone repo to deployment server  
```git clone https://github.com/that1guy15/ansible-flask-demo.git```   
  
Update hosts file on deployment server  
```cd ansible-flask-demo```   
```vim hosts```   
```[webservers]'''
'''<target_server IP>'''


