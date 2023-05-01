# ansible-pull-desktop
Based upon https://github.com/LearnLinuxTV/personal_ansible_desktop_configs


1. ansible pull command <Command>
2. Looks for `local.yml` in root of git repo
3. Roles look for `main.yml` in `/roles/<role name>/tasks/`
4. Roles are 1:1 with groups of hosts

# Ansible pull from Host Machine

```
sudo apt install git ansible
ansible-pull -U https://github.com/JamesHaughey/ansible-pull-desktop.git -C main
```

# Apt Install Notes
- ansible
- bat
- git
- htop
- jq
- yq
- slack-desktop
- solaar
- tilix
- zsh
