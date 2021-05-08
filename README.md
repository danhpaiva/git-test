<h1>:star: GIT Flow</h1>

<h3>:scroll: Description</h3>
<p>The purpose of the repository is to work using the git flow.</p>

<p align="center">
    <img src="./src/git_flow.jpg" width="400"><br>
    credits image: https://www.flickr.com/photos/appleboy/5488984404
</p>

<h3>:scroll: Branch's</h3>

* feature
* develop
* release
* hotfix
* master

<h3>:scroll: Commands in git</h3>

Listar branch's:
~~~
git branch -a
~~~

Criar nova branch:
~~~
git branch MinhaNovaBrach
~~~

Criar nova branch com base em uma atual:
~~~
git branch -c branchEspecifica MinhaNovaBrach
~~~

Mudar para nova branch:
~~~
git checkout MinhaNovaBrach
~~~

Fazer commit:
~~~
git commit -m "Meu primeiro commit"
~~~

Empurrar repositório para o GitHub:
~~~
git push -u origin MinhaNovaBrach
~~~