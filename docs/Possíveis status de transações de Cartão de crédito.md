Os status possíveis para uma transação de Cartão de crédito são:

#### Processando
A transação está sendo [processada](https://pagarme.zendesk.com/hc/pt-br/articles/115000552123-Porque-a-transa%C3%A7%C3%A3o-permaneceu-com-o-status-Processando-).
#### Autorizada 
A transação foi autorizada pela operadora do cartão e precisa ser [capturada](https://pagarme.zendesk.com/hc/pt-br/articles/206300363-Qual-a-diferen%C3%A7a-entre-autoriza%C3%A7%C3%A3o-e-captura-de-uma-transa%C3%A7%C3%A3o-).
#### Paga
A transação foi autorizada e capturada. O valor fica disponível na sua conta em D+29+2 dias úteis, ou você pode [antecipar o recebimento](https://pagarme.zendesk.com/hc/pt-br/articles/217029766-O-que-%C3%A9-antecipa%C3%A7%C3%A3o-).
#### Recusada
A transação foi recusada. os motivos podem ser: 
- **Banco emissor**: transação recusada pela emissora de cartão; 
- **Erro interno**: transação recusada por um erro interno, que pode ser por instabilidade no sistema da Pagar.me ou do antifraude; 
- **Sem adquirente**: transação recusada sem passar pela adquirente. Isso pode ocorrer porque a bandeira de cartão não foi reconhecida/não é suportada pelas adquirentes que trabalhamos; por não ter um "Nome na fatura" cadastrado; quando a opção de cartão de crédito não está liberada no adquirente Pagar.me ou quando o adquirente da conta está desabilitado (conta inativada); 
- **Timeout de captura**: transação recusada por ter expirado o período de captura (no caso de checkout Pagar.me, 5 horas; e no de checkout transparente, 5 dias.); 
- **Timeout da adquirente**: transação recusada por não ter um retorno da adquirente dentro do prazo esperado; 
- **Valor de captura inválido**: transação recusada por tentar capturar um valor superior ao valor autorizado; 
- **Antifraude**: transação recusada pelo antifraude, de acordo com as regras configuradas.
#### Estorno Pendente
O estorno da transação foi enviado, mas a adquirente ainda não respondeu a solicitação. Neste ponto, não é possível desfazer a operação.
#### Estornada
A adquirente respondeu a solicitação e a transação foi estornada. Se a resposta for negativa, a transação volta a aparecer como _Paga_.
#### Chargeback
O pagador solicitou o chargeback para o banco. [Veja aqui o que isso quer dizer](https://pagarme.zendesk.com/hc/pt-br/articles/204767349-O-que-%C3%A9-chargeback-).
#### Chargeback reapresentado
O chargeback foi [reapresentado](https://pagarme.zendesk.com/hc/pt-br/articles/115002814371-Reapresenta%C3%A7%C3%A3o-de-chargeback-a-forma-mais-segura-de-tentar-reaver-seu-dinheiro) e o dinheiro voltou para a sua conta. Tenha em mente que a reapresentação pode **não** ser aceita pelo banco, nesse caso a transação volta para o status *Chargeback* e o dinheiro volta novamente para o cliente.
