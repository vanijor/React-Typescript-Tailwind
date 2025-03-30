## Requisitos

* Conferir a versão do Node.js 22 ou superior: node -v
* Conferir se está instalado o npx: npx -v

# Como rodar o projeto baixado

## Como enviar o projeto para o github

* Configurar o git e github
git config –global user.name “Seu Nome”
git config –global user.email “seu@email.com”
ssh-keygen -t rsa -C “seu@email.com”
cat ~/.ssh/id_rsa.pub
* Adicionar a chave pública ao github
vai no github abre as configurações e clica em SSH and GPG keys
depois clica em new SSH key, dê um nome e cole a chave pública.

* Inicia um novo repositório Git em um diretório
git init

* Criar uma mensagem de commit para as alterações, tornando-as parte do histórico do seu projeto
git commit -m "Nome do log"

* Preparar alterações em arquivos, preparando-os para o próximo commit
git add .

* Enviar as alterações para o repositório remoto
git remote add origin https://github.com/SeuNome/SeuRepositório.git

* Enviar os arquivos para o repositório remoto
git push -u origin master

* Verificar qual branch está
git branch

* Renomear a branch
git branch -M nome_atual nome_novo
