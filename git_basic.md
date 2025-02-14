# comandos basicos do git
#coloca seu nome#
``git config --global user.name "Seu Nome"``

#inclui a credencial do seu e-mail#
``git config --global user.email "seu_email@example.com"``

``git init`` -> inicializa o repositorio local

``git status`` -> exibe se os arquivos/pastas estao adicionados ao repositorio

`git add NomeDoArquivo` -> voce adiciona o arquivo

`git add .` -> vc adiciona todos os arquivos odificados/cirados no repositorio local

`git branch -M main` -> altera o nome da branch principal de master para main

`git commit -m "messagem de atualizaçao"` -> crie um commit para que seja ralizado um novo versionamento

`git log` -> lista todods os commit que foram realizados.
`git log --oneline --graph --decorate` -> forma compacta de exibir os commits

`git remote add origin` https://github.com/jpftinoco/senac_shoes.git ->realiza o sicronizaçao do repositorio local com o remoto

`git push -u origin main` -> envia as informaçoes do local para o remoto