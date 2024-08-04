# Obligatorio Taller de Linux

Paso a paso para la instalación del Obligatorio 

## Installation

Clonar el directorio de Git e instalar ansible 
```bash
$ git clone git@github.com:Gaston2025/Tallerjulio2024.git
# dnf install pyton3-pip
$ pip install pipx
$ pipx ensurepath
$ pipx install ansible-core
```
## Uso
```bash
$ ansible-galaxy install -r collections/requirements.yml
$ ansible-playbook -i inventory/servidores.toml hardening.yml --ask-become-pass
$ ansible-playbook -i inventory/servidores.toml webserver.yml --ask-become-pass
$ ansible-playbook -i inventory/servidores.toml todo.yml --ask-become-pass
$ ansible-playbook -i inventory/servidores.toml podman.yml --ask-become-pass
$ ansible-playbook -i inventory/servidores.toml todovinculosql.yml --ask-become-pass
$ ansible-playbook -i inventory/servidores.toml database.yml --ask-become-pass
```
## License

[MIT](https://choosealicense.com/licenses/mit/)
