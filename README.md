*2. Monte uma matriz para quando o usuário informar um número correspondente a um mês, imprima o número, 
 * o nome do mês indicado em português, abreviatura
*nome do mês em inglês.
*Por exemplo, o usuário digita o número 4 e o programa mostra:
4 → Abril, abril, abril.
 */

programa
{
		
	inteiro num1
	
	
	funcao inicio()
	{	
			escreva("Digite o número correspondente ao Mês escolhido: \n") //Usuario escolhe um número
			leia(num1 )
                                                                     //Atribuição de valores encadeados na Matriz Mêses.
	cadeia ms_mat[3][13] = {{"Mês","Janeiro","Fevereiro","MArço","Abril","Maio","Junho","Julho","Agosto","Setembro", "outubro","Novembro","Dezembro"},
						{"Month","jan","Fev","MAr","Abr","MAi","Junh","Julh","Agos","Set","Out","Nov","Dez"},
							{"Mth","January","February","MArch","April","May","June","July","August","September","October","November","December"}}

		para(inteiro l = 0; l <= 11; l++){                  //Para:leitura linha
                                                              
		para(inteiro c=0; c <=2; c++){	                    //Para:Leitura Coluna

			escreva ("→" + ms_mat[c][num1]+" ")                //Valor da busca a ser escrito na tela:
		}
		pare
		}
		
	}
	
	
}
