# primeira_avalicao

//checkpoint1

let pipoca = 10;
let macarrao = 8;
let carne = 15;
let feijao = 12;
let brigadeiro = 8;

function tempoPipoca (tempo) {

  if(tempo <= pipoca * 2) {
     return "A comida queimou";
 } if(tempo < pipoca ) {
    return "tempo insuficiente";
 } if(tempo >= pipoca * 3) {
   return "kabumm";
 }

}

console.log(tempoPipoca(5));
console.log("Prato pronto, bom apetite!!!");

function tempoMacarrao (tempo) {

    if(tempo <= 8 * 2) {
       return "A comida queimou";
   } if(tempo < macarrao ) {
      return "tempo insuficiente";
   } if(tempo >= 8 * 3) {
     return "kabumm";
   }
  
  }

  console.log(tempoMacarrao());
  console.log("Prato pronto, bom apetite!!!");

function tempoCarne (tempo) {

    if(tempo <= 15 * 2) {
       return "A comida queimou";
   } if(tempo < carne ) {
      return "tempo insuficiente";
   } if(tempo >= 15 * 3) {
     return "kabumm";
   }
  
  }

  console.log(tempoCarne());
  console.log("Prato pronto, bom apetite!!!");

function tempoFeijao (tempo) {

    if(tempo <= 12 * 2) {
       return "A comida queimou";
   } if(tempo < feijao ) {
      return "tempo insuficiente";
   } if(tempo >= 12 * 3) {
     return "kabumm";
   }
  
  }

  console.log(tempoFeijao());
  console.log("Prato pronto, bom apetite!!!");

function tempoBrigadeiro (tempo) {

    if(tempo <= 12 * 2) {
       return "A comida queimou";
   } if(tempo < brigadeiro ) {
      return "tempo insuficiente";
   } if(tempo >= 12 * 3) {
     return "kabumm";
   }
  
  }

  console.log(tempoBrigadeiro());
  console.log("Prato pronto, bom apetite!!!");
