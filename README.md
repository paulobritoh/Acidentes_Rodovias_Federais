# Projeto_PySpaprk
Análise de Dados de Acidentes em Rodovias Federais
Contexto do Projeto:
O presente documento descreve um projeto de análise de dados focado no estudo de acidentes em rodovias federais. Este estudo é parte crucial do planejamento estratégico para a expansão das operações na região sudeste, visando aumentar a segurança nas principais rotas de transporte rodoviário identificadas como zonas críticas de acidentes.
Metodologia
Abordagem: Explicação dos dados coletados, fontes e período de análise.
Ferramentas:  Power BI.
Desenvolvimento do Dashboard:
Análise de dados foi incumbida de desenvolver um Dashboard interativo que sintetize as ocorrências dos anos de 2018 a 2020. As funcionalidades esperadas do Dashboard são:
Quantificação de Eventos: Apresentar o total de acidentes, com detalhamento granular por horário, dia da semana e por estado.
Dados de Vítimas: Compilar os dados relativos a óbitos e feridos, fornecendo uma visão clara do impacto humano dos acidentes.
Geolocalização: Implementar uma ferramenta de mapeamento para visualizar a distribuição geográfica dos acidentes.
Análise de Causas: Investigar as sete principais causas de acidentes, fornecendo insights para medidas preventivas.
Análise de Acidentes Graves: Quantificar os acidentes que resultaram em três ou mais óbitos, destacando as zonas de alto risco.
Funcionalidades Adicionais:
O Dashboard será projetado para oferecer filtros dinâmicos por mês, ano e tipo de ocorrência, permitindo uma análise ágil e multifacetada em uma interface única e intuitiva. Ademais, a equipe de analistas é encorajada a sugerir e incorporar novas métricas e análises que agreguem valor ao estudo.

Documentação Complementar:
O projeto inclui um anexo com um dicionário de dados, que serve como referência para os termos e variáveis utilizados nas análises. Este recurso é essencial para garantir a consistência e a compreensão dos dados apresentados.
id: Variável com valores numéricos representando o identificador do acidente.
data-hora: Data e horário da ocorrência do evento.
uf: Unidade da Federação (Estado).
br: Identificador da BR (rodovias federais).
km: Identificação do quilômetro onde ocorreu o acidente.
municipio: Nome do município de ocorrência do acidente.
causa_acidente: Identificação da causa principal do acidente.
tipo_acidente: Identificação do tipo de acidente.
classificacao_acidente: Classificação quanto à gravidade do acidente.
fase_dia: Fase do dia no momento do Acidente.
sentido_via: Sentido da via considerando o ponto de colisão.
condicao_meteorologica: Condição meteorológica no momento do acidente.
tipo_pista: Tipo da pista considerando a quantidade de faixas.
tracado_via: Descrição do traçado da via.
pessoas: Total de pessoas envolvidas na ocorrência.
mortos: Total de pessoas mortas envolvidas na ocorrência.
feridos_leves: Total de pessoas com ferimentos leves envolvidas na ocorrência.
feridos_graves: Total de pessoas com ferimentos graves envolvidas na ocorrência.
ilesos: Total de pessoas ilesas envolvidas na ocorrência.
ignorados: Total de pessoas envolvidas na ocorrência e que não se soube o estado físico.
feridos: Somatório do total de feridos leves com os graves.
veiculos: Total de veículos envolvidos na ocorrência.
latitude: Latitude do local do acidente em formato geodésico decimal.
longitude: Longitude do local do acidente em formato geodésico decimal.
Link :https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-acidentes
Análise de Dados de Acidentes em Rodovias Federais
Dados publico.

Considerações Finais:
A iniciativa sublinha o compromisso com a aplicação de análises de dados avançadas para melhorar a segurança no transporte rodoviário e suportar a expansão estratégica de forma informada.

Métodos Utilizados:
Linguagem DAX:
Função: DAX é usada para criar fórmulas que calculam colunas calculadas, medidas e tabelas em modelos de dados.
Características: Suporta funções, operadores e valores para trabalhar com dados relacionais e desempenha cálculos de agregação, lógica, manipulação de texto e data/hora.

Calendário no Power BI:
No Power BI, um calendário é geralmente uma tabela de datas que serve para analisar dados ao longo do tempo e realizar comparações temporais.

Relacionamentos no Power BI:
Relacionamentos no Power BI são conexões definidas entre tabelas de dados que permitem integrar e analisar dados de várias fontes em um único relatório.

Medidas no Power BI:

Definição: Medidas são cálculos usados em relatórios e painéis que são recalculados em tempo real conforme os usuários interagem com os relatórios.
Cálculos Dinâmicos: As medidas são dinâmicas e podem ser usadas para calcular somas, médias, mínimos, máximos e outros agregados comuns.
Contexto: Dependem do contexto no qual são usadas; isto é, os valores das medidas mudam com base na seleção atual no relatório.
Templates no Power BI:

Propósito: Templates são arquivos predefinidos que servem como ponto de partida para novos relatórios. Eles podem incluir conexões de dados, modelos, visualizações e até mesmo medidas e cálculos DAX pré-construídos.
Benefícios: Ajudam a manter a consistência nos relatórios e permitem que os usuários criem novos relatórios rapidamente sem começar do zero.
Personalização: Podem ser personalizados para atender às necessidades específicas de negócios e, depois, compartilhados com outros usuários para promover padrões e eficiência.
O template atualizado no projeto é de uso privado da Empresa EmpowerLogistics.
Explicação do Dashboard:
Acidentes com Vítimas Fatais

Dados Principais: Apresentação dos números totais de eventos e vítimas fatais.
Análise Estadual: Destaque para MG como o estado com maior número de acidentes fatais.
Pico Horário: Discussão sobre a concentração de acidentes no final da tarde.
Causas: Enfatizar a falta de atenção como principal causa de acidentes fatais.

Acidentes com Vítimas Feridas

Dados Principais: Números de eventos e vítimas feridas.
Distribuição Horária: Indicação dos períodos críticos ao longo do dia.
Causas: Apontar as principais causas e possíveis medidas preventivas.

Acidentes Sem Vítimas

Dados Principais: Quantidade de acidentes sem vítimas.
Causas e Prevenção: Relação entre defeitos mecânicos e a necessidade de manutenção dos veículos.

Análise Comparativa

Comparação Estadual: Análise comparativa entre os estados e discussão de possíveis fatores contribuintes.
Horários e Dias de Maior Risco: Identificação dos padrões temporais dos acidentes.
Tipos de Pista: Comparação da incidência de acidentes por tipo de pista.

Conclusões e Recomendações

Conclusões: Síntese dos insights obtidos a partir dos dados.
Recomendações: Estratégias focadas em educação, infraestrutura e fiscalização.


