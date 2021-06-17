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





