# Linguagem de programação Julia

Este repositório contem projetos da linguagem de programação Julia.


### Como instalar no Windows

1. Fazer download do [arquivo executável](https://julialang.org/downloads/) exe.
	
2. Instalar a Julia ap partir do instalador baixado. 
	>Observação: Selecionar o item para adicionar a Julia ao Path do Windows.
	
3. Com esses passos o Julia já estará instalado e poderá ser utilizada a partir do seu prompt. 
4. No prompt digite os seguintes comandos para atualizar os pacotes da Julia:

		using Pkg
	
		Pkg.update()
	
5. Para facilitar o desenvolvimento do código é importante habilitar um editor de texto para sua execução. Os editores mais utilizados são o Juno ou o VsCode.

	> Para instalar e configurar o Juno para utilizar a Julia: [Configuracion de Atom+Juno para Julia](https://www.youtube.com/watch?v=BlL3a6HN21I)
	
	> Para instalar o VsCode: [Como baixar e instalar o Visual Studio Code (VS Code) - 2021](https://www.youtube.com/watch?v=_R6YslWRUFk)
	
	> Configurar o VsCode para utilizar a Julia: [Tutoriais de Julia em Português - VSCode no Julia](https://www.youtube.com/watch?v=zZInEh0pAKg)
	
6.  A linguagem Julia pode ser instalada em todos os sistemas operacionais seguindo o tutorial do seguinte video: [Julia - Instalação e Configuração](https://www.youtube.com/watch?v=hP6HP5ELGLM)

	
7. Para verificar se a linguagem foi instalada com sucesso você pode digitar o comando abaixo no terminal do Julia ou no seu editor de código.

		print("Hello World!!")

	
8.  Se tudo estiver ocorrido bem e o código acima executar, então o ambiente está pronto para desenvolvimento Julia.

### Projetos executados
Os códigos executados foram extraidos do repositório [Julia.jl](https://github.com/svaksha/Julia.jl/blob/master/Graphics.md#3d-graphics-imaging)

### Luxor
Para instalar o Pacote Luxor é necessário digitar o comando abaixo no terminal do Julia.

	] add Luxor

Antes de executar qualquer código em Julia que utilize o Luxor deve-se adicionar a linha abaixo no código.

	using Luxor
