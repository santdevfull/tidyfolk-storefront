# Tidyfolk — demonstração de dropshipping

## Estado real

Vitrine em inglês com três produtos ilustrativos, filtro, detalhes, carrinho, simulação de pedidos, painel em português, calculadora de contribuição, calendário de conteúdo e checklist. Não há cobrança, compra, envio de e-mail, integração com fornecedores, coleta de dados pessoais ou IA em execução contínua. O nome é provisório e não passou por pesquisa de marca. As imagens são ilustrações originais em SVG/CSS, não fotografias de mercadorias.

Todos os dados da demonstração ficam em localStorage no navegador/dispositivo atual. O painel não é autenticado e não deve receber dados reais de clientes. Limpar os dados do navegador apaga as simulações. Exportação JSON disponível. Não existe sincronização entre dispositivos.

## Como testar

1. Abra dist/index.html, ou a URL publicada, em navegador moderno.
2. Use os filtros Organize e Workspace; abra um produto.
3. Adicione itens à bag; aumente e diminua quantidades.
4. Simule um pedido. Nenhum pagamento será solicitado.
5. Abra Painel de operação: consulte o pedido e exporte JSON.
6. Edite os custos na calculadora e baixe o calendário CSV.
7. Recarregue a página para verificar a persistência local.

## Pesquisa a executar antes de escolher produtos reais

A organização de mesa é uma hipótese visual, não um nicho validado. Para cada candidato, registrar URL e data da fonte, concorrentes, preço de venda, custo unitário, frete por destino, taxas, devoluções, estoque, prazo de processamento, transportadora, políticas e resultado do teste de amostra. Comparar no mínimo três ofertas de fornecedores. Anúncios ativos não comprovam demanda rentável.

Fontes iniciais:
- TikTok Creative Center: https://ads.tiktok.com/business/creativecenter/inspiration/topads/mobile/en
- Meta Ads Library: https://www.facebook.com/ads/library/
- CJ catálogo nos EUA: https://us.cjdropshipping.com/
- Zendrop: https://www.zendrop.com/Pricing/

Não foram consultadas ofertas individuais nesta implementação. Os preços de US$ 24, US$ 29 e US$ 14 são apenas exemplos de interface.

## Modelo sem gastos adicionais nesta entrega

O site é HTML/CSS/JavaScript estático, sem pacotes pagos, fontes externas, rastreadores ou API de IA. Não foram contratados serviços pagos. Publicação depende da disponibilidade e condições de Sites na conta; isso não constitui promessa de hospedagem gratuita permanente. Um domínio próprio não é necessário para demonstrar.

Para vendas reais, será necessário definir identidade comercial, gateway elegível e conta bancária, políticas, contato, fornecedor e capital para pagar produto/frete antes da liberação do recebimento quando aplicável. Taxas por venda, impostos, devoluções e custos dos produtos continuam existindo mesmo sem mensalidade de software.

## Implantação futura

1. Validar nicho/produto e amostra.
2. Validar marca e dados comerciais.
3. Substituir catálogo ilustrativo por oferta real e materiais autorizados.
4. Escolher checkout hospedado elegível e comparar taxas por transação.
5. Implementar backend autenticado e banco para pedidos reais; nunca usar localStorage como registro comercial.
6. Confirmar pagamentos por webhook assinado no servidor, validar preço e moeda no servidor e prevenir duplicação de pedidos.
7. Integrar fornecedor com limites de gasto e tratamento de falhas.
8. Configurar rastreamento, devoluções, atendimento e backups.
9. Testar pedido completo antes de ativar compra pública.

## Automação disponível agora

Recalcular carrinho, registrar simulação, atualizar painel, calcular contribuição e exportar arquivos são rotinas locais determinísticas. Não são agentes de IA e só executam quando a página é usada. O calendário contém roteiros prontos, não posts publicados. Uma operação contínua exige hospedagem de execução, credenciais, conectores, monitoramento e orçamento compatível.

## Métrica

Contribuição por pedido = venda − produto − frete − taxas − reserva de devoluções − publicidade. A calculadora não representa lucro líquido: não inclui despesas fixas nem apuração tributária.
