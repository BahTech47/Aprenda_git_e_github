# Aprenda Git e Github

GIT e Github são 2 ferramentas muito utilizadas no mundo da programação atualmente e que, basicamente, existem para auxiliar os programadores  a se organizarem, compartilharem seus códigos ou até mesmo aprender programação.

> 📹 Confira o nosso vídeo no YTB: *link*

## Git

O git permite que possamos organizar e salvar todas as modificações dos códigos de forma contínua (acompanhando o progresso), sendo possível a modificação da programação sem perder a linha de raciocínio ou o código propriamente dito.

É através dos Git commands que possamos controlar todos o versionamento do nosso código. Alguns deles são:

1. Git Clone: 

Com esse comando é possível baixar um repositório remoto, seja do Github ou BitBucket, na sua máquina

Existem outras formas de baixar um repositório remoto. Uma das mais utilizadas pelos programadores é utilizado uma URL HTTPS:

```
git clone <https:/name-of-the-repository-link>
```

2. Git Branch

Branches são como se fossem áreas de trabalho de um projeto. Com as branches programadores podem trabalhar simultaneamente em um projeto porém em diferentes tarefas.

O comando ```git branch ``` pode ser utilizado para criar uma nova branch, listar ou deletar.

**Criar uma nova branch**

```
git branch <branch-name>
```

Esse comando irá criar uma branch localmente na sua máquina. Para fazer o upload na nova branch para o repositório remoto, no Github utilize:

```
git push -u <remote> <branch-name>
```

**Para listar as branchs**

```
git branch or git branch --list
```

**Deletar uma branch**

```
git branch -d <branch-name>
```

3. Git Add

Quando criamos algum arquivo, modificamos ou deletamos alguma linha de código estas mudanças são registradas no nosso computador na pasta .git, assim podemos escolher quais arquivos adicionar no commit do nosso projeto e para escolher ou enviar todos arquivos temos as seguintes comandos:

**Para adicionar um único arquivo**

```
git add <file>
```

**Para adicionar todos os arquivos**

```
git add -A
```

4. Git commit

Para salvar as mudanças do nosso código em versões, de fato, utilizamos o git commit. Este comando é como se fosse um checkpoint do nosso código. É possível identificar os commits com mensagens para facilitar na hora de conferir as versões do código

```
git commit -m "commit message"
```

**Importante!** O Git commit salva as modificações localmente

5. Git push

Após comitar todas as mudanças, podemos envia-las para o nosso repositório remoto. O Git push realiza o upload dos commits no repositório remoto.

```
git push <remote> <branch-name>
```

**Podemos também selecionar a branch para a qual o código será redirecionado**

## Github

Explicação do que é Github


