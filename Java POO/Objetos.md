## Objetos
___
`Todos os Objetos são baseados em` [[Classes]] (`Molde`). Então, `para criar um objeto`, primeiramente, tenho de `definir uma Classe`.

Um `Objeto pode ser considerado` uma `caneta`, enquanto a [[Classes|classe]] é o modelo ou protótipo, `desenhado préviamente`.
Através dessa [[Classes|Classe]], iremos `gerar um o Objeto` (`Instanciar Objeto`).

Com isto podemos considerar, que `um objeto, nada mais é do que a instância de uma classe`. 

___
#### Exemplo prático de como instanciar Objeto c1 baseado na [[Classes|Classe Caneta]]

```
	Caneta c1 = new Canela();
	
	c1.cor = "Azul";
	c1.bico = "Fino";
	c1.tapada = false;
	c1.escrever();
	
	Caneta c2 = new Canela();
	
	c1.cor = "Vermelho";
	c1.bico = "Grosso";
	c1.tapada = true;
	c1.tapar();
```
> Resultado final:
> ![[caneta-objeto.png]]