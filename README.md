# vagrant-ansible-sentry-centos7
Setting Sentry on CentOS7 in Vagrant By Ansible

-

# Prerequisite

Installed bellow tools

- VirtualBox
- Vagrant


# Usage

### 1. Add Vagrant Box (CentOS7)

```
$ vagrant box add centos7 https://f0fff3908f081cb6461b407be80daf97f07ac418.googledrive.com/host/0BwtuV7VyVTSkUG1PM3pCeDJ4dVE/centos7.box
```

### 2. git clone this repository

```
$ git clone https://github.com/kenzo0107/vagrant-ansible-sentry-centos7
```

### 3. VagrantVM Build

```
$ cd vagrant-ansible-sentry-centos7
$ vagrant up
```

### 4. add ssh.config

```
$ vagrant ssh-config > ssh.config
```

### 5. ansible-playbook 

```
$ ansible-playbook sentry.yml
```

### 6. Access private_network http://(ip address)

http://192.168.33.10

Display Sentry Auth Login Page !


