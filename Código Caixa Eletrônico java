package caixa.eletronico;

import java.util.Scanner;

public class CaixaEletronico {

    public static void main(String[] args) {

        Scanner ler = new Scanner(System.in);
        int []extrato = new int [100];
        String []extract = new String [50];
        int cpfv, deposito = 0, saque = 0,transferencia = 0, conta, agencia, debito = 0,credito = 0, creditox = 0, numero = 0;
        int iSaldo = 0, iDeposito = 0, iSaque = 0, iPagamentos = 0, iTransferencia = 0;
        String banco;
        String a = " ", b = " ", c = " ", d = " ", e = " ";
        int exa,exb,exc,exd,exe;
        float senhav;
        float senha = (float) 1020304l;
        int cpf = (int) 12345678900l;
        int saldo = 1000;
        extrato[20]=saldo;
        int menu, deposito1 = 0, saque1 = 0;
        
               
      
        System.out.println(" |     ________________________________________");
        System.out.println(" |      BEM-VINDO AO BANCO CENTRAL DA FACENS       ");
        System.out.println(" |");
        System.out.println(" |  LOGIN   ");

        for (int i = 1; i > 0; i++) {
           System.out.print(" | CPF: ");
            cpfv = (int) ler.nextLong();
            
            if (cpf == cpfv) {
                i = i - 9;
            } else {
                System.out.println(" | CPF INVALIDO");
            }}
            
            System.out.print(" | SENHA: ");
            senhav = (float) ler.nextLong();
            if (senha != senhav){ 
                System.out.println(" |     ____________________________________");
                System.out.println(" | ");
                System.out.println(" |                SENHA INVALIDA.               ");
                System.out.println(" | ");
                System.out.print(" | Digite A Senha Novamente: ");   
                senhav = ler.nextInt();
            }
            
                if (senha != senhav){
                System.out.println(" | ");
                System.out.println(" | MUITAS TENTATIVAS");
                System.out.println(" | ");
                System.out.println(" |               CONTA BLOQUEADA           ");
                System.out.println(" |      ____________________________________");
                }
            
            else {

        System.out.println(" |     ____________________________________");
        System.out.println(" |                BEM-VINDO AO MENU         ");
        System.out.println(" | ");
        System.out.println(" |      INSTRUÇÓES DO MENU:");
        System.out.println(" | ");
        System.out.println(" | -Aperte 1 Para Consultar Saldo Atual.");
        System.out.println(" | ");
        System.out.println(" | -Aperte 2 Para Fazer um Depósito.");
        System.out.println(" | ");
        System.out.println(" | -Aperte 3 Para Fazer um Saque.");
        System.out.println(" | ");
        System.out.println(" | -Aperte 4 Para Fazer uma Transferencia.");
        System.out.println(" | ");
        System.out.println(" | -Aperte 5 Para Consultar Pagamentos.");
        System.out.println(" | ");
        System.out.println(" | -Aperte 6 Para Consultar Extrato.");
        System.out.println(" | ");
        System.out.println(" | -Aperte 0 Para Sair Do Menu.");
        System.out.println(" | ");        
        System.out.println(" |     ____________________________________");
        System.out.println(" | ");
        for (int i = 1; i > 0; i++) {

            System.out.print(" | Digite O Numero Desejado: ");
            menu = ler.nextInt();

            switch (menu)
            {
                
                case 1: {
                    iSaldo = i;
                    a = "";
                    extract[1] = a ;
                    exa = 0;
                    System.out.println(" |      ____________________________________");
                    System.out.println(" |                  SALDO ATUAL           ");
                    System.out.println(" | Saldo: " + saldo);
                    extrato[0] = saldo;
                    System.out.println(" |     ____________________________________");
                    System.out.println(" | ");
                    
                    break;
                }

                case 2: {
                    iDeposito = i;
                    b = "";
                    extract[2] =b ;
                    exb = 0;
                    System.out.println(" |     ____________________________________");
                    System.out.println(" |                    DEPÓSITO               ");
                    System.out.println(" | ");
                    System.out.print(" | Insira o Valor Do Seu Depósito: ");                    
                    deposito = ler.nextInt();    
                    saldo = deposito + saldo;
                    extrato[1]= deposito;
                    extrato[4]=saldo;
                    System.out.println(" | ");
                    System.out.println(" |                Saldo Atualizado          ");
                    System.out.println(" |      ____________________________________");
                    System.out.println(" | ");
                    break;
                }

                case 3: {
                    iSaque = i;
                    c= "";
                    extract[3]= c;
                    exc = 0;
                    System.out.println(" |      ____________________________________");
                    System.out.println(" |                    SAQUE                ");
                    System.out.println(" |");
                    System.out.print(" | Insira o Valor Do Seu Saque: ");
                    extrato[2]=saque = ler.nextInt();
                    if (saque > saldo){
                    System.out.println(" | ");
                    System.out.println(" | Saldo Indisponivel.");
                    System.out.println(" | ");
                    System.out.println(" |              Saque Não Aprovado       ");
                    System.out.println(" |      ____________________________________");
                    }
                    else {
                    saldo = saldo - saque;
                    extrato[5]=saldo;
                    System.out.println(" | ");
                    System.out.println(" |                Saque Aprovado         ");
                    System.out.println(" |      ____________________________________");
                    System.out.println(" | ");}
                    break;
                }
                case 4:{
                iTransferencia = i;
                d = "";
                extract[4]= d;
                exd = 0;
                System.out.println(" |         ____________________________________");
                System.out.println(" |                     TRANSFERENCIA           ");
                System.out.println(" | ");
                System.out.print(" | Valor Da Sua Transferencia: ");
                extrato[3]=transferencia = ler.nextInt();
                if (transferencia > saldo){
                    System.out.println(" | ");
                    System.out.println(" | Saldo Indisponivel.");
                    System.out.println(" | ");
                    System.out.println(" |         Transferência Não Aprovada    ");
                    System.out.println(" |     ____________________________________");
                    }   else {                              
                System.out.println(" | ");
                System.out.print(" | Conta De Transferência: ");
                conta = ler.nextInt();
                System.out.println(" | ");
                System.out.print(" | Agência: ");
                agencia = ler.nextInt();
                System.out.println(" | ");
                System.out.print(" | Banco: ");
                banco = ler.next(); 
                saldo = saldo - transferencia;
                extrato[6]=saldo;
                System.out.println(" | ");
                System.out.println(" |                  Transferência Aprovada       ");
                System.out.println(" |           ____________________________________");
                System.out.println(" | ");
                }             
                break;
                }
                case 5:    
                {
                    iPagamentos = i;
                    e = "";
                    extract[5] = e;
                    exe = 0;
                    System.out.println(" |           ____________________________________");
                    System.out.println(" |                         PAGAMENTOS            "); 
                    System.out.println(" | ");
                    System.out.print(" | Valor de Compras Feitas No Débito: ");
                    debito = ler.nextInt();
                    extrato[9]=debito;
                    saldo = saldo - debito;
                    extrato[10] = saldo;
                    System.out.print(" | Valor De Compras Feitas No Crédito: ");
                    credito = ler.nextInt();
                    extrato[11]= credito;
                    System.out.print(" | Parcelas Feita Por Mês Em Crédito: ");
                    creditox = ler.nextInt();
                    extrato[12]=creditox;
                    credito = (credito / creditox);
                    extrato[13]= credito;
                    saldo = saldo - credito;
                    extrato[14]= saldo;
                    System.out.println(" |           ____________________________________");                    
                    break;
                }
                case 6:{
                    
                    System.out.println(" |           ____________________________________");
                    System.out.println(" |                           EXTRATOS            ");    
                       
                       
                       
                       if (extract[1] == a){
                            
                            System.out.println(" | ");
                            System.out.println(" | SALDO INICIAL DE R$ "+extrato[20]);
                            System.out.println(" | ");
                        }
                        
                       
                        if (extract[2] == b){  
                           
                            System.out.println(" | DEPÓSITO DE R$ "+extrato[1]+" - SALDO RESTANTE DE R$ "+extrato[4]);
                            System.out.println(" | ");              
                        }
                       
                       if (extract[3] == c){
                            System.out.println(" | SAQUE DE R$ "+extrato[2]+ " - SALDO RESTANTE DE R$ "+extrato[5]);
                            System.out.println(" | ");
                        }
                      
                        if (extract[4] == d){
                            System.out.println(" | TRANSFERÊNCIA DE R$ "+extrato[3]+ " - SALDO RESTANTE DE R$ "+extrato[6]);
                            System.out.println(" | ");
                        }
                                                
                        if (extract[5] == e){

                            System.out.println(" | PAGAMENTOS EM DÉBITO DE R$ "+extrato[9]+" - SALDO RESTANTE DE R$ "+extrato[10]);
                            System.out.println(" | ");               
                            System.out.println(" | PAGAMENTOS EM CRÉDITO DE R$ "+extrato[11]+" FEITO EM "+extrato[12]+"x"+" DE R$ "+extrato[13]);
                            System.out.println(" |          SALDO RESTANTE DE R$"+extrato[14]);
                        }
                        
                        
                    System.out.println(" |          ____________________________________");
                    System.out.println(" | ");
                
                    break;
        }
        

                case 0: {
                    i = i - 999;
                    System.out.println(" | ");
                    System.out.println(" |                  MENU FECHADO             ");
                    System.out.println(" |      ____________________________________");
                    break;
                }

                default:
                    System.out.println(" | ");
                    System.out.println(" |           NUMERO DIGITADO É INVALIDO     ");
                    System.out.println(" |      ____________________________________");
                    System.out.println(" | ");
            }}
        }}
    }




