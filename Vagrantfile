# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "arrikto/minikf"
  config.vm.hostname = "kubeflow"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "16384"
    vb.cpus = 8
    vb.name = "KubeFlow"
 end
end