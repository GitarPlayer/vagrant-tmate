# vagrant-tmate
vagrant box with kubectl. helm and tmate installed, properly configured to connect.

# How to use it
Run vagrant up inside this folder, then run: 
```bash
vagrant up
vagrant ssh
tmate
Tip: if you wish to use tmate only for remote access, run: tmate -F                                                             [0/0]To see the following messages again, run in a tmate session: tmate show-messages
Press <q> or <ctrl-c> to continue
---------------------------------------------------------------------
Connecting to ssh.tmate.io...
Note: clear your terminal before sharing readonly access
web session read only: https://tmate.io/t/ro-JXqmEWWXVGUM3mEc4pg5qW9FQ
ssh session read only: ssh ro-JXqmEWWXVGUM3mEc4pg5qW9FQ@lon1.tmate.io
web session: https://tmate.io/t/vSqwabJEzvHyFjGk8PmNnUhP7
ssh session: ssh vSqwabJEzvHyFjGk8PmNnUhP7@lon1.tmate.io
# Now people can access your terminal in various ways.
```
