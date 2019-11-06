# Comparison of using MakeFile/Ansible-playbook/Chezmo to manage my dotfiles
  
| MakeFile | Ansible-playbook | Chezmoi |
| --- | :---: | :---: |
|Manage project dependencies |Manage servers pool configurations |Manage your dotfiles |
|Good to setup project dependencies. It allows to install packages, create dir, set env vars... |Ansible role/tasks are good but it feels to be overkill for a laptop install. It's stateful and created to manage servers pool.| Chezmoi is very good to manage dotfiles and allow versionning, save etc.. His fir goal is to share dotfiles accross multiple clients/servers so it's not my goal. But it can't preinstall for me packages over all Linux distrib |
