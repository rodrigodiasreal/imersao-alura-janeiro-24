Para criar uma pasta diretamente do VS Code através do terminal. Basta escolher onde gostaria de criar a pasta através do comando "cd", depois, utilizar o comando "mkdir" e criar o nome da pasta(Sem espaço, para separar as palavras, utilizar hífen).

Após criar os arquivos html (index.html), css(styles.css) e Javascript (script.js), é necessário criar as "conexões" entre os arquivos.

Dica 1 - Para inserir dentro do Head do html a "conexão" do css, basta escrever a palavra 'link' e apertar a tecla tab.

A tag "nav" é usada para fazer menus.

Semântica é a tag que diz exatamente a função dela.

Para imagens que não possui conteúdo e que só é importante para a questão estética, utilizar o css com background-image. É mais interessante dessa forma para a questão de acessibilidade. Assim, no html, deixar o "alt" vazio.

A propriedade "maxlenght" serve para limitar a quantidade máxima de caracteres.

A propriedade vw e vh é utilizado para dar responsividade para o site. No caso, vw, significa "Viewport width" e vh significa "Viewport Height".

A propriedade "rem", diferente do "px", não é de tamanho estático e sempre relativo. Aproximadamente, um rem fica em torno de 16px.

A propriedade "text-overflow" com o valor de "ellipsis" faz com que uma escrita que ultrapasse o tamanho do local que está não quebre e sim utiliza os "...". Essa propriedade apenas funciona caso também tenha a propriedade overflow com o valor de "hidden".

A propriedade "white-space" dentro do input faz com que tudo que seja escrito fique apenas em uma linha.

Começando a usar Javascript, criar uma pasta de API e um arquivo ".json" dentro dela.

Para fazer funcionar, é necessário usar o comando "json-server --watch api-NomeDaPasta/arquivo.json --port 3000"
