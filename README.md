# primeiro-repositorio
 
 ## informações sobre Git e Github
 <p>comandos importantes para o uso e manutenção do Git/Github</p>

### inicia um novo repositório
<code>git init</code>

### criar repositório remoto
<code>git remote add origin (URL_REMOTO) </code>
### adicione um novo arquivo/diretorio ao branch
<code>git add (arquivo/diretorio)</code>
<p>ou adiciona tudo que não estiver no .gitignore</p>
<code>git add *</code>

### manda os arquivos criados e modificados do repositório local para o repositório stage
<code>git commit -m "Mensagem"</code>

### manda da maquina local para o servidor Github
<code>git push origin (branch)</code>

### puxa um repositório que ja se encontra na maquina local do servidor
<code>git pull origin (branch)</code>

### clona um repositório remoto na maquina local
<code>git clone (link https, ssh)</code>

### junta os arquivos modificados com os nao modificados
<code>git merge (branch)</code>
<p>obs: resolver algum possivel conflito</p>

### cadastrar email e name na maquina local, para que apareça no commit do site Github corretamente
<code>git config --global user.email "email@email.com</code><br>
<code>git config --global user.name "nickname da conta"</code>

### link do tutorial de como cadastrar uma nova chave SSH
<a href="https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent">Github Docs</a>

## links para formatar o arquivo markdown
<a href="https://www.w3schools.com/html/">w3schools html</a></br>
<a href="https://www.markdownguide.org/basic-syntax/">markdownguide</a>