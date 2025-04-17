# Classe_de_Heroi

class Heroi {

    constructor(nome,idade, tipo, ataque) {

    this.nome = nome

    this.idade = idade

    this.tipo = tipo

    this.ataque = ataque

    } 

}
 

const nome = "Mila";
const idade = 20;
const tipo = ["mago", "guerreiro", "monge", "ninja"]
const ataque = ["magia", "espada", "artes marciais", "shuriken"]

 


let atacar = new Heroi (nome, idade, tipo, ataque); 


 
console.log (`O herói ${atacar.nome} tem ${atacar.idade} está seguindo seu caminho para atacar.`)
console.log(`O ${atacar.tipo[0]} atacou usando ${atacar.ataque[0]}` )
console.log(`O ${atacar.tipo[1]} atacou usando ${atacar.ataque[1]}` )
console.log(`O ${atacar.tipo[2]} atacou usando ${atacar.ataque[2]}` )
console.log(`O ${atacar.tipo[3]} atacou usando ${atacar.ataque[3]}` )

