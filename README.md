https://bitcoincore.org

O que é Bitcoin?

Bitcoin é uma moeda digital experimental que permite pagamentos instantâneos para qualquer pessoa, em qualquer lugar do mundo. Bitcoin usa a tecnologia peer-to-peer para operar com nenhuma autoridade central: gerenciamento de transações e de emissão de dinheiro são realizadas coletivamente pela rede. Bitcoin Core é o nome do software de código aberto que permite o uso desta moeda.

Para mais informações, bem como uma versão imediatamente utilizável, binário do software Bitcoin Core, veja https://bitcoin.org/en/download , ou ler o whitepaper originais .

Licença

Bitcoin núcleo é liberado sob os termos da licença MIT. Veja COPYING para mais informações ou ver https://opensource.org/licenses/MIT .

Processo de desenvolvimento

O masterramo é regularmente construído e testado, mas não é garantido para ser completamente estável. Etiquetas são criados regularmente para indicar nova oficial, versões versão estável do Bitcoin Core.

O fluxo de trabalho contribuição é descrito no CONTRIBUTING.md .

O desenvolvedor mailing list deve ser usado para discutir mudanças complicadas ou controversos antes de trabalhar em um conjunto de patches.

Desenvolvedor IRC pode ser encontrado na rede Freenode em # bitcoin-core-dev.

ensaio

Teste e revisão de código é o gargalo para o desenvolvimento; temos mais solicitações de pull do que podemos rever e teste em curto prazo. Por favor, seja paciente e ajudar, testando solicitações de pull de outras pessoas, e lembre-se este é um projeto de segurança crítica, onde qualquer erro pode custar pessoas muito dinheiro.

Teste automatizado

Desenvolvedores são encorajados a escrever testes de unidade para o novo código, e de apresentar novos testes de unidade para código antigo. Os testes de unidade pode ser compilado e executar (assumindo que eles não foram desabilitados na configure) com:make check

Há também testes de regressão e integração da interface RPC, escritos em Python, que são executados automaticamente no servidor de compilação. Estes testes podem ser executados (se as dependências do teste são instalados) com:qa/pull-tester/rpc-tests.py

O sistema Travis CI torna-se de que cada solicitação de recebimento é construído para Windows, Linux e OS X, e que os testes de unidade / sanidade são executados automaticamente.

Manual de Garantia de Qualidade (QA) Testing

As alterações devem ser testados por alguém que não seja o programador que escreveu o código. Isto é especialmente importante para grandes alterações ou de alto risco. É útil para adicionar um plano de teste para a atração pedido descrição se testar as alterações não é simples.

traduções

Mudanças a traduções, bem como novas traduções podem ser submetidos a página Transifex do Bitcoin Núcleo .

Traduções são periodicamente retirado do Transifex e se fundiram para o repositório git. Veja o processo de tradução para obter detalhes sobre como isso funciona.

Importante : Não aceitamos alterações de translação como solicitações de pull GitHub porque o próximo gole Transifex seria automaticamente substituí-los novamente.

Tradutores também deve assinar a lista de discussão .
