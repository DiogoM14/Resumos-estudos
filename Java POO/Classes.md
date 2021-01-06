## Classes
___
Define os `atributos` e `métodos` comuns que serão `compartilhados` por algum [[Objetos|objeto]].

Uma `Classe`, nada mais é do que um `molde` de um [[Objetos|Objeto]]. Esta, tem de responder obrigatóriamente a `3 perguntas`:

`Coisas que eu tenho` ([[Definição básica de Objetos|Atributos]])  -> Modelo, Cor, Bico, Carga, Tapada.
`Coisas que eu faço` ([[Definição básica de Objetos|Métodos]]) -> Escrever, Rabiscar, Pintar, Tapar, Destapar.
`Como estou agora` ([[Definição básica de Objetos|Estado]]) -> Azul, Bico fino, 50% de Carga, com tampa e escreve.

___
#### Exemplo Prático da criação de uma classe que [[Objetos|irá ser instânciada]]
```
Classe Caneta
	----Atributos----
	modelo: String	
	cor: String
	bico: String
	carga: Integer
	tapada: Boolean
	----------------
	
	----Métodos----
	Metodo escrever()
		Se(tapada) entao
			Escreva("Erro")
		senao
			Escreva("Rabisco")
		FimSe
	FimMetodo
	Metodo tapar()
		tapada = false
	FimMetodo
	---------------
FimClasse
```
==O Estado vai ser influênciado pelo estado dos atributos==

> Resultado final:
> ![[caneta-classe.png]]
