Cota-parlamentar-analytics
==========================

BI and Open Data Project about "Cota de gastos de cada deputado" powered by IT4DGroup.

Para checar a cota de gastos de cada deputado, a Câmara publica as informações aqui:
http://www2.camara.leg.br/transparencia/cota-para-exercicio-da-atividade-parlamentar

E aqui está o link para o download em XML:
http://www2.camara.leg.br/transparencia/cota-para-exercicio-da-atividade-parlamentar/dados-abertos-cota-parlamentar

Texto extraído do site da Câmera dos Deputados:

Cota para Exercício da Atividade Parlamentar
Dados Abertos - Cota Parlamentar

Cota para Exercício da Atividade Parlamentar em Dados Abertos.

Este serviço de Dados Abertos disponibiliza arquivos XML compactados para download contendo os dados relativos aos gastos parlamentares registrados na Câmara dos Deputados. O acesso é gratuito e não requer autorização de uso. 

IMPORTANTE:  Esta é uma versão beta teste dos serviços de Dados Abertos da Câmara dos Deputados. O uso durante esse período implica em aceitar alterações na estrutura dos dados sem aviso prévio.

Para baixar os arquivos (download), clique em um dos links abaixo:

Dados Abertos do ano atual
Dados Abertos do ano anterior
Dados Abertos dos demais anos anteriores

Consulte as explicações sobre o formato dos arquivos.

Dicionário de Dados:
http://www2.camara.leg.br/transparencia/cota-para-exercicio-da-atividade-parlamentar/explicacoes-sobre-o-formato-dos-arquivos-xml


Explicações sobre o formato dos arquivos XML

Dados Abertos - Cota Parlamentar

A seguir, são expostas as explicações pertinentes a cada elemento de dado publicado como "Dados Abertos" acerca das despesas realizadas e publicadas na Transparência, quanto ao uso da CEAP (Cota para o Exercício da Atividade Parlamentar). Essas despesas se confirmam por meio de lançamento de débitos contra a cota do deputado e podem decorrer em razão de uma das causas a seguir: pelo reembolso de documentos fiscais emitidos (Notas Fiscais, Recibos ou Despesa no Exterior); ou pelo custeio de despesas telefônicas; ou pelo débito de requisição de serviços postais; ou pela emissão de bilhetes aéreos. 

Elemento de Dado

Nome do Dado

Definição do Dado

txNomeParlamentar

Nome Parlamentar

Nome adotado pelo Parlamentar ao tomar posse do seu mandato. Compõe-se de dois elementos: um prenome e o nome; dois nomes; ou dois prenomes, salvo, a juízo do Presidente da Casa legislativa, que poderá alterar essa regra para que não ocorram confusões.

nuCarteiraParlamentar

Número da  Carteira Parlamentar

Documento usado para identificar um deputado federal na CD. Pode alterar a cada Legislatura nova.

nuLegislatura

Número da  Legislatura

Legislatura: Período de quatro anos coincidente com o mandato parlamentar dos Deputados Federais. No contexto da cota CEAP, representa o ano base de início da legislatura e é utilizado para compor a Carteira Parlamentar, pois esta poderá ser alterada à medida que se muda de Legislatura.

sgUF

Sigla da UF

No contexto da cota CEAP, representa a unidade da federação pela qual o deputado foi eleito e é utilizada para definir o valor da cota a que o deputado tem.

sgPartido

Sigla do Partido

O seu conteúdo representa a sigla de um partido. Definição de partido: é uma organização formada por pessoas com interesse ou ideologia comuns, que se associam com o fim de assumir o poder para implantar um programa de governo. Tem personalidade jurídica de direito privado e goza de autonomia e liberdade no que diz respeito à criação, organização e funcionamento, observados os princípios e preceitos constitucionais.

codLegislatura

Código da Legislatura

Legislatura: Período de quatro anos coincidente com o mandato parlamentar dos Deputados Federais. No contexto da cota CEAP, o seu conteúdo representa o código identificador da Legislatura, que um número ordinal sequencial, alterado de um em um, a cada início de uma nova Legislatura (por exemplo, a Legislatura que iniciou em 2011 é a 54ª Legislatura).

