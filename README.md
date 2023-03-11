# prepdeb

git clone url prepdeb
cd prepdeb
git module init --update
ansible-vault edit group_vars/vault.yml
# edit host_vars/localhost.yml
ansible-playbook playbooks/main.yml
