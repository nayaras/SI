# SI
Trabalho Final


**Clonar projeto do heroku:** <br />
heroku git:clone -a nome-do-app <br /> <br />
**Atualizar projeto com nova versão do github** <br />
**1.** Acessar pasta (Se a pasta veio do clone do heroku, provavelmente o nome da pasta será o nome do app. Se veio do clone do github, será o nome do repositório)<br />
```
cd nome-pasta-app 
```
**2.** Atualizar seu repositório local fazendo merge das novas atualizações do repositório no GitHub: <br />
```
git pull origin master 
```
**3.** Subir atualização pro heroku (deploy): <br />
```
git push heroku master 
```
**4.** Abrir app: <br/>
```
heroku open
```
