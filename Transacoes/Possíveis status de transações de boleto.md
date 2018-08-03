Os status possíveis para uma transação de Boleto bancário são:

#### Aguardando registro
Para Boletos registrados, a transação fica alguns segundos com esse status, [enquanto aguardamos a resposta do banco](https://pagarme.zendesk.com/hc/pt-br/articles/115004484383-O-processamento-da-transa%C3%A7%C3%A3o-ficar%C3%A1-mais-lento-com-o-procedimento-de-registro-dos-boletos-).

#### Aguardando pagamento
O Boleto foi gerado e está aguardando pagamento. Esse status permanece até que o pagamento seja **conciliado** no nosso sistema, o que acontece em [até um dia útil](https://pagarme.zendesk.com/hc/pt-br/articles/206350686-Em-quanto-tempo-o-status-de-aguardando-pagamento-%C3%A9-alterado-para-pago-), então é possível que o seu cliente alegue que já pagou o boleto, mas a transação não tenha mudado de status no sistema.

#### Paga
O Boleto foi pago com o valor correto e conciliado.

#### Estorno Pendente
O estorno total da transação foi enviado, mas a conciliação ainda não aconteceu, então o seu cliente ainda não recebeu o valor na sua conta. Neste ponto, não é possível desfazer a operação.

#### Estornada
A conciliação aconteceu e o valor total da transação foi estornado com sucesso.

#### Boleto pago com valor superior
O seu cliente pagou o Boleto com um valor superior. Você pode entrar em contato com ele para fazer um estorno parcial para devolver a diferença.

#### Boleto pago com valor inferior
O seu cliente pagou o Boleto com um valor inferior. Você pode entrar em contato e emitir um novo Boleto para o pagamento, mas tenha em mente que uma nova taxa de pagamento de Boleto será cobrada, então você pode repassar isso para o cliente ou absorver essa diferença.

#### Recusada
Transações de boleto com esse status indicam que aquele boleto **deveria ser registrado**, porém os dados do pagador – nome e documento (CPF e CNPJ) – não foram passados corretamente e, por isso, o documento não foi gerado.  

Atenção: isso acontece apenas na versão [2013-03-01 da API](https://docs.pagar.me/docs/versionamento); nas outras versões, a transação nem é criada e uma mensagem de erro é mostrada. 
