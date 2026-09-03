# Andy

Andy é uma plataforma de inteligência comercial para assessores e consultores financeiros, que transforma a carteira de clientes em oportunidades acionáveis.

A partir da importação de uma planilha com os dados da carteira, a solução analisa os clientes, identifica sinais e potenciais oportunidades de negócio, prioriza quem merece atenção, estima o potencial financeiro deixado na mesa e organiza tudo em uma jornada simples de acompanhamento — da oportunidade identificada à conversa, ganho ou perda.

A proposta é desafogar o profissional que possui uma carteira grande demais para analisar manualmente, reduzindo o trabalho operacional e ajudando-o a saber quem abordar, por quê e qual oportunidade pode estar em jogo.

## Sobre este protótipo

Este é um **MVP (protótipo funcional)** construído como página única em **HTML, CSS e JavaScript**, sem back-end — toda a lógica roda no navegador. A leitura de planilhas usa a biblioteca [SheetJS](https://sheetjs.com/) via CDN. O objetivo é demonstrar a proposta de funcionamento do produto, não uma versão de produção.

Principal arquivo: [`andy-app.html`](andy-app.html).

## Como usar

1. Baixe (ou clone) este repositório.
2. Abra o arquivo `andy-app.html` diretamente no navegador (duplo clique ou arraste para uma aba do Chrome/Edge/Safari).
3. Na tela de login, os campos são apenas ilustrativos — preencha algo qualquer e clique em **Entrar**.
4. Importe os dados da carteira:
   - Clique em **Usar dados de demonstração** para carregar automaticamente a planilha de exemplo (`Andy_Carteira_Demo_200_Clientes.xlsx`, incluída neste repositório), ou
   - Clique em **Selecionar arquivo** e importe sua própria planilha `.csv` ou `.xlsx` (campos esperados: cliente, AUM, produtos, perfil, última interação e sinais comportamentais).
5. Explore o app: veja o plano de ação sugerido, a lista priorizada de oportunidades, o potencial financeiro estimado e a jornada de acompanhamento de cada cliente (da oportunidade identificada até ganho/perda).

Não é necessária instalação, servidor ou conexão com serviços externos além do CDN do SheetJS.
