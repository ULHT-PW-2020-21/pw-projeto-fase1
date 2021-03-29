**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**
 
# Programação Web - Projeto Fase 1 (P1): Website Responsivo 

## ENQUADRAMENTO
Nesta UC desenvolverá um projeto de uma aplicação Web sobre um tópico à vossa escolha. Este estará dividido em três fases de desenvolvimento, P1, P2 e P3:
* **P1: Website**: website que permite a navegação entre um conjunto de páginas Web com conteúdos digitais estáticos (não se atualizando dinâmicamente) constituídos por texto, imagens, video e audio. O seu design deverá ser responsivo ao tamanho do ecrã. Deverá ser desenvolvido usado exclusivamente HTML e CSS.
* **P2: Aplicação Web**: aplicação Web desenvolvida do lado do servidor com Django que, tendo como base o website estático desenvolvido em P1, integra elementos iterativos e funcionalidades. Acedida através de um browser, a aplicação estará ligada a uma base de dados integrada que permite uma experiencia interativa especifica ao indivídio que a usa. Deverá permitir referenciar, guardar e aceder a dados através de interfaces customizados. A renderização será feita no backend, recorrendo a templates para layout. Deverá ser desenvolvida em Django, usando Python, que entre outras funcionalidades manipulará uma base de dados interna. 
* **P3:Aplicação Web full-stack**: aplicação Web desenvolvida em P2 estendida com funcionalidades do lado do cliente para renderização de algumas páginas usando JavaScript. A aplicação ficará com uma arquitetura híbrida, com partes em frontend e outras backend. Será feita integração com Web Services.

## OBJECTIVOS
* O projeto P1 consiste na criação de um website estático sobre um tópico à vossa escolha.
* Deverá demonstrar os conhecimentos adquiridos sobre HTML e CSS.  
* Os conteúdos e o CSS deverão ser totalmente desenvolvidos pelo grupo, não podendo usar Bootstrap nem JavaScript nesta fase.


