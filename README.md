# Ansible
Receta Ansible


This recipe will create a two simple debian intances listen to after execute the ansible playbook to run a wordpress already configured and installed .


Steps 

0.  Put your own Openstack-key in "hot.yml" key zone and in ansible.cfg

1.  launch the stack in your Openstack project via "hot.yml"  

2. replace in "hosts.ini" the ip's that appear for the floating ip thats nova assign to your machines 

3. Launch the ansible.yml playbook 

4. Sustitute your principal dns for ip of the nodo1 machine

5. go to wordpress.misael.gonzalonazareno.org

6. Rock & Roll
