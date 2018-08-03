Quando você clica em uma transação da lista, pode abrir uma tela para ver os seus detalhes. É nessa tela que você encontra tudo o que precisa saber sobre aquela compra. Além disso, este é o lugar para reprocessar, estornar ou exportar os dados de uma transação.

Logo no topo da tela estão os detalhes principais: o ID e o status da transação, a forma de pagamento (Boleto bancário, Cartão à vista ou Cartão parcelado) e o valor que foi autorizado, para compras feitas com Cartão de crédito, ou o valor do Boleto que foi gerado, para compras feitas com Boleto bancário.

Reprocessar, estornar e exportar
(imagem do topo, com os três botões)

Na parte de cima da tela existem três botões: reprocessar, estornar e exportar. O primeiro, como o nome sugere, permite reprocessar uma transação se algo deu errado no momento da sua criação.(ver mais detalhes).

O segundo botão, "Estornar", permite devolver o valor integral ou parcial de uma compra para o cliente. Quando você clica nele, um modal é aberto e guia você pelos passos necessários para realizar o estorno, que pode ser feito para compras de Cartão de crédito ou Boleto. Para saber mais sobre os passos para estornar uma transação, clique aqui (link para página Estornando uma transação do manual).

O último botão permite exportar em um arquivo todos os detalhes da compra, como se encontram no momento. Por exemplo, se você exportar os detalhes de uma transação que está com o status "Pago", e depois ela sofrer um chargeback, o arquivo que foi exportado não é atualizado e perde a validade.

Valor capturado, saídas e valor líquido
É possível acompanhar rapidamente quanto você vai efetivamente receber em uma venda: na parte de cima da tela existem três dados em cards: "Valor capturado", "Total de saídas" e "Valor líquido".

(imagem cards)

O primeiro indica quanto foi efetivamente capturado na transação, isto é, o valor bruto da venda. O segundo card mostra todos os descontos e outras saídas que podem ter sido aplicadas ao valor, como o MDR, um estorno parcial ou total e outros.

Por fim, o valor líquido é uma conta simples entre os dois primeiros: o valor capturado menos o total de saídas, e representa quanto você efetivamente tem para receber naquela transação. Esse valor, se não for antecipado, fica disponível para saque de acordo com as datas de liquidação normais: D+2 para Boleto bancário e D+29 + 2 dias úteis para Cartão de crédito.

Histórico da Transação
Essa coluna, mostrada como uma linha do tempo, traz as informações mais relevantes sobre os eventos de uma transação. Essa timeline é mostrada de cima para baixo – isto é, eventos mais antigos são mostrados para baixo, e os mais recentes ficam no topo da coluna.

(imagens com vários cenários de histórico)

Normalmente, o primeiro evento dessa coluna é a autorização da operadora de cartão, para vendas por Cartão de crédito, e depois a análise do antifraude. Outros eventos mostrados são a captura, a emissão e pagamento do boleto, eventuais chargebacks e estornos e a liquidação do valor (isto é, quando o valor daquela compra fica disponível no seu saldo para saque).

Parcelas de uma transação
No campo "Parcelas" é possível ver todas as parcelas de uma transação de Cartão de crédito. É ali que você vê quais parcelas já foram pagas – ou seja, quais você já recebeu – e quais você ainda receberá. Cada parcela traz os seguintes dados: status, data de pagamento, total bruto, MDR, serviço de antecipação, estorno ou chargeback e valor líquido.

(imagem colunas de parcelas)

O "Total bruto" é o valor pago pelo seu cliente naquela parcela. O MDR é o desconto da adquirente e o serviço de antecipação é a taxa aplicada caso você tenha antecipado aquela parcela. Se foi realizado o estorno total ou parcial da compra, ou se o seu cliente tiver solicitado o chargeback, isso é mostrado na coluna "Estorno ou chargeback".

Por fim, a coluna "Valor líquido" mostra a seguinte conta: total bruto menos o valor das colunas MDR, Serviço de antecipação e Estorno ou chargeback. Esse é o valor que você vai efetivamente receber, seguindo as datas de liquidação do banco. Isto é, caso a transação tenha de 2 a 12 parcelas, o recebimento é feito da seguinte forma: primeira parcela em 29+2 dias úteis, segunda em aproximadamente 62, terceira em aproximadamente 93 dias, e assim por diante.

Detalhes do cliente, Detalhes da transação e Metadata
As informações dos campos Detalhes do cliente, Detalhes da transação e Metadata são fixas: isto é, elas são passadas no momento da criação da transação e não mudam depois. Nesses campos você pode ver todas as informações que foram passadas para o nosso sistema quando a transação foi criada, como o nome do cliente, dados de documento, telefone, endereço e e-mail, operadora de cartão usada na compra, resposta do antifraude, ID da transação e outros.

Em Metadata é possível visualizar tudo o que o seu sistema passou como esse tipo de dado no momento da criação ou da captura de uma transação. Se você quiser saber mais sobre este recurso, veja essa explicação na nossa documentação.
