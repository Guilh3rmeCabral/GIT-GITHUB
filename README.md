# GIT E GITHUB

Guia prático.

### Instalação

<a target="_blank" href="https://git-scm.com/download">Baixar Git Aqui</a>

# SCENES

- [ok] Você deseja criar pontos na história da produção do seu projeto:<br>
    <br>
    -> <strong>git init:</strong> (Vai criar um repositórop git vazio"); <br> 
    -> <strong>git add .:</strong> (Vai add o conteúdo dos arquivos ao índice "todos os arquivos");<br>
    -> <strong>git add nomeArquivo:</strong> (Vai add o conteúdo do arquivo ao índice "somente arquivo apontado");<br>
    -> <strong>git commit -m "mensagem aqui":</strong> (Vai gravar alterações no repositório);<br>
    -> <strong>git commit -am "mensagem aqui":</strong> (Vai gravar alterações no repositório e add ao mesmo tempo);<br>
    -> <strong>git log:</strong> (Vai mostrar os pontos na história do projeto);<br>

- [ok] Você deseja verificar mudanças feitas no seu projeto:<br>
    <br>
    -> <strong>git status:</strong> (Vai mostrar o status da árvore de trabalho);<br>
    -> <strong>git show 8c650010885b62c970dfd67ca16207cdffaa16cf:</strong> (Depois de dar o git log ele vai mostar um ponto na história, se pegar esse ponto e colocar ao lado do git show vai ser mostrado toda mudança que houve naquele ponto );<br>
    -> <strong>git show:</strong> (Vai mostrar o último ponto na história);<br>

- [ok] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito:<br>
    <br>
    -> <strong>git branch feature/nomeDaBranch:</strong> (Vai criar uma linha do tempo alternativa);<br>
    -> <strong>git checkout nomeDaBranch:</strong> (Vai entrar em uma branch já existente ou uma que acabou de criar);<br>
    -> <strong>git branch:</strong> (Vai mostrar todas as branchs existentes);<br>
    -> <strong>git checkout -b nomeDaBranch:</strong> (Vai criar e entrar na branch);<br>

- [ok] Você adiciona as novas funcionalidades ao seu projeto em produção: <br>
    <br>
    -> <strong>git merge nomeDaBranch:</strong> (Vai trazer a branch para a linha do tempo principal "Master");<br>

- [ok] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto:<br>
    <br>
    -> <strong>git branch -D feature/teste:</strong> (Vai deletar a branch depois dela está na linha do tempo principal "Master");<br>

- [Config/ok] Configuração de credencial, caso fique pedindo senha toda vez que for dar o push: <br>
    <br>
    -> <strong>git config credential.helper store</strong>

- [ok] Você vai pegar um projeto já iniciado, para trabalhar com o time: <br>
    <br>
    -> Vai no GITHUB pega o link do projeto e no terminal vai dar o seguinte comando: <br>
        -> <strong>git clone "link do projeto":</strong> (Vai baixar o projeto já iniciado e colocar na sua máquina); <br>

- [ATT/OK] Atualizar projeto local: ,br>
    <br>
    -> <strong>git pull</strong> (Vai atualizar o projeto local);

- [back] Você precisa voltar um arquivo para determinado momento da linha do tempo:<br>
    <br>
    -> Vai ser necessário dar o <strong>git log</strong> e pegar a linha do tempo escolhida:<br>
        -> <strong>git checkout linhaDoTempo -- arquivo:</strong> (Vai trazer de volta da determinada linha do tempo);<br>

- [Recuperar] Você precisa recuperar algo deletado:<br>
    <br>
    -> <strong>git checkout -- nomeDoArquivo:</strong> (Vai recuperar arquivo deletado);

