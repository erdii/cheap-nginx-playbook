# Cheap Nginx Playbook for Ubuntu

* set `domain` and `email` in `playbook.yml`
* create `./inventory` and put your target server ip in there
* execute `ansible-playbook -i inventory playbook.yml`
* profit!

PS: use `vagrant up` to test the playbook (obviously letsencrypt won't work in vagrant)
