ssh:- help to secure the connection(encrypted communciaton)
ssh key Authentication
server -- client
asametric key -- to encript and decrpt



Ansible:- tool to automate IT tasks
-------
How ansible works?
ansible works by connecting nodes and pushing out samll programs called anible modules, to them.
ansible then execute these modules over ssh by default and remove them when finished
library of module can reside on any machine.
and there are no server, demons or database required
Management Node(Control Server, Master Server) => 
Inventory file -> provide the list of host where the ansible modules need to be run.
Main advantage of ansible- it remove the modules once configration is  done
    - so it connect the host machine execute the instruction and once configration done, it remove the ansible modules.
    - it use the ssh connect to push module to the host
 there are three ways to push the code.
  - ad-hoc commands(it just simple linux command)
     - ad-hoc means temporary. (no idempotency)
  - modules - to run single command or work
  - playbooks - to run more than single command.
modules and playbooks written in yml.





advantage:-
python friedly
easy to learn
agentless
yaml == playbook == modules == task(todo-instruction)
yet another markup language
  - play is going to be executed against all the hosts.

1)what happen when we execute playbook?
  we execute playbook (anible)
  
ansible galaxy -  comminity there we find infomatin and we can contribute bec it publec   

Ansible install
- we can install in Linux sytem.

Ansible in Devops:-
-----------------
Ansible Control Node --> this is the system that has Ansible installed on it. and that will be managing other systems.
1) It should be have inventory, that list of devices that we're going to be controlling.




set up:-
1) how to install Ansible to Management Node (Central Node, Main Node, Control Server, Master Server)
2) how to communicate to Client Node through ssh 




Ansible and Red Hat:-

configuration (change or setup)
tasks:  time consuming and tedious to do manually. Repetitive Tasks
configuration Management tools:- 

configuration Management - Orchestratoin  - Deployment.
humans are prone to do mistake and forgets.

Ansible is written in PYthon.
Playbooks are written in YAML
Strict indentation
Playbook describes: how and in which order
    -
    
    build, maintain, moniter and manage and operate - 
    targets the local system and remote system.
    control other system (control node)
    (clientless)ssh
    
    
   
    Fleet Management - Red Hat Ansible tower
    ad hoc command 
    
    
    
    configuration - manual - automation - 1) shell scripting  2) configurations tools - Ansible, Puppet, chef
    
    shell scripting language -  Python
    shell scripting limitation:-  
    what is the different between shell sripting language
    
    
#  KR NETWORK CLOUD   utube
   Ansible : 
   1. It is an opensource.
   2. It configuration management tools.
   3. It automate the configuration.
   4. using ansible we can manage IT changes
 
 1) server change:  cross platform
     - file creation, software installation , permission, disk managment.

2) Dvices changes:
3) Cloud 

    what is  Mutable and unmutable infrastructure?
 4) Virtulizatoin Host:
    
ansible tower - gui of ansible develop by redhat

working  style of Ansible?
1) Ansible is an  agent less  configuration tools.
2) it work on push system
3) it work on parrell(forks) and serial mode
4) by default it comes with Forks style (forks=5)
5) 
we can install ansible server on linux Based Machine:-




Ansible Arch- 
1) control Node -- ansible server
2) Manage Node  -- the mchine where u running Ansible
softeare
  os: only linux Based
  python - 2.6
4) 
5) Connection PLugin
6) Inventory system
8) Ad Hoc - commands (simple Linux), no tempotency
9) Modules - single work
10) Playbooks - more then one module.

===============================================================
spring
spring core, 
dependency injection, auto wiring


What is Spring Framework:- 
----------------------------
Spring Framework with Core i.e Spring Dependency Injection:-
  We use Maven Build Tool for SF
  - impement Spring IOC
  - implement spring dependency injection
Inverson of Control(IOC)
- ioc provides mecha


pojo- plain old Java Object
Java Bean - Dimple object with only getter and setter



  
dependiencies
it provide ioc and dependiencies Injection.





spring boot is sub module of spring: 
----------------------------------
what is spring framework really all about: 



spring boot is module of spring from which we speed up the development.
It provides an easier and faster way to set up, configure, and run both simple and web-based application.
  - converntion over configuration software dising style.
  
  - because it make the config atuomatic
  - rapid application development | boilerplate
 Spring Framework + Embedded Sever  - Configuration = Boot
 Automatically configure
 
 
 
 
 
 
 
 
 
 








