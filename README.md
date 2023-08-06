# playbook

# Tester ansible en local

## Commande

```bash
# Lancer le script d'automatisation
ansible-playbook -i hosts playbook.yml --ask-become-pass

ansible-playbook -i hosts playbook-installer-package.yml --ask-become-pass

ansible-playbook -i hosts playbook-test-template.yml --ask-become-pass