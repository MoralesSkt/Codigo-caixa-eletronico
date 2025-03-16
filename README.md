programa{
	funcao inicio(){

		real saldo =1000
		inteiro opcao
		real saque

		enquanto(verdadeiro){
			escreva("=====Caixa Eletronico=====\n")
			escreva("1 - Consultar Saldo\n")
			escreva("2 - Sacar Saldo\n")
			escreva("3 - Sair\n")
			escreva("Escolha uma opção: \n")
			leia (opcao)

se(opcao == 1){
    escreva("Seu saldo atual é R$ ", saldo, "\n")
}
senao se(opcao == 2){
    escreva("Digite o valor para saque: ")
    leia(saque)
    se(saque>saldo)
    escreva ("Valor para saque insuficiente, por favor selecione um valor para saque")
    se(saque<saldo)
    escreva("Saque realizado com sucesso!\n")
    saldo = saldo - saque

     escreva("Seu novo saldo agora é de" ,saldo, "\n")
     escreva ("obrigado por usar o Caixa Eletronico\n")}

  se(opcao == 3){
  
  escreva ("Saindo...\n")

pare!

}

    }
  }
}

      
    
  
