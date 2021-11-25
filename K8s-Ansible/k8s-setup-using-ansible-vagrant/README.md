# k8s-setup-using-ansible-vagrant
[kubernetes.io](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)
It's a copy from [kubernetes-setup-using-ansible-and-vagrant](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/) Kubernetes blog's post. I made some changes to update it.

```

┌─[torbite]@[Bio2059]:~/k8s-augusto/k8s-setup-using-ansible-vagrant
└──> $ vagrant status
Current machine states:

k8s-master                running (virtualbox)
node-1                    running (virtualbox)
node-2                    running (virtualbox)

This environment represents multiple VMs. The VMs are all listed
above with their current state. For more information about a specific
VM, run `vagrant status NAME`.

```

```

┌─[torbite]@[Bio2059]:~/k8s-augusto/k8s-setup-using-ansible-vagrant
└──> $ vagrant ssh k8s-master
Welcome to Ubuntu 16.04.6 LTS (GNU/Linux 4.4.0-173-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

 * Multipass 1.0 is out! Get Ubuntu VMs on demand on your Linux, Windows or
   Mac. Supports cloud-init for fast, local, cloud devops simulation.

     https://multipass.run/

6 packages can be updated.
6 updates are security updates.



This system is built by the Bento project by Chef Software
More information can be found at https://github.com/chef/bento
Last login: Wed Feb  5 17:23:19 2020 from 10.0.2.2
-bash: warning: setlocale: LC_CTYPE: cannot change locale (pt_BR.UTF-8): No such file or directory
vagrant@k8s-master:~$

```
