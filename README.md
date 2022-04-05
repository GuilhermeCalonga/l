# Projeto Loteca 
Este é um projeto de simulador de loteria, onde o usuario digita ate 6 numeros 
e realiza um soretio de outros 6 numeros e é verificado quantos nuemros ele acertou.
## Tecnologias Utilizadas 
-**HTML**: estrutura 
-_CSS_: estilo
-_*_JS_*: Funcoes 
-~~bootStrap~~: Nao foi utilizado
### Melhorias Possiveis
1.[]Subir para GitHubPAGEs
2.[]Alterar os alerts
3.[] Utilizar o Bootstrap
4.[]deixar responsivo
### Disponibilidade em 
[GitHubPage]( https://guilhermecalonga.github.io/loteca_GUI/)

### Prints Da Tela 
|  ID |   Primeira Tela | Segunda Tela | 
|-----|-----------------|--------------|
| 1 | Loteca Limpa | Loteca Preenchida |
| 2 | ![image](https://user-images.githubusercontent.com/101648142/161781625-eb0946e6-3bba-44cf-9d18-2958c3e08362.png) | ![image](https://user-images.githubusercontent.com/101648142/161782562-eaa20a44-3c92-42b5-aa68-33b17b64af77.png|

#### Função Principal
```js:
var  numSort  = [ ] 
var  numEsco  = [ ]
função  sorteio ( ) {
    var  cont =  0
    numOrdenar = [ ]
    
    enquanto ( cont  <  6 ) {
        deixe  num  =  Math . aleatório ( )  *  60
   num =  matemática . teto ( num )
   if ( ! numSort . inclui ( num ) ) {
    numSort [ cont ] = num
    consola . log ( numSort )
    cont ++
   }
  
    }
    documento . getElementById ( "sorteados" ) . innerHTML = numSort
   
}
 

```
#### Comando Git
Para Iniciar o Projeto
```bash:
git init 

```
