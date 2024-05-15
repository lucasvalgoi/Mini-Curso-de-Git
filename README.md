# Mini Curso de Git <img height="30px" width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg"/>

Neste mini curso desenvolvido pelo canal Código Fonte TV, aprendi as principais funcionalidades e conceitos do Sistema de Controle de Versão, o **GIT**

## 📚 Conceitos Aprendidos:
- Config Username & Email Global;
     - `$ git config --global user.name "#"`
     - `$ git config --global user.email "#"`
- Listar Configs Globais;
     - `$ git config --global --list`
- Criar uma nova Pasta pelo Terminal;
     - `$ mkdir nome_da_pasta`
- Criar um arquivo pelo Terminal;
     - `$ touch nome_do_arquivo`
- Navegar até a Pasta/arquivo criada;
     - `$ cd ./nome_da_pasta(ou arquivo)`
- Iniciar um repositório Git;
     - `$ git init`
- Listar todos os arquivos de uma pasta;
     - `$ ls ./nome_da_pasta`
- Abrir o VS Code pelo terminal;
     - `$ code .`
- Adicionar um ou todos os arquivos à _Staging Area_;
     - `$ git add nome_do_arquivo`
     - `$ git add .`
- Ver os status dos arquivos;
     - `$ git status`
- Discartar mundaças do diretório de trabalho restaurando a versão mais recente;
     - `$ git restore nome_do_arquivo`
- Desfazer as mudanças de um arquivo do diretório de trabalho;
     - `$ git reset nome_do_arquivo`
