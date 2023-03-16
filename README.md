# GIT E GITHUB

Guia prático.

### Instalação

https://git-scm.com/download

# SCENES

- [ok] Você deseja criar pontos na história da produção do seu projeto:<br>
    -> <strong>git init:</strong> (Vai criar um repositórop git vazio"); <br> 
    -> <strong>git add .:</strong> (Vai add o conteúdo dos arquivos ao índice "todos os arquivos");<br>
    -> <strong>git add nomeArquivo:</strong> (Vai add o conteúdo do arquivo ao índice "somente arquivo apontado");<br>
    -> <strong>git commit -m "mensagem aqui":</strong> (Vai gravar alterações no repositório);<br>
    -> <strong>git log:</strong> (Vai mostrar os pontos na história do projeto);<br>

- [ok] Você deseja verificar mudanças feitas no seu projeto:<br>
    -> <strong>git status:</strong> (Vai mostrar o status da árvore de trabalho);<br>
    -> <strong>git show 8c650010885b62c970dfd67ca16207cdffaa16cf:</strong> (Depois de dar o git log ele vai mostar um ponto na história, se pegar esse ponto e colocar ao lado do git show vai ser mostrado toda mudança que houve naquele ponto );<br>
    -> <strong>git show:</strong> (Vai mostrar o último ponto na história);<br>

- [ok] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito:<br>
    -> <strong>git branch feature/nomeDaBranch:</strong> (Vai criar uma linha do tempo alternativa);<br>
    -> <strong>git checkout nomeDaBranch:</strong> (Vai entrar em uma branch já existente ou uma que acabou de criar);<br>
    -> <strong>git branch:</strong> (Vai mostrar todas as branchs existentes);<br>

- [ok] Você adiciona as novas funcionalidades ao seu projeto em produção: <br>
    -> <strong>git merge nomeDaBranch:</strong> (Vai trazer a branch para a linha do tempo principal "Master");<br>

- [ok] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto:<br>
    -> <strong>git branch -D feature/teste:</strong> (Vai deletar a branch depois dela está na linha do tempo principal "Master");<br>

<style>
    strong {
        color: red;
    }
</style>
