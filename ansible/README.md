# Ansible Deployment

This config is ready but it needs a few tweaks.

First Run
- Create a bastion instance on Google.
- run `gcloud compute ssh bastion --zone` this command is only needed generate ssh keys and add it to the project.
- Amend ssh.cfg to have the IP of the bastion.