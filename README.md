# Desafio-Dio---Organizador-de-Imposto-de-Renda
O Descomplica IR é uma planilha desenvolvida no Microsoft Excel para reunir e organizar informações utilizadas na preparação da Declaração de Imposto de Renda. O projeto foi elaborado como parte do desafio “Criando Um Organizador de Declaração de Imposto de Renda”, da plataforma DIO.
A proposta é oferecer uma interface simples e centralizada, com menu lateral vertical, campos de preenchimento, validações e fórmulas que auxiliam a consulta e o acompanhamento dos registros.
Importante: esta ferramenta organiza informações e comprovantes. Não substitui o programa oficial da Receita Federal, a análise da documentação nem a verificação das regras tributárias vigentes.

Estrutura da planilha
O arquivo possui quatro abas:
Aba	Finalidade
MENU	Página inicial com atalhos para as demais abas e visão geral dos registros.
TITULAR	Cadastro do contribuinte: identificação, contato, endereço e observações.
INFORMES	Registro de fontes/instituições, tipos de informe, ano-calendário, valores e situação de recebimento.
NOTAS	Organização de lançamentos, datas, categorias, natureza de entrada ou saída, valores e conferência.


Funcionalidades implementadas
- Navegação vertical: menu lateral disponível nas quatro abas, com links internos criados por meio da função HYPERLINK.
- Painel de acompanhamento: a aba MENU mostra indicadores de preenchimento e totais calculados a partir das outras abas.
- Cálculos automáticos: uso de SUM para totalizar valores e COUNTIF para contar registros, além de IF para apresentar o estado do cadastro do titular.
- Validação de dados: listas suspensas em campos das abas INFORMES e NOTAS para padronizar escolhas.
- Formatação: títulos destacados, cores de fundo, bordas, alinhamentos, mesclagem de células e formatos apropriados para datas e valores monetários.
- Link de e-mail: campo de contato do titular com hiperlink do tipo mailto:.
As funções podem aparecer com nomes traduzidos na interface do Excel, conforme o idioma da instalação.
Como utilizar
1. Abra o arquivo .xlsx no Microsoft Excel.
2. Na aba MENU, utilize os atalhos verticais para navegar entre as seções.
3. Em TITULAR, preencha ou revise os dados cadastrais.
4. Em INFORMES, registre as informações dos documentos fornecidos pelas instituições e fontes pagadoras, utilizando as listas suspensas quando disponíveis.
5. Em NOTAS, cadastre os lançamentos e acompanhe a conferência dos comprovantes.
6. Volte ao MENU para visualizar os indicadores e totais apresentados pela planilha.
Alguns indicadores dependem de colunas específicas e do preenchimento correto dos campos. Confira os valores e a documentação antes de utilizá-los na declaração.

Conceitos de Excel aplicados
O desenvolvimento permitiu praticar a criação de interfaces em planilhas, o uso de fórmulas para automatizar operações, a validação de dados para reduzir inconsistências, a formatação de células para melhorar a legibilidade e a utilização de hiperlinks para facilitar a navegação.
Recurso	Exemplo de aplicação
HYPERLINK	Atalhos para MENU, TITULAR, INFORMES e NOTAS.
IF	Estado do cadastro do titular no painel.
COUNTIF	Contagem de registros no painel.
SUM	Totalização dos valores dos informes e lançamentos.
Validação de dados	Opções selecionáveis para classificação e acompanhamento.
Formatação de células	Destaque visual de seções, datas e valores em reais.


Tecnologias e ferramentas
- Microsoft Excel (.xlsx)
- Fórmulas, validação de dados, hiperlinks e formatação de planilhas
- GitHub para documentação e compartilhamento do projeto
Objetivos de aprendizagem
O desafio proporciona a aplicação prática dos recursos do Excel em uma ferramenta funcional, a organização de informações de forma acessível e a documentação de uma solução para compor o portfólio de projetos no GitHub.
Publicação e privacidade
Antes de publicar: remova ou substitua por dados fictícios quaisquer nomes, CPFs, datas de nascimento, telefones, e-mails, endereços e informações financeiras reais existentes no arquivo. Verifique também hyperlinks, comentários e metadados do documento.
Referência
Desafio da Digital Innovation One (DIO) — Criando Um Organizador de Declaração de Imposto de Renda.
