# Kubernetes_Test
# Create K8s cluster on Windows by using Vagrant. 
# After initiating nodes, use Ansible to bootstrap cluster.

Step1: Run cmd command to add box to Vagrant
  ~ vagrant box add centos/7 --provider virtualbox
  ~ vagrant box add ubuntu/trusty64             # Provider can be virtualbox, libvirt, vmware_desktop, etc.

Step2: Run cmd command to initiate Vagrantfile (run cmd on any folder you want ~^^~)
  ~ vagrant init
  # Change Vagrantfile configuration
  
Step3: Bootstrap your cluster
  ~ vagrant up
  
Step4: Updating 
