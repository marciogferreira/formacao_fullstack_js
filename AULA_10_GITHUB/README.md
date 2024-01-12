AULA - GIT E GITHUB

#### Objetivos desta Aula
```
    1. Criação de Repositório
    2. Clonagem de Repositório
    3. Autorizações para colaboradores do repositório
    4. Contribuição em projetos de terceiros com Pull Request.
```

#### 1. Subindo seu projeto no Github

``` 
    # Comando para iniciar git no seu projeto
    git init

    # Comando add . prepara todos os arquivos do diretório para subir.
    git add .

    # Comando commit assina os arquivos com esse comentário para registrar o que foi atualziado.
    git commit -m "Comentário"

    # Comando branch -M main faz referência a branch main para ser a principal
    git branch -M main

    # Comando remote add origin informa ao nosso diretório para qual repositório os arquivos irão.

    # Comando push autentica com o github e envia os arquivos.
    git push -u origin main
```


#### 2. Clonando qualquer repositório para sua máquina

```
    # Comando para clonar qualquer repositório
    git clone url_do_repositorio
```

#### 3. Dando autorização para os time de desenvolvimento trabalhar em seu projeto.

<small>
<ol>
    <li>Clique em seu repositório</li>
    <li>Clique na Aba Settings</li>
    <li>Clique no menu Lateral na opção Collaborators</li>
    <li>Sem seguida, informe o e-mail do github de seu/sua dev e aguarde ele/ela aceitar o convite</li>
</ol></small>

#### 4. Contribuindo com projetos de terceiros enviando Pull Request
<small><ol>
    <li>Acesse o repositório que você deseja contribuir.</li><li>Clique no botão Fork. Com isso, o github irá confirmar se você deseja puxar o projeto para seu repositório. Você deve confirmar.</li>  <li>Após puxar o projeto para seu repositório, você deve clonar para sua máquina e trabalhar normalmente.</li>    <li>Após realizar seus ajustes, voce deve subir para seu repositório dando os comandos:
    </li> </ol></small>

```
    git add .
    git commit -m "Comentário do que foi feito"
    git push -u origin main
```

<small><ol start="5">
    <li>Após subir, você deve ir no seu repositório e clicar em commit ahead. Assim você irá poder submeter as suas alterações para o repositório original de onde puxou o projeto. Somente com a confirmação do administrador do projeto é que suas alterações estará disponível para todos que utilizam o repositório</li></ol></small>


