# Bitwarden manual updater 

This updater updates your manual installed Bitwarden docker-compose instance.

## Requirements
- Functional Bitwarden
- Bash
- Knowledge of domain which Bitwarden runs on E.g. ```bitwarden.example.com```

## Download
Download the ```setup.sh``` into your root-directory from bitwarden. E.g. your ```docker-compose.yml``` file is in ```/opt/bitwarden/bwdata/docker```, then you have to place the ```setup.sh``` file into ```/opt/bitwarden```. It needs to be above ```bwdata```. 
```bash
root:/opt/bitwarden# curl -o setup.sh https://raw.githubusercontent.com/craeckor/bitwarden-manual-update/main/setup.sh
```
For execute permissions, add ```+x``` with ```chmod``` to setup.sh.
```bash
root:/opt/bitwarden# chmod +x setup.sh
```
