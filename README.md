# Garagem 783 — estudo conceitual

Protótipo público de apresentação para iniciar uma conversa com a equipe do Garagem 783 Bar. Não é o site oficial nem foi aprovado pelo estabelecimento. Três direções visuais ficam no seletor superior.

## Discovery — 22/10/2026

### Fatos confirmados em fontes públicas
- Google Maps: Garagem 783 Bar, 4,9/5 e 37 avaliações; endereço Avenida Henrique Monat, 783, Federal, Caxambu/MG; horários qua/qui 17h–23h, sex/sáb 17h–00h e dom–ter fechado. A ficha não lista site. Consulta: [Google Maps](https://www.google.com/maps/search/Garagem+783+Bar+Caxambu+MG).
- Prefeitura de Caxambu registrou o estabelecimento no Festival Comida de Boteco 2024 e citou “toucinho de barriga ao molho com jiló” como prato participante naquela edição: [fonte oficial](https://caxambu.mg.gov.br/noticia/7647/festival-comida-de-boteco/).
- Perfil Instagram indicado como oficial: [@garagem783bar](https://www.instagram.com/garagem783bar/). O conteúdo e a bio não puderam ser inspecionados durante este trabalho.

### Hipóteses e recomendações
- Uma página pode concentrar localização, horários e o cardápio atual com atalhos aos canais já usados. Validar essa necessidade antes de propor escopo.
- Sabores locais podem orientar a narrativa, sem concluir que o prato de 2024 ainda é servido.

### Pendências para a conversa
- Confirmar identidade visual, produtos atuais, cardápio e preços, horários, serviços de pedido/reserva e relevância de eventos.
- Conferir bio e destinos do Instagram; perguntar qual jornada merece prioridade.
- O telefone listado no Maps diverge do publicado em fonte municipal de 2024; não foi testado e não é usado como botão.
- Email garagem783bar@gmail.com veio de imagem mencionada no brief; a imagem não estava disponível para confirmação visual.

## Design

Direção base: um letreiro circular “783” como sinal visual próprio da proposta, com carvão, osso e verde ácido; tipografia Oswald, DM Sans e DM Mono. As outras rotas mudam composição e uso: editorial quente para o registro gastronômico municipal; mapa utilitário em papel claro para localização e serviço. A pesquisa ui-ux-pro-max recomendou hierarquia de restaurante, foco móvel e contraste; o padrão de testemunhos foi descartado por não haver depoimentos verificados adequados para publicação.

## Revisão

- Seletor por teclado, botões com estado `aria-pressed`, links externos rotulados, foco visível, layout mobile-first, `prefers-reduced-motion`.
- Nenhum formulário transacional; pedidos e reservas não são funcionais.
- Menus e agendas atuais foram omitidos por falta de confirmação.

## Publicação

Publicado no GitHub Pages após revisão: consultar a URL do repositório e a URL pública nas informações de entrega da tarefa.
