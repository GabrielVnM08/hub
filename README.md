Tutorial Git e GitHub.

git config --list - exibi uma lista de todas as configurações do Git em seu sistema, incluindo as informações do usuário configuradas.

git status - usado para exibir o status atual do seu repositório Git. Ele mostra quais arquivos foram modificados, quais estão prontos para serem commitados e quais ainda não foram adicionados ao índice.

git init - usado para inicializar um novo repositório Git vazio em um diretório existente.

git add - usado para adicionar arquivos ou diretórios a área de staging do Git, preparando-os para serem incluídos em um commit posterior.
git add . - adiciona todos os arquivos.

git commit -m - é usado para criar um novo commit com as alterações preparadas no staging.

git branch -m "antigo-nome" "novo-nome" - usado para alterar o nome da branch.
git branch -m "novo-nome" - caso ja esteja na branch que deseja alterar.
git checkout "branch" - altera a branch.
git checkout -b "nova-branch" - adiciona nova branch.

git remote add origin https://github.com/GabrielVnM08/hub.git - Este comando adicionará o repositório remoto com o apelido "origin" ao seu repositório local e apontará para o URL especificado.

git push -u origin master - usado para enviar as alterações do seu repositório local para um repositório remoto e configurar uma associação de upstream entre os dois repositórios.

git merge "branch alterada" - isso fará com que a alteração feita em uma branch seja atribuida a branch principal(OBS: é preciso estar na branch principal, para as alterações da outra branch atualizar na principal.)

git clone "link do repo" - faz uma clonagem no repositório do GitHub para um diretório local.
git pull - após ter cloonado um repositório, isso faz com que quaalquer alteração feita após o git clone, seja atualizada na maquian local.


#Vizualizar user#
git config user.name
git config user.email

#Alterar user#
git config --global user.name "seunome"
git config --global user.email "seuemail@example.com"
