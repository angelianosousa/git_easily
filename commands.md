# Commands for Git

~~~
git log
~~~
> Ao executar esse comando vai aparecer o histórico do seu repositório desde o seu primeiro commit, junto de cada comentário e por quem ele foi adicionado, isso é muito útil para acompanhar o desenvolvimento do time e visitar commits especificos para acompanhar de perto os trabalhos individualmente
~~~
git diff
~~~
> Esse comando mostra o que foi feito dentro do seu **Working Tree** exibindo desde as linha que foram adicionadas/deletadas em cada arquivo modificado. 
> Você pode adicionar comandos como **--staged** para filtrar os resultados, nesse caso seria mostrado somente os arquivos que estão na **Stage Area**
~~~
git restore <file_name>
~~~
> A ideia aqui é remover o arquivo nomeado da **Stage Area**
~~~
git rm <file_name>
~~~
> O arquivo selecionado é apagado totalmente, no entanto é possível recuperar com um comando git caso você se arrependa

~~~
git mv <file_name> <new_name_filename>
~~~
> Esse comando serve para renomear arquivos trocando o primeiro valor para o segundo

> Esse mesmo comando pode ser usado para move arquivos entre pastas bastando você colocar o path antes no nome do arquivo de destino, se seguirmos o exemplo acima o comando é para ser parecido com isso: **git mv <file_name> /pasta/<file_name>**