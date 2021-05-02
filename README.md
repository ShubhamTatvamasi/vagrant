# vagrant

Download vagrant box:
```bash
vagrant box add bento/ubuntu-16.04
vagrant box add ubuntu/focal64
```

List all vagrant boxs
```bash
vagrant box list
```

Setup Vagrantfile for an image
```bash
vagrant init ubuntu/focal64
```

Start vagrant box:
```bash
vagrant up
```

Check status of the box:
```bash
vagrant status
```

Package your VM:
```bash
vagrant package
```

Install scp package:
```bash
vagrant plugin install vagrant-scp
```

ssh into vagrant box:
```bash
vagrant ssh
```

Shutdown system:
```bash
vagrant halt
```

Save the current state on VM:
```bash
vagrant suspend
```

Resume suspended machine:
```bash
vagrant resume
```

Restart vagrant box:
```bash
vagrant reload
```

Destroy vagrant box:
```bash
vagrant destroy -f
```

