
# Projeto Integrador - Ruivo Solutions

Professores: Marco André Mendes e Alann Perini.

Projeto feito por Rafael Alvaro Almeida

# Situação Problema

Rafael possui um negócio de manutenção de celulares,  desktops e notebooks. Ele deseja que seja desenvolvido para o seu negócio, um sistema de ORDEM DE SERVIÇO afim de uniformizar, otimizar e administrar sua empresa.

Rafael, especialista em reparos de aparelhos eletrônicos, estabelece contato com os clientes através de mensagens eletrônicas ou encontros pessoais, a fim de oferecer orçamentos sem compromisso. Embora os potenciais clientes descrevam o problema que estão enfrentando, Rafael sempre realiza uma inspeção minuciosa no aparelho eletrônico para confirmar a origem e a gravidade do defeito.

Uma vez identificado o problema, Rafael pesquisa os componentes eletrônicos necessários para o reparo, verificando os preços e prazos de entrega. Em seguida, ele entra em contato com o cliente, informando o valor do conserto e o prazo estimado para solucionar o problema do aparelho. 

Para oferecer opções aos clientes, Rafael realiza pesquisas no mercado local, nacional e internacional, apresentando pelo menos dois ou três orçamentos diferentes. Caso o cliente aceite o orçamento proposto, Rafael encomenda as peças e realiza o reparo necessário. 

Ao concluir o trabalho, ele notifica o cliente de que o aparelho está pronto e disponível para retirada. Rafael oferece uma garantia de três meses para os reparos realizados nos aparelhos eletrônicos, exceto para serviços de limpeza. Ele registra as garantias dos serviços em notas fiscais de compra dos componentes utilizados, uma vez que as peças adquiridas possuem garantia de três meses oferecida pelo fabricante ou distribuidora. 

No caso de algum cliente reclamar que o aparelho eletrônico não está funcionando corretamente após o reparo, Rafael analisa o problema e busca encontrar uma solução adequada. 

Se o cliente não aceitar o orçamento proposto, Rafael devolve o aparelho nas mesmas condições em que foi recebido, caso seja possível, e o cliente pode ir buscá-lo.

# Descrição da proposta

TODO: DESCREVER MELHOR A PROPOSTA INCLUINDO ORÇAMENTO, INFORMAÇÕES DO CLIENTE, 

Pensando nisso sera desenvolvido um software para automatizar o serviço da assistência de Rafael com gerenciamento de venda, gasto, garantia, andamento do serviço.

# Regras de negócio

TODO: REVISAR ORTOGRAFIA E FORMATO

**RN001 - Cadastro de cliente:** - O cliente fará seu cadrastro na loja preenchendo um formulário com informações cruciais para sua identificação.

RN002-O software apresentara uma tela para o cliente, para ser feita a descrição do problema com um campo para inserção de fotos e videos do aparelho eletronico em questão.

RN003-O sistema devera gerar uma ordem de serviço quando o cliente cadrastrado deixar seu aparelho eletronico na assistencia, com uma formatação contendo informações, que aparelho é, quando o aparelho entrou, e o numero da ORDEM DE SERVIÇO.

RN004-Apos a detalhação do problema apos o aparelho entregue a assistencia, sera gerado uma ordem de serviço 

RN005-Orçamento:Antes de realizar qualquer serviço, a assistência técnica deve informar ao cliente o valor do reparo apos a examinação do aparelho.

RN006-Sera gerado com o numero da ordem de serviço, uma barra de progresso do aparelho eletronico em estagios de (Em fila/Proximo da fila/Em examinação/Orçamento Disponivel/Em reparo/Disponivel pra retirada).

RN007-Apos o reparo concluido e o pagamento recebido, sera gerado a garantia de serviço de 90 dias com valor do reparo com data de saida do aparelho.

# Requisitos funcionais

RF001(Cadrastramentos)-O sistema deve permitir que o cliente se cadrastre para ter acesso a os serviços.

RF002(Acesso ao sistema)- O sistema devera permitir que o administrador tenha acesso a todas informções, o atendente a algumas areas de acesso e o cliente apenas a sua respectiva area.

RF003(Primero contato)-O sistema deve permitir que os clientes entrem em contato com a assistencia tecnica por mensagens eletrônicas ou pessoalmente para solicitar orçamentos para seus aparelhos eletrônicos.

RF004(Geração de ordem de serviço)-O sistema deve permitir que o atendente gere uma ordem de serviço para o cliente.

RF005(Codigo de acompanhamento)-O sistema deve permitir que seja gerado um codigo na ordem de serviço.

 
 RF006(Acompahmento em tempo real)-O sistema deve permitir que haja uma barra de status do serviço com o codigo.(Em fila/Proximo da fila/Em examinação/Orçamento Disponivel/Em reparo/Disponivel pra retirada).
 
RF007(Avisos previos)-O sistema deve permitir que o atendente possa se comunicar com o cliente para qualquer alteração fora do esperado/combinado.

RF008(Não aprovamento orçamentario)-O sistema deve permitir que caso o orçamento não seja aprovado o aparelho seja separado em outro lugar, para ser recolhido pelo dono do aparelho apenas com a ordem de serviço ou codigo.

RF009(Reparo concluido)-O sistema deve permitir a geração de uma nota fiscal com garantia de 90 dias do serviço, apos o pagamento integral do reparo.

# Requisitos não funcionais

RNF001-Segurança: O formulário preenchido pelo cliente deve garantir a privacidade e segurança dos dados fornecidos.

RBF002-Usabilidade: A interface do software deve ser amigável e intuitiva para permitir que o cliente descreva com clareza o problema com seu aparelho eletrônico.

RNF003-Confiabilidade: O sistema deve gerar corretamente a ordem de serviço com as informações relevantes (aparelho, data de entrada, número da ordem de serviço).

RNF004-Escalabilidade: O sistema deve ser capaz de gerar ordens de serviço para um grande número de clientes sem comprometer a sua eficiência.

RNF005-Transparência: A assistência técnica deve informar ao cliente o valor do reparo antes de realizar qualquer serviço.

RNF006-Rastreabilidade: O sistema deve fornecer uma barra de progresso para que o cliente possa acompanhar o andamento do reparo do seu aparelho eletrônico.

RNF007-Confiabilidade: O sistema deve gerar corretamente a garantia de serviço de 90 dias com o valor do reparo e data de saída do aparelho.
