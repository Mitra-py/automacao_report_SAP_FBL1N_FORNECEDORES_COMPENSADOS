# automacao_report_SAP_FBL1N_FORNECEDORES_COMPENSADOS

Automação tem o objetivo de tratar e reclassificar problemas de códigos nas colunas e trazer análise que possibilitem a visualização e tomada de decisão. Portanto, a automação foi dividida a priori em 2 blocos.

Bloco 1 : problemas de códigos nas colunas tipo de documento, forma de pagamento, doc de compensação, bloqueio, condições de pagamento que vem em formato de códigos (letras e números) para a visualização de dados não é possível identificar de forma proativa ao que se refere cada informação.

Bloco 2: identificar dentre os pagamento realizados a diferença entre a data de emissão e lançamento, que nesse contexto nos permite análisar o tempo em que essa nota demora a ser enviada para processamento desde sua emissão, a diferença entre data de emissão, vencimento e condição de pagamento, possibilitando verificar se o pagamento ocorreu dentro das condições | vencimento previsto. 

Solução a automação trata e reclassifica esse códigos trazendo novas colunas De-Para. Por exemplo: o tipo de documento ZP = Lançamento de pagamento, formas de pagamento se Y (Depósito), se (B) Manuais e etc.. O documento de compensação que se inicia-se com 110 sendo desmembramentos, 350 sendo estornos e 200 sendo pagamentos, foram tratatdos e a automação retorna uma coluna com o status de "Pago, Desmembrado e Estorno", os tipos de bloqueio de pagamento e após essa tratativa realiza a análise do bloco 2 retornado as colunas com a informação NF Lançada no prazo, NF Lançada posterior à emissão, Pago antecipado das condições | vencimento de pagamento, Pago dentro das condições | vencimento de pagamento, Pago fora das condições | vencimento de pagamento.




