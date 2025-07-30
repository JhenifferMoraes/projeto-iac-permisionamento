<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=f5b100&height=180&section=header"/>

 # <img width=3% src="tux.png"/> Projeto Script Bash: Criação de Diretórios, Grupos e Usuários com Permissões
Este projeto, desenvolvido como parte das atividades do bootcamp Linux com a Santander, teve como objetivo principal este script bash que automatiza a criação de uma estrutura básica de usuários e permissões em sistemas Linux. Ele é útil para cenários de provisionamento inicial, ambientes educacionais ou controle de acesso por departamento.

### ⚠️ Principais assuntos trabalhados:

- Criação e controle de grupo

- Criação de Usuários

- Permissões e Propriedade de Diretórios

- Criação de Diretórios

### 📋Como realizar a execução:


- O script deve ser executado com permissões de superusuário (sudo).

- O pacote openssl deve estar instalado para criptografar as senhas dos usuários.

- A senha padrão utilizada é Senha123 (criptografada via openssl passwd -crypt).

- A estrutura criada é composta por:

        Diretórios: /publico, /adm, /ven, /sec

        Grupos: GRP_ADM, GRP_VEN, GRP_SEC

- Usuários:

        GRP_ADM: carlos, maria, joao

        GRP_VEN: amanda, josefina, rogerio

        GRP_SEC: debora, roberto, sebastiana

- Permissões:

        Diretórios privados recebem chmod 770 e pertencem ao grupo correspondente.

        O diretório /publico tem permissão 777, acessível a todos os usuários.



### 📋O que foi necessário para realizar este projeto:

Este projeto exigiu o uso de um terminal Linux funcional (Debian ou Ubuntu) no caso foi criada uma vm do Ubuntu 24.04.2 LTS, com permissões administrativas e acesso ao interpretador Bash. Foram explorados comandos essenciais como mkdir, groupadd, useradd, chown, chmod e openssl.

Além disso, o script foi salvo com a extensão .sh, tornado executável com chmod +x, e executado via terminal para provisionar automaticamente o ambiente proposto.

Abaixo, deixarei alguns links para downloads oficiais de tudo o que foi utilizado.

```
 VirtualBox Oracle - https://www.virtualbox.org/
```
```
 Ubuntu - https://ubuntu.com/download/desktop
```

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=f5b100&height=100&section=footer"/>
