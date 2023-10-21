# prepdeb

git clone https://github.com/tbasset/prepdeb.git prepdeb<br/>
cd prepdeb<br/>
git module init --update<br/>
<br/>
ansible-vault edit group_vars/vault.yml<br/>
edit host_vars/localhost.yml<br/>
<br/>
ansible-playbook playbooks/main.yml<br/>

