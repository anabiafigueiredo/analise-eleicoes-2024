# **Projeto Final: Uma Análise das Eleições Municipais 2024**

### **Objetivo**
O objetivo deste projeto é realizar uma análise das candidaturas e dos processos eleitorais das eleições municipais de 2024, trazendo informações relevantes e transparentes para a sociedade civil. Ao analisar dados eleitorais, o projeto busca proporcionar maior visibilidade sobre o perfil dos candidatos, as campanhas e os processos relacionados.

### **Fonte dos Dados**
Os dados utilizados para esta análise foram extraídos do [repositório de dados abertos do TSE](https://dadosabertos.tse.jus.br/). A base de dados contém informações cruciais para a análise, e todas as tabelas foram devidamente processadas e organizadas para garantir uma análise eficiente.

### **Coleta de Dados**
A base de dados do TSE é composta por 6 tabelas diferentes que fornecem um panorama completo das eleições municipais de 2024. Abaixo estão as principais tabelas utilizadas neste projeto:

- **Perfil do Eleitorado em 2024**: Informações detalhadas sobre os eleitores, como idade, gênero e localização.
- **Motivo da Cassação**: Registro das cassações de candidatos e seus motivos.
- **Bens dos Candidatos em 2024**: Declaração de patrimônio dos candidatos.
- **Consulta sobre os Candidatos**: Duas tabelas com informações sobre os candidatos que foram unificadas para facilitar a análise.
- **Prestação de Contas dos Candidatos**: Detalhamento das receitas e despesas das campanhas dos candidatos.

### **Arquivos de Dados Utilizados**
Os arquivos de dados utilizados neste projeto foram armazenados no Google Drive devido ao seu tamanho. Abaixo estão os links para download de cada um dos arquivos:

- [Receitas Candidatos](https://drive.google.com/file/d/1ySZAuUPvg5deq8egvtgNy1U883qYY7OC/view?usp=sharing)
- [Motivo Cassação](https://drive.google.com/file/d/1u5T4YUP-C2fZV4guks1zeFqpggfaw6Un/view?usp=sharing)
- [Bens Candidatos](https://drive.google.com/file/d/1sOUh5qLPi9lmFnPR8ArAzI73sq5R6r1x/view?usp=sharing)
- [Consulta Candidato](https://drive.google.com/file/d/1sEEL0xXWt_uTpLIa60xUm22e_BGJPAos/view?usp=sharing)
- [Perfil Eleitorado](https://drive.google.com/file/d/1IVGLHfzkXZqpRcgAWhqf8AxmdiLZJKys/view?usp=sharing)
- [Base Final](https://drive.google.com/file/d/1pVWcBWChkPnrXNYh8YVd0sv0FaPa7OhM/view?usp=sharing)

### **Ferramentas Utilizadas**
Este projeto utilizou as seguintes bibliotecas do Python:

- **Pandas**: Para a coleta, limpeza e análise dos dados, permitindo carregar os dados de diferentes fontes e realizar transformações nos DataFrames.
- **Seaborn**: Para criar visualizações estatísticas, ajudando a ilustrar a distribuição e relações entre os dados.
- **Matplotlib**: Para gerar gráficos personalizados que ilustram os resultados da análise.

### **Como Utilizar o Projeto**
1. Clone este repositório para a sua máquina:
   ```bash
   git clone https://github.com/seu-usuario/analise-eleitoral-limpo.git
   cd analise-eleitoral-limpo
