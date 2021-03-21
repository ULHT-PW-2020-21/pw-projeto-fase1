**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**
 
# Programação Web - P1: Projeto fase 1: website responsivo 

## ENQUADRAMENTO
Nesta UC desenvolverá um projeto de uma aplicação Web sobre um tópico à sua escolha. Este estará dividido em três fases de desenvolvimento, P1, P2 e P3:
* **P1: Website**: website que permite a navegação entre um conjunto de páginas Web com conteúdos digitais estáticos (não se atualizando dinâmicamente) constituídos por texto, imagens, video e audio. O seu design deverá ser responsivo ao tamanho do ecrã. Deverá ser desenvolvido usado exclusivamente HTML e CSS.
* **P2: Aplicação Web**: aplicação Web desenvolvida do lado do servidor com Django que, tendo como base o website estático desenvolvido em P1, integra elementos iterativos e funcionalidades. Acedida através de um browser, a aplicação estará ligada a uma base de dados integrada que permite uma experiencia interativa especifica ao indivídio que a usa. Deverá permitir referenciar, guardar e aceder a dados através de interfaces customizados. A renderização será feita no backend, recorrendo a templates para layout. Deverá ser desenvolvida em Django, usando Python, que entre outras funcionalidades manipulará uma base de dados interna. 
* **P3:Aplicação Web full-stack**: aplicação Web desenvolvida em P2 estendida com funcionalidades do lado do cliente para renderização de algumas páginas usando JavaScript. A aplicação ficará com uma arquitetura híbrida, com partes em frontend e outras backend. Será feita integração com Web Services.

## OBJECTIVOS
* O projeto P1 consiste na criação de um website sobre um tópico à vossa escolha.
* Deverá demonstrar os conhecimentos adquiridos sobre HTML e CSS.  
* Os conteúdos e o CSS deverão ser totalmente desenvolvidos pelo grupo, não podendo usar Bootstrap nem JavaScript. 

## REQUISITOS
O website desenvolvido deverá satisfazer os requisitos (R) que se seguem:

* **R1.	Originalidade**: o website deve ser inteiramente desenvolvido pelos membros do grupo. Devem seguir um estilo e gosto pessoal. Deverá ter elementos originais e diferentes dos fornecidos e feitos nos laboratórios. Não deverá usar bootstrap, nem trechos de código extraídos da Internet ֎
* **R2.	Proficiência**: deverá compreender profundamente o que cada linha do código faz. Na apresentação e discussão do trabalho, deverá ser capaz de explicar, implementar novamente ou alterar qualquer aspeto do site ֎
* **R3.	Estrutura**: O website deverá ter pelo menos 5 páginas Web. ֎
* **R4.	Online no Heroku**: O website deverá estar a correr no Heroku. ֎* **R5.	HTML5**: Todos os ficheiros HTML deverão estar no formato HTML5 e o head adequadamente formatado e detalhado. Utilize pelo menos 7 etiquetas HTML5 (article, main, nav, aside, header, footer, figure). Evitar a utilização das etiquetas div e span. ֎
* **R5.	Layout CSS Grid**: O website deverá ter os seus layouts construídos com CSS grid e Flexbox. ֎
* **R6.	Layout Fluido e responsivo**: O layout deverá ser flúido e responsivo, usando media queries, com layouts consoante a dimensão do ecrã (PC ou smartphone), considerando também a possiblidade de o telemóvel estar em orientação portrait ou landscape. Todos os conteúdos deverão adaptar-se de forma responsiva. Nunca deverão aparecer scrollbars horizontais ou verticais. ֎
* **R7. Elemento head**: tenha o head formatado com detalhe em cada ficheiro, com pelo menos 4 etiquetas meta a descrever detalhes. ֎
* **R8. Barra de navegação**: especifique um titulo (elemento <title> do head) e crie um ícone para a barra de navegação.

