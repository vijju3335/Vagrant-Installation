## Vagrant-Installation
vagrant-installation on WINDOWS

## Project Overview
  Vagrant provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.Once you or someone else creates a single Vagrantfile, you just need to vagrant up and everything is installed and configured for you to work. Other members of your team create their development environments from the same configuration, so whether you are working on Linux, Mac OS X, or Windows, all your team members are running code in the same environment, against the same dependencies, all configured the same way. Say goodbye to "works on my machine" bugs.

For more, visit [Vagrant](https://www.vagrantup.com/docs/)


## Table Of Contents
- [Download](#download)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Bug And Feature Requests](#bug-and-feature-requests)


#### Download
The files for the project, [download](https://github.com/vijju3335/Vagrant-Installation/archive/master.zip).

#### What's included

Within the download you'll find the following directories and files:
```
Vagrant-Installation-master.zip
|
└── images
|     |
|     └── v1.pjg
|     |
|     └── v2.jpg
|     |
|     └── v3.jpg
|     |
|     └── .....
|
└── README.md
```

#### Prerequisites
- For Direct installation  [download](https://github.com/vijju3335/Vagrant-Installation/archive/master.zip) and  go [here](#)
---
## Installation

- Install [Vagrant](#vagrant)
- Install [Virtual Box](#virtual-box)

- First here, I go to drive, D and create folder VM_14.04
- open command prompt at VM_14.04 folder 

```D:\VM_14.0.4>```

- There are different vagrant-boxes [here](https://app.vagrantup.com/boxes/search)
- This required only at time of intialization.
#### Stages

- To [Start Vagrant](#start-vagrant)
- To [Exit Vagrant](#exit-vagrant)
- To [Stop Vagrant](#stop-vagrant)
- To [Restart Vagrant](#restart-vagrant)

- Skip Below  command if you [download](https://github.com/vijju3335/Vagrant-Installation/archive/master.zip) these files. 
```D:\VM_14.0.4>vagrant init ubuntu/trusty64 ```  [live demo](https://github.com/vijju3335/LogsAnalysis/blob/master/images/v1.JPG) 

### Start Vagrant

- Go to directory where Vagrantfile exists. then open command 
```D:\VM_14.0.4>vagrant up```  [live demo](https://github.com/vijju3335/LogsAnalysis/blob/master/images/v2.JPG)

- To control **Virtual Machine** from Host Sytem

```\VM_14.04>vagrant ssh```  [live demo](https://github.com/vijju3335/LogsAnalysis/blob/master/images/v3.JPG)

- To Access shared Directory Folders,
```
vagrant@vagrant-ubuntu-trusty-64:~$ cd /vagrant
vagrant@vagrant-ubuntu-trusty-64:/vagrant$
```
[live demo](https://github.com/vijju3335/LogsAnalysis/blob/master/images/v4.png)
```
vagrant@vagrant-ubuntu-trusty-64:/vagrant$ ls -a
.  ..  .vagrant  Vagrantfile
vagrant@vagrant-ubuntu-trusty-64:/vagrant$ 
```
### Exit Vagrant
- To Exit from vagrant virtual box ,
```
vagrant@vagrant-ubuntu-trusty-64:/vagrant$
vagrant@vagrant-ubuntu-trusty-64:/vagrant$ exit
logout
Connection to 127.0.0.1 closed.
```
### Stop Vagrant
- To stop vagrant virtual box ,
```
D:\VM_14.0.4>vagrant halt
==> default: Attempting graceful shutdown of VM...

D:\VM_14.0.4>
```

### Restart Vagrant
if any changes made to config file **Vagrantfile** must follow these,
- [Stop Vagrant](#stop-vagrant) then
- 
```D:\VM_14.0.4>vagrant up```
```D:\VM_14.04>vagrant ssh```  

#### Vagrant
- Download the vagrant setup file for **windows** [Vagrant.exe](https://www.vagrantup.com/downloads.html).
These files configure the virtual machine and install all the tools needed to run this project.

#### Virtual Box
- Download the virtual box setup file for **windows** [VirtualBox.exe](https://download.virtualbox.org/virtualbox/5.2.12/VirtualBox-5.2.12-122591-Win.exe).

---

## Bug And Feature Requests
- Have a bug or a feature request? Please feel free to open an [issue](https://github.com/vijju3335/LogsAnalysis/issues).

