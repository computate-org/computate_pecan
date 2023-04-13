
# Install the prerequisite applications, powertools and libmodplug

- https://github.com/computate-org/computate_powertools
- https://github.com/computate-org/computate_libmodplug

# Install the pecan ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_pecan

# Clone the pecan ansible role. 
git clone git@github.com:computate-org/computate_pecan.git ~/.ansible/roles/computate.computate_pecan

# Change into the pecan ansible role directory. 
cd ~/.ansible/roles/computate.computate_pecan
```

# Run the pecan ansible playbook to install pecan locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
