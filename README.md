# Projeto Loteca
Este é um projeto de simulador de loteria, onde o usuário digita 6 numeros e realiza um sorteio de outros 6 numeros no final é verificado quantos numeros ele acertou

## tecnologias utilzadas
- **HTML**: estrutura do site
- _CSS_: Estilização do site
- *_JS_*: funções do site
- ~~bOOTsTRAP~~: Não foi utilizado

### Melhorias possiveis
1. [X] Subir para o GitHubPages
2. [ ] Alterar os Alerts
3. [ ] Utilizar o Bootstrap
4. [ ] deixar responsivo

### Disponibilizado em 
[GitHubPage]( https://lgci12.github.io/loteca-mat-2-master/)


### Prints da tela

| ID | Primeira tela | Segunda tela | 
|----|---------------|--------------|
| 1  |loteca limpa | loteca preenchida|
| 2  | ![loteca nao preenchida ](https://user-images.githubusercontent.com/100213140/161782441-eac40b0b-d9bd-41e3-b1d7-bce663552e10.png) | ![image](https://user-images.githubusercontent.com/100213140/161782727-837fe610-c999-482d-92f1-6c0a80f450d3.png) |


#### função principal
```js: 
function sorteio (){
    var cont = 0
    numSort = []

    while(cont < 6){
        let num = Math.random() * 60
        num = Math.ceil(num)
        if(!numSort.includes(num)){
        numSort[cont] = num
        console.log(numSort)
        cont++
        }
    }
```

#### comando git
para iniciar o projeto
```bash:
git init
```
