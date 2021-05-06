# K8sMultiNodeCluster
Ansible role for creating a little infrastructure of Kubernetes multimode cluster over AWS cloud

1. Donwload all the files and keep it in a folder  `roles`.
2. Try to keep the `.pem` security key file in the same roles folder where you kept this repo files.
3. In `vars.yml`, replace your access key and secret key of AMI with mine.
4. change the values of variable instead of `image_id`.
5. Configure the `ansible.cfg` file according to your paths of `roles` directory.
6. All done! Just run `ec2.yml` file with : `ansible-playbook ec2.yml`.
7. Then, after successfully starting the instances and inventory updates. Run `main.yml` file with : `ansible-playbook main.yml`.
8. They will call the roles and apply the changes accordingly.

`This cluster will create two slave nodes and one master node for cluster. It contains the static inventory, you can practice the same with dynamic inventory too`

Enjoy the k8s-cluster on just two clicks.
