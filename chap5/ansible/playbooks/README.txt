
Running Openstack In Action examples from chapter 5.

The design is to use an already deployed openstack cloud to create a project
which will then be used to create the Openstack project and resoures to
complete the examples.  An Openstack on Openstack approach.

Playbooks.

 - os_setup.yaml
     - Perfroms ths setup necessary to enable the examples.
        - Install ubuntu image
	- Create Project/Users/Roles
	- Create networking infrasturcture.
	- Create VMs to run the examples.
 - 
