# Documentação de git
![git_banner](https://github.com/eugeniobr25/Estudo_de_Layout_com_CSS_Flex_e_Grid/assets/132760301/fe90ded4-5a7f-45f5-9740-138283a40152)

## Comanandos de Git
Principais comandos do git para ajudar no dia a dia. 
<hr>
<br>

### Inicia o arquivo ".git/" para controlar a pasta.

````
git init
````
<hr>
<br>

### Validar os arquivos modificados dentro do projeto
````
git status
````

##### - Vermelho: Mostra os arquivos adicionados, modificados ou excluidos. 
##### - Verde: Mostra os arquivos que foram adicionados pelo "git add", que estão preparados para serem commitados. <font color="#ffff00">
<hr>
<br>

### Coloca o arquivo modificado em uma area segura.
````
git add <nome_do_arquivo.extensão>
````
<hr>
<br>

### Criar uma nova versão do projeto com as referencias do criador.
````
git commit -m "<texto_da_modificação"
````
<hr>
<br>

### Validar os meus comentarios e modificações.
````
git log
````
<hr>
<br>

### Cria uma nova branch/ramificação.
````
git checkout -b <nome_da_nova_branch>
````
<hr>
<br>

### Muda de branch/ramificação.
````
git checkout <nome_da_branch>
````
<hr>
<br>

### Adiciona a branch atual o conteúdo de outra(s) branch(s).
````
git merge <nome_da_branch>
````
<hr>
<br>

### Baixa o projeto do repositório.
````
git clone <url>
````

### Envia alteração para o repositório.
````
git push
````
<hr>
<br>

### Puxa as alterações do repositório.
````
git pull
````
<hr>
<br>

### Paniel para visualização das branchs e suas respectivas alterações.
````
gitk
````
# Erros: 
````
git config --global user.name "<seu_nome>"
````
````
git config --global user.email "<seu_email>"
````

### Apagando as credencias, gerenciamento de credenciais
````
ERRO:403
````
