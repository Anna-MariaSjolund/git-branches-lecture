# git-branches-lecture

Vi lägger till första raden och commitar

### branches

Nu skapar vi en branch som heter instructions
Detta gör vi med hjälp av kommandot:

```md
git checkout -b instructions
```

För att pusha upp ändringar till denna branch måste vi först stage, commit och pusha. För push till denna branch gör vi: 

```md
git push origin instructions
```

För att checka branches som vi har:

```md
git branch
```

### pull requests

För att få mergea in ändringar från denna branch in till main, så öppnar vi en pull request. Detta gör vi i fliken pull request.

<img src="assets/pull_request.png" width = 400>

## merge

Efter pull request är det viktigt att varje person kör en pull till sin main branch och pull till sin egna branch. 
