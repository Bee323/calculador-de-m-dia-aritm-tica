# calculador-de-media-aritmtica
//Função do Algoritmo: Calcular a média aritmética
//Autor: Erick Asafe

programa
{
	
	funcao inicio()
	{
		real nota1,nota2,nota3,nota4,media
		cadeia aluno

		escreva("Digite o seu nome:")
		leia(aluno)
		escreva("Digite a nota1:")
		leia(nota1)
		escreva("Digite a nota2:")
		leia(nota2)
		escreva("Digite a nota3:")
		leia(nota3)
		escreva("Digite a nota4:")
		leia(nota4)

		media = (nota1+nota2+nota3+nota4)/4
		
          escreva("Sua media é:" + media)
          //Verifica se a média é maior ou igual a 7
		se(media>=7) {
			escreva("\n" + "Parabéns!! você foi aprovado")
		
		}

          //Caso a média seja menor que 7
		
		senao {
			escreva("\n" + "Infelizmente você foi reprovado")
		}
	}
}