## PRÉ-REQUISITOS
* O projeto deve ser realizado em grupos de 2. Excepcionalmente, mediante aprovação do docente, poderá ser realizado individualmente.
* 🆕 Registe no [formulário](https://docs.google.com/forms/d/1_hYd38F1FvIjiKH10Lz0TQBYs3qkST1no7nGfbf92XI/edit?usp=sharing) o nome e numero dos membros do grupo, assim como link do repositório GitHub do projeto.


## REQUISITOS PARA REALIZAÇÃO DO PROJETO
O website desenvolvido deverá satisfazer os requisitos (R) que se seguem:

* **R1.	Originalidade**: o website deve ser inteiramente desenvolvido pelos membros do grupo. Devem seguir um estilo e gosto pessoal. Deverá ter elementos originais e diferentes dos fornecidos e feitos nos laboratórios. Não deverá usar bootstrap, nem trechos de código extraídos da Internet.
* **R2.	Proficiência**: deverá compreender profundamente o que cada linha do código faz. Na apresentação e discussão do trabalho, deverá ser capaz de explicar, implementar novamente ou alterar qualquer aspeto do site.
* **R3.	Estrutura**: O website deverá ter pelo menos 5 páginas Web. As imagens deverão estar numa pasta images.
* **R4.	No GitHub e online no Heroku**: O website deverá estar num repositório GitHub, e sincronizado e a correr no Heroku.
* **R5.	HTML5**: Todos os ficheiros HTML deverão estar no formato HTML5 e o head adequadamente formatado e detalhado. Utilize pelo menos 7 etiquetas HTML5 (article, main, nav, aside, header, footer, figure). Evitar a utilização das etiquetas div e span.
* **R5.	Layout CSS Grid**: O website deverá ter os seus layouts construídos com CSS grid e Flexbox. 🆕 Explore os [layouts básicos](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Common_web_layouts) e alguns [princípios](https://www.creativebloq.com/netmag/create-balanced-page-layouts-7-pro-tips-121310009) para criar um layout balanceado.
* **R6.	Layout Fluido e responsivo**: O layout deverá ser flúido e responsivo, usando media queries, com layouts consoante a dimensão do ecrã (PC ou smartphone), considerando também a possiblidade de o telemóvel estar em orientação portrait ou landscape. Todos os conteúdos deverão adaptar-se de forma responsiva. Evite scrollbars horizontais ou verticais.
* **R7. Elemento head**: tenha o head formatado com detalhe em cada ficheiro, com pelo menos 4 etiquetas meta a descrever detalhes.
* **R8. Barra de navegação**: especifique um titulo (elemento <title> do head) e crie um ícone para a barra de navegação.

* **R9. Menu**: Crie um menu de navegação configurando com pseudo-classes os links.
* **R10. CSS**: Deverá usar um único ficheiro CSS externo para estilizar as páginas do website. Deverá utilizar todos os tipos de selectores e deverá fazer composição de seletores. Deverá usar o maior número de propriedades. Os conteúdos das páginas deverão estar estilizados usando CSS, demonstrando todos os conhecimentos adquiridos até agora sobre HTML e CSS. 
* **R11.	Fonte**: Deverá usar uma fonte web Google ( https://fonts.google.com/ ) [1] que disponibiliza uma grande variedade de fontes que funcionam garantidamente [2] em todos os browsers. 
* **R12.	Cores**: Deverá ter uma coerência de estilo em todas as páginas, usando uma palete de cores de forma coerente em todas as páginas. 🆕 Explore por exemplo a ferramenta [Paletton](https://paletton.com/).
* **R13.	Imagens documentadas**: Todas as imagens deverão estar dentro duma etiqueta figure e ter uma legenda (figcaption) com um título e hiperlink para a fonte de onde foram retiradas. Nalgumas, inclua detalhes dentro de uma etiqueta HTML `<details>`.
* **R14. Estilização de imagens**: Insira algumas imagens, aplicando a técnica de sobreposição de imagens e texto umas por cima das outras, recorrendo a posições absolutas e relativas. Explore também com a propriedade sticky e fixed, em imagens a colocar no background.
* **R15.	Tamanho de Imagens** cada imagem não deverá exceder 100kB. Deverão ser processadas para ficar pequenas, usando por exemplo o Paint.Net, existindo versões diferentes para desktop e telemóvel.
* **R16.	Tamanho responsivo**: O tamanho das imagens deverá ser devidamente adaptado ao tamanho do navegador para que se veja cada imagem na totalidade, nunca ficando cortada. 
* **R17.	Display flex para imagens**: deverá ter um contentor flex com mais de 5 items com imagens nas quais aplicaa propriedade display:flex para que as imagens fiquem dispostas de forma responsiva.
* **R18.	Animações**: Deverá ter pelo menos duas animações feitas com keyframes.
* **R19. Wordcloud**: Crie uma wordcloud com hiperlinks em algumas das palavras, usando SVG.
* **R20. Icons**: Utilize ícones no website (por exemplo nos menus, títulos, no texto, etc).
* **R21.	Efeitos em imagens**: Estilize imagens através de efeitos CSS.
* **R22.	Videos e áudios**: Deverá incluir vídeos do Youtube através de iframes. Inclua na página sobre este website um vídeo de 2 minutos a mostrar o website (veja detalhes em R30).
* **R23. Formulário**: Crie um formulário explorando os vários tipos de input existentes. Quando submetido deverá ser enviado para um endereço de email. Estilize o formulario usando o CSS.
* **R24.	Links**: Inclua links para páginas externas ao seu website, relacionadas com o tópico.
* **R25. Técnicas usadas**: uma das páginas deverá ser sobre o website em si, decrevendo em detalhe as técnicas usadas para desenvolvimento da aplicação. 
* **R26.	Mapa do website**: incluir na página sobre o website o desenho da árvore das páginas do seu website, expansão completa do menu e todos submenus (com tudo aberto).
* **R27.	Layouts**: colocar na página sobre o website uma secção sobre os layouts. Deverá incluir ilustrações e explicar os layouts que definiu para PC e telemóvel (podem ser desenhos de esboços do layout apenas com caixas). Estes deverão ser feitos antes da implementação.
* **R28.	Tabela de inventário**: incluir na página sobre o website uma tabela que lista quantas páginas tem o website, quantas imagens, quantos links externos, quantos vídeos e animações.
* **R29. Técnicas usadas**: Na página sobre o website deverá integrar uma tabela com as técnicas usadas. Deverá detalhar todas as etiquetas HTML5 semânticas usadas, seletores e propriedades CSS, media queries, tipos de display usados, animações, efeitos, etc. Inclua os requisitos técnicos listados neste enunciado. Apresenta-se em baixo um exemplo de parte da tabela:

| Carateristicas | Elementos/técnicas | Exemplos |
| --- | --- | --- |
| Layouts | Usou-se o CSS grid e CSS flexbox para construção de layouts | ... |
| Responsividade | Foram usadas media queries que adaptam o layout para telemovel e PC consoante o tamanho da janela do browser. | ... |
| Seletores | Foram usados seletores de ... | ... |
| Etiquetas | HTML5	main, header, article, footer, figure... |
| Animações | Foram feitas animações usando keyframes que permite … | ... |

* **R30.	Video de apresentação**: Inclua na página sobre este website um vídeo de 2 minutos 🆕 sem som a mostrar o website, seu layout, mostrar a responsividade deste, técnicas empregues, evidenciando aspectos diferenciadores que empregou. Mostre também o HTML, a sua estrutura, evidenciando como está simples e claro, e mostre também o CSS, com o uso de diversos tipos de seletores, media queries, etc. Para fazer o vídeo pode usar por exemplo a aplicação OBS. Carregue o video no Youtube, disponibilizando-o no website num iframe.

* **R31.	Anonimato**: Não deverá haver no projeto nem link referências aos nomes dos autores do projeto, visto haver uma componente de avaliação anónima que será feita pelos pares.
  
## SUBMISSÃO e AVALIAÇÃO

O prazo de entrega do projeto é 12 de abril.

A avaliação do projeto terá duas componentes:
* avaliação pelos docentes, baseada nos requisitos listados anteriormente (60%).
* avaliação por pares, feita por colegas, de acordo com um conjunto de critérios que serão explicitados (40%).
