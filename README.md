# Kubernetes_Test
Create K8s cluster on Windows by using Vagrant. 
After initiating nodes, use Ansible to bootstrap cluster.

# Step1: Run cmd command to add box to Vagrant
  ~ vagrant box add fedora/25-cloud-base --provider virtualbox
  ~ vagrant box add ubuntu/xenial64  --provider virtualbox             # Provider can be virtualbox, libvirt, vmware_desktop, etc.

# Step2: Run cmd command to initiate Vagrantfile (run cmd on any folder you want ~^^~)
  ~ vagrant init                                					   # Change Vagrantfile configuration like example
  
# Step3: Place your id_rsa and id_rsa.pub
example:
C:\Users\user-name\keypair\

# Step4: Bootstrap your cluster
  ~ vagrant up
  
# Step5: Updating
