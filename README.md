# Java-operador-logico
feito um programa em java para ver se pode ou não dá empréstimo 



package pacotelogico;

import java.math.*;

public class Operadores_logicos {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		boolean ult3EmprestimosPrazo, possuiRendaComprovada, ClienteDezEstrelas;
		
		ult3EmprestimosPrazo = false;
		possuiRendaComprovada = false;
		ClienteDezEstrelas =true;
		
		boolean concederEmprestimo = ult3EmprestimosPrazo && possuiRendaComprovada || ClienteDezEstrelas;
		
		System.out.printf("Emprestimno concedido? \n%b", concederEmprestimo);
		
		

	}

}


São verdadeira

![image](https://user-images.githubusercontent.com/72118415/122480700-b3e9e080-cfa3-11eb-9fcb-5401f5680ab6.png)


![image](https://user-images.githubusercontent.com/72118415/122480735-c49a5680-cfa3-11eb-9939-de33017a874d.png)

![image](https://user-images.githubusercontent.com/72118415/122481470-26a78b80-cfa5-11eb-8045-1ca636bb6c9d.png)



Quando é falso 

![image](https://user-images.githubusercontent.com/72118415/122481262-c9133f00-cfa4-11eb-9d8f-16247f65d071.png)

