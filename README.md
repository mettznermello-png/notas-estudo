# notas-estudo
Minhas notas de estudos do tec SENAC 2026

## Configurando o GIT

Codes Needed to change the PC:

```bash
git config --global user.name
git config --global user.email
```
```bash
git –version
git config –global user.name “Joao Mello”
git config –global user.email “mettznermello@gmail.com”
```

## How to create a repositerie

```bash
Go to the site on Google Chrome "Github" open the charecter
Go through to "New" and then repositerie
Put on public always
Turn on README.md
wait to the paste apear
open the Git Bash
put the code "cd Doc *tab*" The initias of the paste *tab*
```

## How to create a key on Github

Follow the steps:

```bash
ls -al ~/.ssh
ssh-keygen -t ed25519 -C “mettznermello@gmail.com”
eval “$(ssh-agent -s)”
ssh-add ~/.ssh/id_ed25519
clip <~/.ssh/id_ed25519.pub
```

## codes to use on diary day sunny day

```bash
control + K + O: open the "open folder"
```





                    1º
```bash
const idade = Number(prompt("Qual é a sua idade?"))
const resultado1 = idade*12
const resultado2 = idade*365
alert(resultado1 + "meses")
alert(resultado2 + "dias")
```

```bash
function exercicio2() {
    const valorHora = Number(prompt("Digite o valor por hora:"))
    const horasTrabalhadas = Number(prompt("Digite suas horas Trabalhadas:")) 
    const resultado = valorHora*horasTrabalhadas
    alert("seus salário é:" + resultado)
}
const buttonExercicio2 = document.getElementById("exercicio2")
buttonExercicio2.addEventListener('click', () => {
    exercicio2()
}) 
// addEventListener
```
```bash
 <button id="exercicio3" >Exercicio 3</button>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style/styles.css">
    <title>Document</title>
</head>
<body>
    <header id="exemplo" >
        um titulo qualquer
    </header>

    <main>
        <h2>Minha pagina de exercicios</h2>
        <button id="exercicio1" >Exercicio 1</button>
        <button id="exercicio2" >Exercicio 2</button>
        <button id="exercicio3" >Exercicio 3</button>
        <button id="exercicio4" >Exercicio 4</button>
        <button id="exercicio5" >Exercicio 5</button>
        <button id="exercicio6" >Exercicio 6</button>
        <button id="exercicio7" >Exercicio 7</button>
        <button id="exercicio8" >Exercicio 8</button>
        <button id="desafio0" >Desafio 0</button>
        <button id="desafio1" >Desafio 1</button>
        <button id="desafio2" >Desafio 2</button>
        
    </main>

    <footer id="footer" >
        todos os direitos reservados - Joao Francisco Mello - 2026
    </footer>
    <script src="./script/desafio2.js"></script>
</body>
</html>
```

```bash
const footer = document.getElementById("footer")
//footer.style.color = "blue"

const novoTitulo = document.createElement("h2")
novoTitulo.textContent = "Um Novo Titulo"
//console.log(novoTitulo)

footer.appendChild(novoTitulo)
// getElementById = puxa um elemento do HTML

const header = document.getElementById("exemplo")
header.appendChild(novoTitulo)


//const button = document.getElementById('my-button');
//button.addEventListener('click', () => {
//    alert('button was clicked');
//});
header.addEventListener("click", () => {
    alert("it's going down now, just let's us adore you")
})
```

```bash
const nota1 = Number(prompt("digite sua primeira nota:"))
const nota2 = Number(prompt("digite sua segunda nota:"))
const nota3 = Number(prompt("digite sua terceira nota:"))

const media = (nota1+nota2+nota3)/3
//console.log(media)
//console está no f12 na aba console
if (media < 3 ) {
    alert("Melhore (é sério)")
} else if ( media >= 3 && media <= 7 ) {
    alert("Dá pra melhorar")
} else if (media > 7 && media <= 10) {
    alert("Exelente, merece uma balinha")
} else {
    alert("Essa nota não existe")
}
```