# List my dependencies needed on every laptop. ✍️
## Searched from my actual Centos7 Env.  
  
| Soft/Tool/Pkg | Dependencies | Versions | Details | Type | Structure |
| :--- | :---: | :---: | :---: | :---: |
| **Vim** | $HOME/.vimrc | latest | My text editor. With my confs. (maccros, indentation). | Package | -> # tree -L 2 $HOME/.vim/
/root/.vim/
├── autoload
│   └── plug.vim
├── ftdetect
│   ├── docker-compose.vim
│   └── Dockerfile.vim
├── plugged
│   ├── nerdcommenter
│   └── vim-puppet
├── snippets
│   ├── docker-compose.snippets
│   └── Dockerfile.snippets
└── syntax
    ├── docker-compose.vim
    ├── Dockerfile.vim
    └── python.vim |
| **Zsh** | $HOME/.zshrc | latest | My shell (aliases et ENV vars). | Package |  |
| **Oh-my-zsh** | $HOME/.oh-my-zsh/* | latest | Framework for managing your zsh configuration. |  |
| **Git** | $HOME/.ssh/config && $HOME/.gitconfig | latest | Git is a fast, scalable, distributed revision control system with an unusually rich command set. | Package |  |
| **Curl** | Just a binary. | latest | Tool to transfer data to/from a server using a lot of proto (HTTP, FTP, SMTP, TFTP...) | Package |  |
| **Ssh** | /etc/ssh/sshd_config && $HOME/.ssh/* | latest | My ssh client package. | Package |  |
| **Ag** | binary | latest | A tool for searching a string in folders (support regex). | Package |  | 
| **Sed** | binary | latest | A tool to manipulate file content. | Package |  |
| **Nmap** | binary | latest | A tool to scan network ports. | Package |  |
| **Netcat || nc** | binary | latest | A tool to open network connections. | Package |  |
| **Traceroute** | binary | latest | A tool to trace a package travel through the network to reach an IP/url. | Package |  |
| **Dig** | binary | latest | A tool to communicate with DNS servers. | Package |  |
| **Dive** | binary | latest | A tool for exploring docker images layers. | Package (from github) |  |
| **Docker** | /etc/docker/* && /etc/containerd | latest | Docker engine + cli. | Package |  |
| **Sudo** | /etc/sudoers && /etc/sudoers.d/* | latest | Sudo tool to execute command as another user. | Package |  |
| **Kvm** | /etc/libvirt/* | latest | Kernel-based Virtual Machine. Free and opensource Hypervisor for Linux :D. Qemu = logiciel libre de machine virtuelle, KVM = hyperviseur / instance de QEMU, Libvirt = lib de gestion de la virtualisation utilisée par des hyperviseurs, Virt-manager = outil graphique pour gérer les machines virtuelles.) | Packages (qemu-kvm, libvirt, libguestfs-tools, libvirt-python, virt-install, virt-manager) |  | 
| **Python** |  | 2.7.16 && 3.stable | Python interpreter and lib. | Packages |  |
| **Kubectl** | ~/.kube/config | 18.09.10 | Kubernetes cli to interact with K8s API. | Binary |  |
| **Ansible** | /etc/ansible.cfg | 2.8 | Ansible and ansible-playbook cmd. | Pypi package |  |
| **Ansible-lint** |  |  | Ansible linter. | Pypi package |  |
| **Ansible-tower-cli**  |  |  | CLI tool for Ansible Tower and AWX. | Pypi package |  |
| **Virtualenv**  |  |  | A tool for creating isolated 'virtual' python environments. | Pypi package |  |
| **Virtualenvwrapper** | **To ADD** | latest | A wrapper for Virtualenv. | Pypi package |  |

