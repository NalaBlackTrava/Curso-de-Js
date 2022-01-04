= ->recebe

COMENTÁRIOS
	
	/* css */
	<!-- html -->
	// js

TIPOS

	Conversões
		> Number(n) or Number.parseInt(n) or Number.parseFloat(n)
		> String(n) or n.toString()

	Formatando Strngs
		var s = 'gostosa'
		`Ouvi dizer que a Nalinha tá ${s}` or 'Ouvi dizer que a Nalinha tá ' + s

	Formatando Números
		var n1 = 1543.5
		n1.toFixed(2) 		//isso aumenta o n de casas decimais
		'1545.50'

		 > n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'}) //isso pesquisa sozinho na internet a forma de representação do sistema monetário brasileiro
		 'R$ 1.545,50'     //currency == dinheiro


OPERADORES

	Aritiméticos
		5 + 2  = 7
		5 - 2  = 3
		5 * 2  = 10
		5 / 2  = 2.5
		5 % 2  = 1   			 //resto da fração ou 'Divisão inteira'
		5 ** 2 = 25 
		
		var n = 3
		n = n + 4  				//mesma coisa q n+4		prq n tá recebendo ele mesmo + 4, logo, n = n + 4 == n+=4
		x ++ = x + 1			//++ = +1  assim como -- = -1 (pré incremento {++x} e pós incremento {x++} // pré decremento {--x} e pós decremento {x--}	)


	Relacionais
		>
		<
		>=
		<=
		==
		!=

		// = recebe / == igual / === identico
	
	Lógicos
		! negação	 (n)	true / false
		&& conjunção (e)	 
		|| disjunção (ou)


DOM
	        var p1 = window.document.getElementsByTagName('p')[1]

		