* **R9. CSS**: Deverá usar um único ficheiro CSS externo para estilizar as páginas do website. Deverá utilizar todos os tipos de selectores e deverá fazer composição de seletores. Deverá usar o maior número de propriedades. ֎
* **R10.	Fonte**: Deverá usar uma fonte web Google ( https://fonts.google.com/ ) [1] que disponibiliza uma grande variedade de fontes que funcionam garantidamente [2] em todos os browsers. 
* **R11.	Cores**: Deverá ter uma coerência de estilo em todas as páginas, usando uma palete de cores de forma coerente em todas as páginas.

* **R12.	Imagens documentadas**: Todas as imagens deverão estar dentro duma etiqueta figure e ter uma legenda (figcaption) com um título e hiperlink para a fonte de onde foram retiradas. Nalgumas, inclua detalhes dentro de uma etiqueta HTML `<details>`.
* **R13.	Tamanho de Imagens** cada imagem não deverá exceder 100kB. Deverão ser processadas para ficar pequenas, usando por exemplo o Paint.Net, existindo versões diferentes para desktop e telemóvel.
* **R14.	Tamanho responsivo**: O tamanho das imagens deverá ser devidamente adaptado ao tamanho do navegador para que se veja cada imagem na totalidade, nunca ficando cortada. 
* **R15.	Display flex para imagens**: deverá ter um contentor flex com mais de 5 items com imagens nas quais aplicaa propriedade display:flex para que as imagens fiquem dispostas de forma responsiva.
* **R16.	Animações**: Deverá ter pelo menos duas animações feitas com keyframes.
* **R16.	SVG**: Inclua pelo menos uma imagem SVG com hiperlinks em algumas das suas partes.
* **R17.	Efeitos em imagens**: Estilize imagens através de efeitos CSS.
* **R18.	Videos e áudios**: Deverá incluir vídeos do Youtube através de iframes. Inclua na página sobre este website um vídeo de 2 minutos a mostrar o website e a falar sobre as tecnicas empregues. Mostre o HTML e CSS.
* **R19.	Links**: Inclua links para outras páginas.
* **R20. Técnicas usadas**: uma das páginas deverá ser sobre o website em si, decrevendo em detalhe as técnicas usadas para desenvolvimento da aplicação. 
* **R21.	Layouts**: colocar na página sobre o website uma secção sobre os layouts. Deverá incluir ilustrações e explicar os layouts que definiu para PC e telemóvel (podem ser desenhos de esboços do layout apenas com caixas). Estes deverão ser feitos antes da implementação.
* **R22.	Mapa do website**: incluir na página sobre o website o desenho da árvore das páginas do seu website, expansão completa do menu e todos submenus (com tudo aberto).
* **R23.	Tabela de inventário**: incluir na página sobre o website uma tabela que lista quantas páginas tem o website, quantas imagens, quantos links externos, quantos vídeos e animações.
* **R24. Tecnicas usadas**: Na página sobre o website deverá integrar uma tabela com as técnicas usadas. Deverá detalhar todas as etiquetas HTML5 semânticas usadas, seletores e propriedades CSS, media queries, tipos de display usados, animações, efeitos, etc. Inclua os requisitos técnicos listados neste enunciado. Apresenta-se em baixo um exemplo de parte da tabela:

| Carateristicas | Elementos/técnicas | Exemplos |
| --- | --- | --- |
| Layouts | Usou-se o CSS grid e CSS flexbox para construção de layouts | ... |
| Responsividade | Foram usadas media queries que adaptam o layout para telemovel e PC consoante o tamanho da janela do browser. | ... |
| Seletores | Foram usados seletores de ... | ... |
| Etiquetas | HTML5	main, header, article, footer, figure... |
| Animações | Foram feitas animações usando keyframes que permite … | ... |

* **R25.	Video de apresentação**: Inclua na página sobre este website um vídeo de 2 minutos a mostrar o website, seu leyout, mostrar a responsividade deste, a falar sobre as tecnicas empregues. Mostre também o HTML, a sua estrutura, e o ficheiro CSS, explicando alguns seletores e seus efeitos na renderização final. Para fazer o vídeo pode usar por exemplo a aplicação OBS.