numSubCota

Número da Subcota

No contexto da Cota CEAP, o conteúdo deste dado representa o código do Tipo de Despesa referente à despesa realizada pelo deputado e comprovada por meio da emissão de um documento fiscal, a qual é debitada na cota do deputado.

txtDescricao

Descrição da Subcota

O seu conteúdo é a descrição do Tipo de Despesa relativo à despesa em questão.

numEspecificacaoSubCota

Número da Especificação da Subcota

No contexto da Cota CEAP, há despesas cujo Tipo de Despesa necessita ter uma especificação mais detalhada (por exemplo, “Combustível”). O conteúdo deste dado representa o código desta especificação mais detalhada.

txtDescricaoEspecificacao

Descrição da Especificação da Subcota

Representa a descrição  especificação mais detalhada de um referido Tipo de Despesa.

txtFornecedor

Fornecedor

O conteúdo deste dado representa o nome do fornecedor do produto ou serviço presente no documento fiscal

txtCNPJCPF

CNPJ/CPF

O conteúdo deste dado representa o CNPJ ou o CPF do emitente do documento fiscal, quando se tratar do uso da cota em razão do reembolso despesas comprovadas pela emissão de documentos fiscais.

txtNumero

Número do Documento

O conteúdo deste dado representa o número de face do documento fiscal emitido ou o número do documento que deu causa à despesa debitada na cota do deputado.

indTipoDocumento

Indicativo de Tipo de Documento Fiscal

Este dado representa o tipo de documento do fiscal – 0 (Zero), para Nota Fiscal; 1 (um), para Recibo; e 2, para Despesa no Exterior.

datEmissao

Data de Emissão

O conteúdo deste dado é a data de emissão do documento fiscal ou a data do documento que tenha dado causa à despesa.

vlrDocumento

Valor do Documento

O seu conteúdo é o valor de face do documento fiscal ou o valor do documento que deu causa à despesa.

vlrGlosa

Valor da Glosa

O seu conteúdo representa o valor da glosa do documento fiscal que incidirá sobre o Valor do Documento, ou o valor da glosa do documento que deu causa à despesa.

vlrLiquido

Valor Líquido

O seu conteúdo representa o valor líquido do documento fiscal ou do documento que deu causa à despesa e será calculado pela diferença entre o Valor do Documento e o Valor da Glosa. É este valor que será debitado da cota do deputado.

numMes

Mês

O seu conteúdo representa o Mês da competência financeira do documento fiscal ou do documento que deu causa à despesa. É utilizado, junto com o ano, para determinar em que período o débito gerará efeito financeiro sobre a cota.

numAno

Ano

O seu conteúdo representa o Ano da competência financeira do documento fiscal ou do documento que deu causa à despesa. É utilizado, junto com o mês, para determinar em que período o débito gerará efeito financeiro sobre a cota.

numParcela

Número da Parcela

O seu conteúdo representa o número da parcela do documento fiscal. Ocorre quando o documento tem de ser reembolsado de forma parcelada.

txtPassageiro

Passageiro

O conteúdo deste dado representa o nome do passageiro, quando o documento que deu causa à despesa se tratar de emissão de bilhete aéreo.

txtTrecho

Trecho

O conteúdo deste dado representa o trecho da viagem, quando o documento que deu causa à despesa se tratar de emissão de bilhete aéreo.

numLote

Número do Lote

No contexto da Cota CEAP, o Número do Lote representa uma capa de lote que agrupa os documentos que serão entregues à Câmara para serem ressarcidos. Este dado, juntamente com o Número do Ressarcimento, auxilia a localização do documento no Arquivo da Casa.

numRessarcimento

Número do Ressarcimento

No contexto da Cota CEAP, o Número do Ressarcimento indica o ressarcimento do qual o documento fez parte por ocasião do processamento do seu reembolso. Este dado, juntamente com o Número do Ressarcimento, auxilia a localização do documento no Arquivo da Casa.
