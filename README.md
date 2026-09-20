<a name="topo"></a>

<div align="center">

  <h1>🏗️ ORÇAGAV</h1>

  <p><strong>Orçamentação de obras com Excel, VBA e Power Query.</strong></p>
  <p>Estruture serviços, organize insumos e consolide os custos da obra.</p>

  <p>
    <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge" alt="Microsoft Excel">
    <img src="https://img.shields.io/badge/VBA-154D79?style=for-the-badge" alt="Automações em VBA">
    <img src="https://img.shields.io/badge/Power%20Query-F2C811?style=for-the-badge" alt="Consultas com Power Query">
    <img src="https://img.shields.io/badge/Formato-XLSM-555555?style=for-the-badge" alt="Arquivo XLSM">
    <img src="https://img.shields.io/badge/Vers%C3%A3o-3.5-217346?style=for-the-badge" alt="Versão 3.5 registrada na aba LOG">
  </p>

  <p>
    <a href="#sobre">Sobre</a> ·
    <a href="#funcionalidades">Funcionalidades</a> ·
    <a href="#precos">Preços e insumos</a> ·
    <a href="#estrutura">Estrutura</a> ·
    <a href="#uso">Como utilizar</a> ·
    <a href="#tecnologias">Tecnologias</a>
  </p>

</div>

<a name="sobre"></a>

📌 Sobre o projeto

O ORÇAGAV é uma planilha de orçamentação de obras que reune estrutura orçamentária, composições de serviços, insumos, quantitativos e preços em um único ambiente de trabalho.

Desenvolvida em Microsoft Excel, combina fórmulas, tabelas estruturadas, automações em VBA e consultas via Power Query para apoiar a rotina de engenharia de custos. Botões e formulários auxiliam na montagem do orçamento, na atualização das informações e na consulta dos resultados.

Seu objetivo é padronizar a elaboração dos orçamentos e automatizar tarefas recorrentes, mantendo a relação entre os serviços previstos e os recursos necessários à execução da obra.

<a name="funcionalidades"></a>

⚙️ Funcionalidades

Recurso

Aplicação na rotina

Orçamento hierárquico

Organização por níveis, itens e subitens, com códigos, descrições, unidades e quantidades.

Composições de serviços

Inserção de composições por formulário e consulta dos insumos e coeficientes associados.

Insumos do orçamento

Atualização da relação de insumos a partir das composições inseridas na planilha orçamentária.

Atualização de preços

Rotinas de consulta a orçamentos aprovados e ao feedback de compras, conforme a obra e as bases disponíveis.

Custos e participação

Cálculo de valores unitários, totais e peso percentual dos itens no orçamento.

Visões sintética e analítica

Alternância entre níveis de detalhamento para consulta e revisão dos custos.

Modelo para importação

Aba dedicada à organização de itens, códigos, quantidades e demais campos do modelo de importação.

Navegação e configurações

Menu de acesso às áreas da planilha e comandos para atualização das bases de composições e insumos.

Ajuda contextual

Botões de ajuda vinculados às seções de um manual externo em Word.

Histórico de versões

Registro das alterações, datas e abas afetadas na aba LOG.

<a name="precos"></a>

💰 Preços e insumos

A aba INSUMOS reúne diferentes referências de preço para apoiar a definição do valor utilizado no orçamento:

Fonte

Informação registrada

Cotação

Valor obtido por cotação do insumo.

Feedback de compras

Referência de compras associada à obra selecionada.

Orçamento aprovado

Preço de referência de um orçamento já aprovado.

SINAPI

Campo para preço de referência da base SINAPI.

Internet

Campo para valor obtido em pesquisa na internet.

Consideração

Campo para um valor considerado no orçamento.

A rotina de atualização permite selecionar a obra e o critério de preço do feedback de compras: médio, maior, menor ou última compra, conforme registrado no histórico da planilha.

A estrutura também inclui campos para documentação e classificação de frete, com opções CIF, FOB e N/A.

A atualização automática depende das fontes configuradas e do acesso às bases utilizadas. A existência de um campo de preço não significa que sua consulta seja automática.

