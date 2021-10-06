# Installing Virtualbox and Vagrant for MacOSX

Vagrant uses Virtualbox to manage the virtual dependencies.

```$ brew cask install virtualbox```

```$ brew install vagrant```

```$ brew cask install vagrant-manager```

Add the Vagrant box link:

```$ vagrant box add precise64 http://files.vagrantup.com/<link>```

More boxes are available here: [Vagrant Cloud](https://app.vagrantup.com/boxes/search).

# Initializing the VM:

```$ vagrant init <box-name>```

```$ vagrant up```

```$ vagrant ssh```

Other regularly used commands can include halt, suspend and destroy.
