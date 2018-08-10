Para estornar uma transação, primeiro você precisa encontrá-la. Entre em "Transações", no menu lateral, e use as [opções de busca](https://github.com/pagarme/Manual-Pilot-Alfa/blob/master/Transacoes/Encontrando%20transa%C3%A7%C3%B5es.md) para achar a compra que precisa ser estornada. 

Assim que você encontrar a transação desejada, clique uma vez nela para abrir as opções avançadas e então clique em "[Ver detalhes](https://pagarme.github.io/Manual-NovaDashboard-Alfa/Vendo%20os%20detalhes%20de%20uma%20transa%C3%A7%C3%A3o)". No topo da tela que é aberta existe o botão "Estornar", clique nele. Caso a transação tenha sido paga por Cartão de crédito, é preciso seguir os passos a seguir para realizar a devolução total ou parcial do valor.

## 1) Indique o valor a ser estornado

Para transações feitas por Cartão de crédito, existe um mecanismo automático de devolução do valor, então você só precisa confirmar os dados já indicados no modal. A única mudança possível nesse caso é o valor, já que você pode fazer um estorno parcial de uma compra.

No campo "Valor", é indicado por padrão o total da compra, mas você pode estornar apenas uma parte disso. Um cenário no qual isso faz sentido é se o cliente tiver comprado vários itens e um ou mais deles não tiverem sido entregues, mas os outros sim. Nessa situação, o valor estornado seria apenas do que não foi enviado para o cliente. 

**Atenção**: transações que passaram pela Rede e pela eRede possuem o limite de R$ 5.000,00 de valor para estorno. Para fazer o estorno de um montante maior do que esse, é preciso criar dois ou mais estornos parciais de valores menores, até atingir a quantia certa.

<p align="center" > <img src="img/Transações/Estornando Transacoes Cartao/modalEstorno.png" /> </p>


## 2) Confirme os dados

Ao clicar em "Continuar", uma nova tela é aberta na qual você precisa rever os dados para saber se está tudo correto. Se estiver, é necessário fazer a autenticação no campo "Digite a sua senha", para garantir que é você mesmo que está realizando essa ação. Se o valor estiver errado, clique no botão "Voltar" para retornar à tela anterior. 

Para estorno parcial, a transação permanece com o status "Pago". Para estornos totais, o status da transação é alterado primeiro para "Estorno pendente" e depois para "Estornado" apenas quando ocorrer a confirmação pela adquirente de que o estorno foi aceito. Para estornos de Cartão de crédito, existe um limite para até quantos dias depois da transação você pode realizar a devolução do valor. Esse limite depende da adquirente:

- **Stone**: 350 dias
- **Cielo**: 300 dias
- **Rede e eRede**: 60 dias

Tenha em mente que a partir do momento que você clicar em "Estornar Transação", isso não pode ser desfeito. 

<p align="center" > <img src="img/Transações/Estornando Transacoes Boleto/modalConfirmacao.png" /> </p>

Na última tela do modal é mostrado o comprovante do estorno: 

<p align="center" > <img src="img/Transações/Estornando Transacoes Cartao/modalOperacao.png" /> </p>

Se você clicar em "Visualizar transação", vai para a tela de [detalhes dessa compra](link para artigo de detalhes da transação), que agora mostra esse estorno – total ou parcial – na coluna "Histórico da transação".  
