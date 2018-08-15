# Encontrando as chaves de API e Criptografia

As chaves de acesso (API e Criptografia) do Pagar.me podem ser encontradas na sua Dashboard, seguindo o caminho Menu > Configurações > Geral. Para visualizá-las, clique na setinha localizada no canto superior direito da caixinha Chaves da API e criptografia. 

Nesta tela, você tem acesso a informações sobre as taxas cobradas e também às chaves, para utilizá-las clique em "Chaves de API e Criptografia", como mostra a imagem abaixo. 

<img src="https://user-images.githubusercontent.com/29930809/44131962-b35f9fb4-a02c-11e8-8637-83f3007cee32.png" alt="Menu Chaves de API" /> 

Nesta tela estão disponíveis as chaves de API e Criptografia. Elas variam de acordo com o modo da dashboard que você está acessando e podem ser:

**API Live**:  essa é a chave mais importante para o nosso sistema, pois ela funciona como uma autenticação instransferível para a sua conta. Seu uso é necessário para que sua aplicação consiga criar transações, planos, transferências etc., por isso é muito importante que você a mantenha segura. As chaves de "Live" são utilizadas para criar transações reais, ou seja, deve ser utilizada no ambiente de produção (Live) da sua Dashboard. 

**Criptografia Live**: essa chave também é utilizada como uma forma de autenticação, mas apenas para autorização de transações e geração de chaves públicas para encriptação de dados. A chave "Live" deve ser usada em operações que estejam sendo realizadas em ambiente de produção. 

<img src="https://user-images.githubusercontent.com/29930809/44131937-8d4e19cc-a02c-11e8-8d81-d0a0c03eb59c.png" alt="Chaves Live" /> 

**API Test**: a chave de API "Test" é utilizada para as mesmas situações citadas acima (para que sua aplicação consiga criar transações, planos, transferências etc.) e seu uso também é instransferível, por isso assim como a "Live" ela também deve ser mantida em segurança. A API Test deve ser utilizada apenas para operações realizadas em modo teste, pois as transações criadas com ela não geram recebíveis reais. 

**Criptografia Test**: a chave de Criptografia "Test" é utilizada para as mesmas situações citadas acima (autorização de transações e geração de chaves públicas para encriptação de dados). Essa chave deve ser utilizada apenas para operações realizadas em modo teste, pois as transações criadas com ela não geram recebíveis reais.

<img src="https://user-images.githubusercontent.com/29930809/44131938-8d72ec20-a02c-11e8-9759-0fed55ae7d2a.png" alt="Chaves Teste" /> 

Para utilizar a chave necessária, clique no botão "Copiar" e cole-a onde ela deve ser informada, por exemplo no corpo de uma requisição que contenha o parâmetro etc. Para mais informações sobre as rotas, acesse a nossa [Documentação](https://docs.pagar.me/reference) :). 

<img src="https://user-images.githubusercontent.com/29930809/44131939-8d96b876-a02c-11e8-9a43-37dc92b47556.png" alt="Copiar chaves" />
