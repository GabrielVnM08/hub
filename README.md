Tutorial Git e GitHub.

git config --list - exibi uma lista de todas as configurações do Git em seu sistema, incluindo as informações do usuário configuradas.

git init - usado para inicializar um novo repositório Git vazio em um diretório existente.

git add - usado para adicionar arquivos ou diretórios ao índice do Git (também conhecido como área de staging), preparando-os para serem incluídos em um commit posterior.

git status - usado para exibir o status atual do seu repositório Git. Ele mostra quais arquivos foram modificados, quais estão prontos para serem commitados e quais ainda não foram adicionados ao índice.

git commit -m - é usado para criar um novo commit com as alterações preparadas no staging. Um commit é uma snapshot das alterações feitas nos arquivos do seu repositório em um determinado momento. (obs: para usar o commit é preciso antes ter adicionado algo à área de staging.)

git branch -m "antigo-nome" "novo-nome" - usado para alterar o nome da branch.
git branch -m "novo-nome" - caso ja esteja na branch que deseja alterar.

git remote add origin https://github.com/GabrielVnM08/hub.git - Este comando adicionará o repositório remoto com o apelido "origin" ao seu repositório local e apontará para o URL especificado.

git push -u origin master - usado para enviar as alterações do seu repositório local para um repositório remoto e configurar uma associação de upstream entre os dois repositórios.