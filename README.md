# GIT E GITHUB

Guia prático.

### Instalação

https://git-scm.com/download

# SCENES

- [] Você deseja criar pontos na história da produção do seu projeto:
    -> <strong>git init</strong> (Vai criar um repositórop git vazio");  
    -> <strong>git add .</strong> (Vai add o conteúdo dos arquivos ao índice "todos os arquivos");
    -> <strong>git add nomeArquivo</strong> (Vai add o conteúdo do arquivo ao índice "somente arquivo apontado");
    -> <strong>git commit -m "mensagem aqui"</strong> (Vai gravar alterações no repositório);
    -> <strong>git log</strong> (Vai mostrar os pontos na história do projeto);

- [] Você deseja verificar mudanças feitas no seu projeto:
    -> <strong>git status</strong> (Vai mostrar o status da árvore de trabalho);
    -> <strong>git show 8c650010885b62c970dfd67ca16207cdffaa16cf</strong> (Depois de dar o git log ele vai mostar um ponto na história, se pegar esse ponto e colocar ao lado do git show vai ser mostrado toda mudança que houve naquele ponto );
    -> <strong>git show</strong> (Vai mostrar o último ponto na história);

- [] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito:
    -> <strong>git branch feature/nomeDaBranch</strong> (Vai criar uma linha do tempo alternativa);
    -> <strong>git checkout nomeDaBranch</strong> (Vai entrar em uma branch já existente ou uma que acabou de criar);
    -> <strong>git branch</strong> (Vai mostrar todas as branchs existentes);

- [] Você adiciona as novas funcionalidades ao seu projeto em produção: 
    -> <strong>git merge nomeDaBranch</strong> (Vai trazer a branch para a linha do tempo principal "Master");

- [] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto:
    -> <strong>git branch -D feature/teste</strong> (Vai deletar a branch depois dela está na linha do tempo principal "Master");

