## CONFIGURE A FERRAMENTA

- $ git config --global user.name "[nome]"

​    Configura o nome que você quer ligado as suas transações de commit

- $ git config --global user.email "[endereco-de-email]"

  Configura o email que você quer ligado as suas transações de commit

- $ git config --global color.ui auto

  Configura o email que você quer ligado as suas transações de commit

  ## CRIE REPOSITÓRIOS

- $ git init [nome-do-projeto]

  Cria um novo repositório local com um nome específico

- $ git clone [url]

  Baixa um projeto e seu histórico de versão inteiro

  ## FAÇA MUDANÇAS

- $ git status

  Lista todos os arquivos novos ou modificados para serem commitados

- $ git diff

  Mostra diferenças no arquivo que não foram realizadas

- $ git add [arquivo]

  Faz o snapshot de um arquivo na preparação para versionamento

- $ git diff --staged

  Mostra a diferença entre arquivos selecionados e a suas últimas versões

- $ git reset [arquivo]

  Deseleciona o arquivo, mas preserva seu conteúdo

- $ git commit -m "[mensagem descritiva]"

  Grava o snapshot permanentemente do arquivo no histórico de versão