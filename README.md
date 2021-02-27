# Fundamentos Git

- Comando: ```` git config user.name "seu usuário" ````
    - Esse comando é utilizado para configurar com qual nome os seus commits serão exibidos
    - Caso queira ver como ficou configurado, digite: ```` git config user.name ````

- Comando: ```` git config user.email "seu email" ````
    - Mesmo conceito do comando anterior, porém para configurar o seu email.
    - Caso queira ver como ficou configurado, digite: ```` git config user.mail ````
    
- Comando: ```` git init ````
    - Cria um repositória na pasta atual onde o comando foi executado

- Comando: ```` git status ````
    - Mostra como está o status atual do repositório, se possui novas atualizações a serem baixadas, etc

- Comando: ```` git add ````
    - inclui as modificações realizadas em sua máquina que não estão no seu repositório
    - Variações do git add: ```` git add * ````, ```` git add *.txt ````, ```` git add nome_do_arquivo ````

- Comando: ```` git commit -m "mensagem do commit" ````
    - vai salvar as alteracoes que você realizou no seu projeto e as modificações estão prontas para subirem para o repo.
    - é importante deixarmos uma mensagem clara para identificação das alterações.

- Comando: ````git commit --amend -m "mensagem"````
    - Este comando edita o último commit, e não faz um novo commit.

- Comando: ```` git diff ````
    - este comando lista as modificações que ocorreram nos arquivos do projeto. em vermelho as remoções e em verde as adições.

- Comando: ````git log```` 
    - este comando mostra o histórico de todos os commits, você pode utilizar a chave para reverter um commit ou trabalhar naquele commit novamente

- Comando: ````git checkout --````
    - esse comando fará o arquivo que vc definiu voltar o status original

- Comando: ````git tag````
    - Caso você tenha tags no seu repo, esse comando irá mostrar as tags

- Comando: ````git lag -a v1.0 -m "versão 1.0"````
    - comando para criar uma tag nova

- Comando: ````git show v1.0````
    - Esse comando irá mostrar informações da tag que for informada

- Comando: ````git checkout v1.0````
    - você altera seu estado de edição para a tag selecionada

- Comando: ````git tag -d v1.0````
    - Deleta a tag informada

- Comando: ````git branch nome_da_branch````
    - este comando irá criar uma branch, será necessário navegar para dentro dela utlizando o comando ````git checkout nome_da_branch````
    - Esse caminho pode ser encurtado utilizando o comando ````git checkout -b nome_da_branch````, esse caminho irá criar e modificar a branch atual para a branch que acabou de ser criada.

- Comando: ````git merge branch_que_possui_alteracoes````
    - esse comando irá migrar as modificacoes da branch informada para a branch atual.

- Comando: ````git branch -d nome_da_branch````
    - Comando para deletar a branch informada