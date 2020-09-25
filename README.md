## Run Installer

### Production installations
sudo wget --no-cache "https://gitlab.com/skyhuborg/ansible-tracker/-/raw/master/install" -O "install" -o /dev/null && sudo chmod u+x ./install && sudo bash -c 'source ./install'

### Test installer in develop branch with this command
sudo wget --no-cache "https://gitlab.com/skyhuborg/ansible-tracker/-/raw/develop/install" -O "install" -o /dev/null && sudo chmod u+x ./install && sudo bash -c 'source ./install dev'