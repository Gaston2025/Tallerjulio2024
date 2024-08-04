# Obligatorio Taller de Linux

Paso a paso para la instalación del Obligatorio 

## Installation

Clonar el directorio de Git e instalar ansible 
```bash
$ git clone git@github.com:Gaston2025/Tallerjulio2024.git
# sudo install pyton3-pip
$ pip install pipx
$ pipx ensurepath
$ pipx install ansible-core
```
## Uso
```bash
$ ansible-galaxy install -r collection/requirements.yml
$ ansible-playbook -i inventory/servidores hardening.yml
$ ansible-playbook -i inventory/servidores webserver.yml 
$ ansible-playbook -i inventory/servidores todo.yml
$ ansible-playbook -i inventory/servidores podman.yml 
$ ansible-playbook -i inventory/servidores todovinculossql.yml 
$ ansible-playbook -i inventory/servidores database.yml
```
## License

[MIT](https://choosealicense.com/licenses/mit/)
