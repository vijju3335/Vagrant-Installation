## Vagrant-Installation
vagrant-installation on WINDOWS

## Project Overview
  Vagrant provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.Once you or someone else creates a single Vagrantfile, you just need to vagrant up and everything is installed and configured for you to work. Other members of your team create their development environments from the same configuration, so whether you are working on Linux, Mac OS X, or Windows, all your team members are running code in the same environment, against the same dependencies, all configured the same way. Say goodbye to "works on my machine" bugs.

For more, visit [Vagrant](https://www.vagrantup.com/docs/)


## Table Of Contents
- [Download](#download)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Postgresql](https://github.com/vijju3335/LogsAnalysis)
- [Bug And Feature Requests](#bug-and-feature-requests)


### Download
The files for the project, [download](https://github.com/vijju3335/Vagrant-Installation/archive/master.zip).

#### What's included

Within the download you'll find the following directories and files:
```
Vagrant-Installation-master.zip
|
└── images
|     |
|     └── v1.pjg
|     └── v2.jpg
|     └── v3.jp  
|     └── ...
|
└── VM_Vagrant
|     |
|     └── Vargantfile
|
└── README.md
```

### Prerequisites
- For Direct installation  [download](https://github.com/vijju3335/Vagrant-Installation/archive/master.zip) and  go [here](#installation)

## Installation

- Install [Vagrant](https://download.virtualbox.org/virtualbox/5.2.12/VirtualBox-5.2.12-122591-Win.exe).
- Install [Virtual Box](https://www.vagrantup.com/downloads.html).

- First here, I go to anydrive and copy downloaded folder [here](https://github.com/vijju3335/Vagrant-Installation/blob/master/images/v1.jpg)
- open command prompt at that folder [live demo](https://github.com/vijju3335/Vagrant-Installation/blob/master/images/v1.jpg)

```C:\Users\vijaybabu\Desktop\VM_Vagrant>```

- [Skip](#stages), below command unless to want to use another vagrant box.
- There are different vagrant-boxes [here](https://app.vagrantup.com/boxes/search)
- This required only at time of intialization.

#### Stages

- To [Start Vagrant](#start-vagrant)
- To [Exit Vagrant](#exit-vagrant)
- To [Stop Vagrant](#stop-vagrant)
- To [Restart Vagrant](#restart-vagrant)

### Start Vagrant

```C:\Users\vijaybabu\Desktop\VM_Vagrant>vagrant up```  [live demo](https://github.com/vijju3335/Vagrant-Installation/blob/master/images/v2.png)

- To control **Virtual Machine** from Host Sytem

```C:\Users\vijaybabu\Desktop\VM_Vagrant>vagrant ssh```  [live demo](https://github.com/vijju3335/Vagrant-Installation/blob/master/images/v3.JPG)

- To Access shared Directory Folders,

```
vagrant@vagrant:~$ cd /vagrant
vagrant@vagrant:/vagrant$
```

```
vagrant@vagrant:/vagrant$ ls -a
.  ..  .vagrant  Vagrantfile
vagrant@vagrant:/vagrant$ 
```
### Exit Vagrant
- To Exit from vagrant virtual box ,
```
vagrant@vagrant:/vagrant$
vagrant@vagrant:/vagrant$ exit
logout
Connection to 127.0.0.1 closed.

C:\Users\vijaybabu\Desktop\VM_Vagrant>
```
### Stop Vagrant
- To stop vagrant virtual box ,
```
C:\Users\vijaybabu\Desktop\VM_Vagrant>vagrant halt
==> default: Attempting graceful shutdown of VM...

C:\Users\vijaybabu\Desktop\VM_Vagrant>
```

### Restart Vagrant
if any changes made to config file **Vagrantfile** must follow these,
- [Stop Vagrant](#stop-vagrant) then
- [Start Vagrant](#start-vagrant)

---
### Postgresql
- how to use [postgresql](https://github.com/vijju3335/LogsAnalysis) see from here.

## Bug And Feature Requests
- Have a bug or a feature request? Please feel free to open an [issue](https://github.com/vijju3335/Vagrant-Installation/issues).

