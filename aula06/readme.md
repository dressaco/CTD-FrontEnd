### Conhecendo o GIT, GitHub e comandos.

**git config** -> usado para definir valores de configuração específicos do usuário.
*git config --global user.email [seuemail]*
*git config --global user.name [seunome]*

**git init** -> usado para criar um novo repositório GIT.

**git clone** -> usado para clonar um repositório online para sua máquina.
*git clone [url]*

**git add** -> usado para adicionar arquivos ao índice. Você pode informar um arquivo específico ou utilizar "." para adicionar todos os arquivos que estiverem pendentes.
*git add arquivo.txt*
*git add .*

**git status** -> usado para verificar o status da branch (informa que um arquivo foi criado mas não foi commitado, por exemplo.)

**git commit** -> usado para confirmar as alterações no repositório (localmente). É obrigatório informar uma mensagem para o commit, utilizando **-m**.
*git commit -m "sua mensagem aqui"*

**git push origin** -> faz o upload das alterações para o repositório online.