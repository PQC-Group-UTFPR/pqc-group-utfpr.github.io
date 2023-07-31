# pqc-group-utfpr.github.io

Welcome to the webpage for the PQC Research Group at the [UTFPR](http://portal.utfpr.edu.br/campus/toledo), Toledo Campus.

# Contribution Guide (in Portuguese)

O primeiro passo é criar uma conta no github e encaminhar por email para ser adicionado ao github do grupo.

Após aceitar o convite, para adicionar suas informações na página `group_members.html`, faça o seguinte:
1. Download do repositório (pelo navegador ou via `git clone https://github.com/PQC-Group-UTFPR/pqc-group-utfpr.github.io`
2. Crie uma branch com o seu nome: `git checkout -b seu-nome` (pode ser feito direto no passo 3 abaixo)
3. Edite o arquivo `group_members.html`, pelo navegador (logado na conta do github) ou pelo seu editor/IDE:
3.1 Encontre o código abaixo
```
<!-- Student template here      
       <div class="col-md-6 mx-auto">
          <div class="client_container ">
            <div class="client_id">
              <div class="img-box">
                <img src="images/team-fotos/SUAFOTOAQUI.jpg" alt="">
              </div>
              <div class="client_name">
                <h5>
                  Seu nome aqui
                </h5>                  
                <h6>
                  Undergratuate Student in <Computer Engineering> <br>
                  Personal page : <a href="linkaqui" target="blank"> link </a>               
                </h6>
              </div>
            </div>
          </div>
        </div>
      </div>
-->
```
3.2 Copie-o e cole logo abaixo da marcação `-->`
3.3 Remova as marcações do código copiado `<!--` e `-->`
3.4 Substitua `Seu nome aqui` pelo seu nome, troque `<Computer Engineering>` pelo seu curso, e, opcionalmente, insira o link da sua página, github, linkedin ou o que preferir;
3.5 Faça o commit em uma nova branch (pelo navegador, selecione "Create a new branch for this commit and start a pull request" informando um nome para sua branch nova) ou pelo terminal: `git add group_members.html`, `git commit -m "Add Info.`, `git push` [explicação aqui](https://blog.betrybe.com/git/git-push/)
3.6 Verifique suas alterações no repositório (navegador) e finalize o [pull request](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).
