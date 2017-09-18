**AnsibleHackSession-1**


----------


![enter image description here](https://secure.meetupstatic.com/photos/event/5/d/1/3/600_464603827.jpeg)


----------


Our first ansible hack session

We are planning to touch the following subjects

- LabEnv vagrant setup

- BootStrapping a new server

- Inventory

- Running module commands

- Setting up a project

- Roles vs playbooks

- Simple playbooks

but we are not limited to these by any means.

If you have any suggestions do let us know or discuss them f2f on the session.

We have been discussing in general in our slack channel (https://devstaff.slack.com/messages/C6AHQP4JH)


----------


Required:

- Bring your laptop

- Make sure that vagrant is installed and working on it

- (have the image of ubuntu/trusty64 already downloaded)

----------
USAGE
---

Login to `ansimaster` via
```vagrant ssh ansimaster```

As user `vagrant` you can run any playbook from the following directory:
```/home/vagrant/ansible```
like so:
```ansible-playbook -i inventory/hosts playbooks/testThings.yml```

The key of ansimaster exists already on the three web nodes
