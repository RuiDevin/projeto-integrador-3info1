# projeto-integrador-3info1
Projeto feito por Rafael Alvaro Almeida

Rafael possui um negocio de manutenção de celulares e desktops/notebooks e deseja que seja desenvolvido para o seu negocio, um sistema de ORDEM DE SERVIÇO afim de unifromizar, otimizar e administrar sua empresa.

Ate então Rafael gere suas manutenções da seguinte forma...

-Entram em contato com Rafael por mensagens eletronicas ou pessoalmente para ele fazer orçamnentos sem compromisso com ele do aparelho eletronico, embora os possiveis clientes cravem aonde esta o problema Rafael sempre faz uma inspeção no eletronico afim de confirmar aonde realmente esta o problema e se realmente aquele realmente eo problema...
-Uma vez encontrado o problema Rafael faz uma busca pelo componente eletronico afim de ver o preço e um prazo de entrega, feito isso entro em contato com o cliente e aviso o valor do reparo e o prazo para a resolução do problema do aparelho eletronico...
-Rafael faz pesquisas no mercado local/nacional/internacional para disponibilizar ao menos de 2 a 3 orçamentos para o cliente...
-Se  o cliente aceitar o orçãmento feito Rafael encomenda a peça e realiza o reparo, e no final de tudo ele avisa o cliente que o aparelho esta pronto, e pode ser recolhido pelo cliente...
-Rafael oferece 3 meses de garantia em reparos de eletronicos exceto em serviços de limpeza do equipamento eletronico...
-Rafael armazena as garantias de serviços em nota fiscais de compra de componentes dos serviços realizados isto porque, as peças que  ele compra possuem a garantia de 3 meses oferecidas pela fabricante/distribuidora de peças...
-Caso algum cliente faça queixas do aparelho eletronico que não funciona por causa do reparo
-Se o cliente não aceitar orçamento, Rafael deixa o aparelho do mesmo que se encontrava quando o recebeu se possivel for, e o cliente podera vir buscar o aparelho eletronico...

REGRAS DE NEGOCIO 


RN001-O cliente fara seu cadrastro na loja preenchendo um formulario com informações cruciais para sua identificação.
RN002-O software apresentara uma tela para o cliente, para ser feita a descrição do problema com um campo para inserção de fotos e videos do aparelho eletronico em questão.
RN003-O sistema devera gerar uma ordem de serviço quando o cliente cadrastrado deixar seu aparelho eletronico na assistencia, com uma formatação contendo informações, que aparelho é, quando o aparelho entrou, e o numero da ORDEM DE SERVIÇO.   
RN004-Apos a detalhação do problema apos o aparelho entregue a assistencia, sera gerado uma ordem de serviço
RN005-Orçamento:Antes de realizar qualquer serviço, a assistência técnica deve informar ao cliente o valor do reparo apos a examinação do aparelho.
RN006-Sera gerado com o numero da ordem de serviço, uma barra de progresso do aparelho eletronico em estagios de 
(Em fila/Proximo da fila/Em examinação/Orçamento Disponivel/Em reparo/Disponivel pra retirada)
RN007-Apos o reparo concluido e o pagamento recebido, sera gerado a garantia de serviço de 90 dias com valor do reparo com data de saida do aparelho.

Requisitos Funcionais

RF001(Cadrastramentos)-O sistema deve permitir que o cliente se cadrastre para ter acesso a os serviços.
RF002(Acesso ao sistema)- O sistema devera permitir que o administrador tenha acesso a todas informções, o atendente a algumas areas de acesso e o cliente apenas a sua respectiva area.  
RF003(Primero contato)-O sistema deve permitir que os clientes entrem em contato com a assistencia tecnica por mensagens eletrônicas ou pessoalmente para solicitar orçamentos para seus aparelhos eletrônicos.
RF004(Geração de ordem de serviço)-O sistema deve permitir que o atendente gere uma ordem de serviço para o cliente.
RF005(Codigo de acompanhamento)-O sistema deve permitir que seja gerado um codigo na ordem de serviço
RF006(Acompahmento em tempo real)-O sistema deve permitir que haja uma barra de status do serviço com o codigo.(Em fila/Proximo da fila/Em examinação/Orçamento Disponivel/Em reparo/Disponivel pra retirada) 
RF007(Avisos previos)-O sistema deve permitir que o atendente possa se comunicar com o cliente para qualquer alteração fora do esperado/combinado.
RF008(Não aprovamento orçamentario)-O sistema deve permitir que caso o orçamento não seja aprovado o aparelho seja separado em outro lugar, para ser recolhido pelo dono do aparelho apenas com  a ordem de serviço ou codigo. 
RF009(Reparo concluido)-O sistema deve permitir a geração de uma nota fiscal com garantia de 90 dias do serviço, apos o pagamento integral do reparo.

Requisitos não funcionais

RNF001-Segurança: O formulário preenchido pelo cliente deve garantir a privacidade e segurança dos dados fornecidos.

RBF002-Usabilidade: A interface do software deve ser amigável e intuitiva para permitir que o cliente descreva com clareza o problema com seu aparelho eletrônico.

RNF003-Confiabilidade: O sistema deve gerar corretamente a ordem de serviço com as informações relevantes (aparelho, data de entrada, número da ordem de serviço).

RNF004-Escalabilidade: O sistema deve ser capaz de gerar ordens de serviço para um grande número de clientes sem comprometer a sua eficiência.

RNF005-Transparência: A assistência técnica deve informar ao cliente o valor do reparo antes de realizar qualquer serviço.

RNF006-Rastreabilidade: O sistema deve fornecer uma barra de progresso para que o cliente possa acompanhar o andamento do reparo do seu aparelho eletrônico.

RNF007-Confiabilidade: O sistema deve gerar corretamente a garantia de serviço de 90 dias com o valor do reparo e data de saída do aparelho.




