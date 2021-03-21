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

* **R1.	Estrutura**: O website deverá ter pelo menos 5 páginas Web. ֎
* **R2. Técnicas usadas**: uma das páginas deverá decrever em detalhe as técnicas usadas para desenvolvimento da aplicação. Nesta deverá integrar:
    * desenho da árvore que representa a estrutura do website
    * apresentação dos layouts escolhidos (com imagens) e critérios de responsividade, com media queries.
    * Tabela de técnicas usadas, que lista todas as etiquetas HTML5 semânticas usadas, seletores e propriedades CSS, media queries, tipos de display usados, animações, efeitos, etc. Inclua os requisitos técnicos listados neste enunciado. Apresenta-se em baixo um exemplo de parte da tabela:

| Carateristicas | Elementos/técnicas | Exemplos |
| --- | --- | --- |
| Layouts | Usou-se o CSS grid e CSS flexbox para construção de layouts | ... |
| Responsividade | Foram usadas media queries que adaptam o layout para telemovel e PC consoante o tamanho da janela do browser. | ... |
| Seletores | Foram usados seletores de ... | ... |
| Etiquetas | HTML5	main, header, article, footer, figure... |
| Animações | Foram feitas animações usando keyframes que permite … | ... |

* **R3.	Online no Heroku**: O website deverá estar a correr no Heroku. ֎
* **R1.	Originalidade**: o website deve ser inteiramente desenvolvido pelos membros do grupo. Devem seguir um estilo e gosto pessoal. Deverá ter elementos originais e diferentes dos fornecidos e feitos nos laboratórios. Não deverá usar bootstrap, nem trechos de código extraídos da Internet ֎
* **R2.	Proficiência**: deverá compreender profundamente o que cada linha do código faz. Na apresentação e discussão do trabalho, deverá ser capaz de explicar, implementar novamente ou alterar qualquer aspeto do site ֎
* **R5.	HTML5**: Todos os ficheiros HTML deverão estar no formato HTML5 e o head adequadamente formatado e detalhado. Utilize pelo menos 7 etiquetas HTML5 (article, main, nav, aside, header, footer, figure). Evitar a utilização das etiquetas div e span. 
* **R6.	Layout CSS Grid**: O website deverá ter os seus layouts construídos com CSS grid e Flexbox.
* **R7.	Layout Fluido e responsivo**: O layout deverá ser flúido e responsivo, usando media queries, com layouts consoante a dimensão do ecrã (PC ou smartphone), considerando também a possiblidade de o telemóvel estar em orientação portrait ou landscape. Todos os conteúdos deverão adaptar-se de forma responsiva. Nunca deverão aparecer scrollbars horizontais ou verticais. 
* **R9.	Elemento head**: tenha o head formatado com detalhe em cada ficheiro, com pelo menos 4 etiquetas meta a descrever detalhes.
* **R10.	Barra de navegação**: especifique um titulo (elemento <title> do head) e crie um ícone para a barra de navegação.
* **R11.	CSS**: Deverá usar um único ficheiro CSS externo para estilizar as páginas do website. Deverá utilizar todos os tipos de selectores e deverá fazer composição de seletores. Deverá usar o maior número de propriedades. 
* **R12.	Body**: formatado pelo CSS externo. 
R13.	Fonte: Deverá usar uma fonte web Google ( https://fonts.google.com/ ) [1] que disponibiliza uma grande variedade de fontes raras e especiais que funcionam garantidamente [2] em todos os browsers. 
R14.	Cores: Deverá ter uma coerência de estilo em todas as páginas, usando uma palete de cores de forma coerente em todas as páginas.

O meu website
R15.	Storyboard: colocar desenho(s) (papel e lápis) a explicar como concebeu o website, antes de o fazer em HTML. Como pensou o layout telemóvel e em PC. Como seria o layout com imagens.
R16.	Mapa do website: incluir desenho da árvore das páginas do seu website, expansão completa do vosso menu e todos submenus (com tudo aberto).
R17.	Tabela de inventário: incluir uma tabela que lista quantas páginas tem o seu website, quantas imagens, quantos links externos, quantos vídeos, animações, etc.



Portfólio
R19.	5 cadeiras: deverá incluir trabalhos de no mínimo 5 cadeiras do curso, incluindo Desenvolvimento Web.
R20.	30 trabalhos mínimo: Pelo menos 30 imagens, animações ou vídeos de trabalhos de outras cadeiras.
R21.	Imagens documentadas: Todas as imagens deverão estar dentro duma etiqueta figure e ter uma legenda (figcaption) com: título (caso não tenha, indicar “sem título”), técnica, dimensões, data, e um texto dentro de uma etiqueta HTML “details”, de 10 a 30 palavras (sobre a obra, o que o motivou, curiosidades, local onde foi feito, referencias, citações que o inspiraram).
R22.	Tamanho de Imagens cada imagem não deverá exceder 200kB. Deverão ser processadas para ficar pequenas, usando por exemplo o Paint.Net e redimensionando-as para tamanhos mais pequenos.
R23.	Tamanho responsivo: O tamanho das imagens deverá ser devidamente adaptado ao tamanho do navegador para que se veja cada imagem na totalidade, nunca ficando cortada (adaptando-se ao tamanho da janela do browser). 
R24.	Display flex para imagens: deverá aplicar display flex para que as imagens fiquem dispostas de forma responsiva.
R25.	Animações: Deverá ter pelo menos três animações feitas com keyframes.
R26.	Efeitos em imagens: Deverá estilizar imagens através de efeitos CSS.
R27.	Videos e áudios: Deverá incluir vídeos e áudios através de iframes. Poderá ter um vídeo seu a falar sumariamente sobre si, o que gosta, faz e o motiva.

Sobre mim
R28.	CV em PDF: Deverá ter um link para um PDF do seu CV que possa ser descarregada.
R29.	Conta Linked-In: Deverá ter uma conta Linked-In, onde inclua uma referência ao seu website, e utilize conteúdos da sua pagina de curriculum. Adicione os seus colegas, amigos e professores assim como grupos de interesse na sua área.
R30.	Posts: criar post no seu Facebook, Instagram e LinkedIn sobre a sua página web.
R31.	Links: deverá ter links para as suas contas de Facebook ,LinkeIn, Instagram e Youtube.
R32.	Contacto: Incluir o seu contacto de email.

 

CRONOGRAMA DE TRABALHO

•	3 de junho: prazo para submissão do projeto. A submissão será feita da seguinte forma:
o	O sítio Internet deverá ser a sua homepage da UBI
(a www.webx.ubi.pt\~a123456\index.html)
o	Todos os laboratórios deverão estar integrados no site.
o	Submeta no Moodle um ficheiro zip com o website completo.
o	Submeta no Moodle o link para a sua página pessoal.
o	Responda no Moodle ao questionário onde identifica os requisitos que implementou.
•	5 de junho (9h-17h): Apresentação, discussão e avaliação dos projetos. O website será apresentado, discutido e avaliado através do Teams. Os projetos serão apresentados por ordem alfabética dos alunos, independentemente da turma a que pertençam.
