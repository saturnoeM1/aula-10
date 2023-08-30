# aula-10
aula-função
//função
//exercicios 2
 function imprimirOlaMundo(){console.log("Ola mundo");}

 imprimirOlaMundo();

 function escreveNome(nome){console.log(nome);}

 let meuNome = "Emily";
 escreveNome(meuNome);
 

 const a = 1

 function imprimeVariavel (){const b = 2
    console.log('Variavel a', a)
    console.log('Variavel b', b)
}

imprimeVariavel()

console.log('Variável a', a)
console.log('Variável b', b)


function calculaArea(altura, largura){
    const area = altura * largura;
    return area;
}
const areaCalculada = calculaArea(5, 8);

console.log("Variavel areaCalculada:"+
    areaCalculada);
console.log("Chamada da função crua: " +
    calculaArea(5, 8));

//exercicio 3

function somaValores(a,b){
     return a + b;
}
const resultadoDaSoma  = somaValores(2,4);
console.log("O resultado da soma é: "+
    resultadoDaSoma);

    //exercicio 4
    function receberArray(g){
        let h = [(g[0] /2),(g[g.length-1] /2)];

        return h;
    }
     let i = [2,4,6,8,10,12,14,16,18];

     const resultado = receberArray(i)
     console.log(resultado);
    
    */
