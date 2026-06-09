Projeto: BI de Integração (Distribuidora / Atacado)
Visão Geral do Desafio
O projeto nasceu da necessidade de alinhar visões distintas de negócio entre uma grande rede de atacado e sua distribuidora parceira. Enquanto o atacado exige uma visão consolidada de estoque e pedidos, a distribuidora opera com uma estrutura segmentada em múltiplos status. A complexidade aumentava devido à ausência de vínculo sistêmico entre o pedido de compra (Indústria/Distribuidora) e o pedido de venda (Distribuidora/Atacado), além da falta de rastreio por lotes.


Nível de Atendimento (Card 1): Criado para expor a realidade da entrega da indústria para a distribuidora. Esse indicador permite que o atacado gerencie negociações de nível de serviço e devoluções diretamente com a indústria, garantindo transparência.

Análise de Fluxo (Card 2): Implementei indicadores "termômetro" através de gráficos de linha, cruzando dados de recebimento e faturamento. Isso possibilita identificar a velocidade de giro, datas de entrega e o comportamento da mercadoria mês a mês, já que indicação precisa não seria possível dado a falta de lastro dos processo da distribuidora, onde sistemicamente não recebem mercadoria por lote (o que via banco linkaria compra com venda), ou alguma marcação no pedido de venda).

Usabilidade e Padronização: Adotei a hierarquia de navegação Drill-down, permitindo que o gestor visualize o macro na tela inicial, enquanto analistas e assistentes podem navegar até o nível micro (processual). Além disso, unifiquei os códigos de produto da distribuidora com os do cliente, eliminando ruídos de comunicação.

Conceito de Estoque & Carteira

Gestão de Estoque: Alterei os diversos status de estoque da distribuidora para, estoque operacional, que inclui todos os status menos o de avaria (necessário para a visão do atacado do real valor dentro do cd) e estoque sem pedido (onde eles podem aproveitar para cobrir a ruptura imediata sem precisar negociar com a indústria)
Carteira de Pedidos: Consolidei os diversos status em apenas 3: pedidos sem estoque para atender, pedidos na logística, pedidos faturados últimas 3 datas(importante pois foi faturado, saiu do sistema da distribuidora, mas não entrou ainda no atacado, devido a necessidade de agendamento da nota 2 dias antes da entrega)

Além disso adicionei diversas ferramentas de conforto na navegação como o usuário clicar no gráfico no dia específico e ter pode acessar as saídas e entradas selecionadas.

