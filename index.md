# HTML
  linguagem de marcação 
    <table> Criar uma tabela 
      width= Largura da tabela
    <thead> Cabeçãlho
    <tr> Cirar uma linha dentro da tag
    <th> Define uma célula cabeçalho do grupo de células de sua tabela

#CSS
 Cascading Style Sheet 

#JavaScript
  // variaveis
const mensagem = "Oi, Tudo bem?"
// tipos de dados
  //number
  //string
// funcao
alert(mensagem)

//objeto javascript
const participante = {
  nome: "Mayk Brito",
  email: "mayk@gmail.com",
  dataIscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}

// array
let participantes = [
 {
  nome: "Mayk Brito",
  email: "mayk@gmail.com",
  dataIscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00),
},
]

// estrutura repetição - loop
  for(let participante of participantes){
    //faça alguma coisa
    output = output + criarNovoParticipante(participante)
  }


//condicional
  if(participante.dataCheckIn == null) {
    dataCheckIn = 