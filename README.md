# LG2
códigos de pilha e fila

//como pratos empilhados, no sistema pilha, o primeiro a entrar, é o último a sair.

package ex.pilha;

import java.util.LinkedList;
import java.util.List;

public class Pilha {

	private List<String> nomes = new LinkedList<String>();

	public void push(String nome) (
		nomes.add(nome);
	)

	public String pop() {
		return nomes.remove(nomes.size()-1);
	}

	public String toString() {
		return nomes.toString();
	}
}

//já com o sistema fila, o primeiro a entrar é o primeiro a sair.

package ex.fila;

import java.util.LinkedList;
import java.util.List;


public class Fila{

	private List<String> alunos = new LinkedList<String>();

	public void push(String aluno) (
		aluno.add(aluno);
	)

	public String pop() {
		return alunos.remove(0);
	}

	public boolean vaza() {
		return alunos.isEmpty();
	}
	public String toString() {
		return alunos.toString();
	}
}


