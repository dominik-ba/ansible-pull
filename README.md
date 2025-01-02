# ansible-pull-example

my ansible pull repo

## invoking ansible

```bash
# pull mode (suitable for automation)
sudo ansible-pull -o -U https://github.com/dominik-ba/ansible-pull.git -C main

# push mode (development)
$ ansible-playbook -i inventory ./playbook.yml --limit foo.example.com
```

## Prereqs:

- git
- ansible

```bash
sudo su
apt update
apt install git ansible
```