<a name="estrutura"></a>

🗂️ Estrutura da planilha

Aba

Finalidade

MENU

Navegação entre os principais módulos.

MENU - CONFIGURAÇÕES

Comandos de atualização das bases e reinicialização da planilha.

PLANILHA ORCAMENTARIA

Montagem do orçamento, quantitativos, custos e participação percentual.

ESTRUTURA

Organização dos elementos e níveis que compõem a estrutura da obra.

ORÇAMENTO MOD. IMPORTAÇÃO

Organização dos dados no modelo destinado à importação.

COMP - INS - PRECO

Relação entre composições, insumos, coeficientes e preços.

INSUMOS

Referências de preço, valor utilizado, documentação e informações de frete.

OBRAS E FRETE

Cadastros de apoio para seleção de obras e classificação do frete.

LOG

Histórico de evolução e identificação das versões.

<details>
<summary><strong>Consultar as abas auxiliares</strong></summary>

<br>

As abas abaixo estão ocultas na versão de referência e dão suporte às consultas, aos cálculos e às análises.

Aba

Finalidade

CURVA COMPOSICOES

Análise ABC das composições, com custo, participação e percentual acumulado.

CURVA INSUMOS

Análise ABC dos insumos, com custo, participação e percentual acumulado.

DE - PARA - MEGA

Correspondência entre códigos de insumos e referências do feedback de compras.

COMP - INS - CURVA

Dados auxiliares para a composição da curva de insumos.

COMP - INS - CONSULTA

Base de consulta das relações entre composições e insumos.

COMPOSICOES Z

Cadastro de composições utilizado nas consultas da planilha.

As abas de curva ABC contêm orientações para ajuste das fórmulas após a atualização. Confira essas orientações ao utilizar as análises.

</details>

<a name="uso"></a>

🚀 Como utilizar

Preparação

Utilize o Excel para desktop, com suporte a VBA, Power Query e funções utilizadas na planilha, como PROCX.

Habilite as macros do arquivo para utilizar os botões e formulários.

Configure o acesso às fontes externas necessárias às rotinas de atualização.

Para a ajuda contextual, disponibilize o manual em Word no local esperado pela rotina.

Mantenha o arquivo no formato .xlsm para preservar as automações.

Fluxo de trabalho

Abra o ORÇAGAV e acesse o MENU. Utilize os atalhos para navegar entre os módulos.

Atualize as bases necessárias. Em MENU - CONFIGURAÇÕES, utilize a atualização das abas de composições e insumos com as fontes externas disponíveis.

Organize a estrutura do orçamento. Defina os níveis e elementos da obra e utilize os comandos de inserção de itens, subitens e composições.

Preencha os quantitativos. Confira códigos, descrições, unidades e quantidades na PLANILHA ORCAMENTARIA.

Atualize os insumos e as referências de preço. Na aba INSUMOS, utilize os comandos correspondentes e selecione a obra e o critério de consulta quando solicitado.

Atualize os custos das composições. Revise os coeficientes e utilize a atualização de preço unitário em COMP - INS - PRECO.

Calcule e revise o orçamento. Confira os totais e os pesos percentuais, alternando entre as visões sintética e analítica.

Prepare o modelo de importação, quando necessário. Utilize a aba específica e confira os campos exigidos pelo destino dos dados.

<a name="tecnologias"></a>

🛠️ Tecnologias

Tecnologia

Papel no projeto

Microsoft Excel

Interface de trabalho, estrutura dos dados e apresentação do orçamento.

VBA

Automações, formulários, navegação e rotinas acionadas por botões.

Power Query

Consultas às bases de composições e insumos configuradas no arquivo.

Fórmulas e tabelas estruturadas

Relações entre dados, consultas de valores e cálculos de apoio.

<div align="center">
  <p><strong>ORÇAGAV</strong><br>Organização e automação aplicadas à orçamentação de obras.</p>
  <p><a href="#topo">Voltar ao topo ↑</a></p>
</div>
