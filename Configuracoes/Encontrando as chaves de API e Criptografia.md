# Encontrando as chaves de API e Criptografia

As chaves de acesso (API e Criptografia) do Pagar.me podem ser encontradas na sua Dashboard, seguindo o caminho Menu > Configurações > Geral. Para visualizá-las, clique na setinha localizada no canto superior direito da caixinha Chaves da API e criptografia. 

Nesta tela, você tem acesso a informações sobre as taxas cobradas e também às chaves, para utilizá-las clique em "Chaves de API e Criptografia", como mostra a imagem abaixo. 

[inserir imagem] 

Nesta tela, estão disponíveis as chaves de: 

**API Live**:  essa é a chave mais importante para o nosso sistema, pois ela funciona como uma autenticação instransferível para a sua conta. Seu uso é necessário para que sua aplicação consiga criar transações, planos, transferências etc., por isso é muito importante que você a mantenha segura. As chaves de "Live" são utilizadas para criar transações reais, ou seja, deve ser utilizada no ambiente de produção (Live) da sua Dashboard. 

**API Test**: a chave de API "Test" é utilizada para as mesmas situações citadas acima (para que sua aplicação consiga criar transações, planos, transferências etc.) e seu uso também é instransferível, por isso assim como a "Live" ela também deve ser mantida em segurança. A API Test deve ser utilizada apenas para operações realizadas em modo teste, pois as transações criadas com ela não geram recebíveis reais. 

**Criptografia Live**: essa chave também é utilizada como uma forma de autenticação, mas apenas para autorização de transações e geração de chaves públicas para encriptação de dados. A chave "Live" deve ser usada em operações que estejam sendo realizadas em ambiente de produção. 

**Criptografia Test**: a chave de Criptografia "Test" é utilizada para as mesmas situações citadas acima (autorização de transações e geração de chaves públicas para encriptação de dados). Essa chave deve ser utilizada apenas para operações realizadas em modo teste, pois as transações criadas com ela não geram recebíveis reais.

Para utilizar a chave necessária, clique no botão "Copiar" e cole-a onde ela deve ser informada, por exemplo no corpo de uma requisição que contenha o parâmetro etc. Para mais informações sobre as rotas, acesse a nossa [Documentação](https://docs.pagar.me/reference) :). 


[inserir imagem do botão de copiar]
