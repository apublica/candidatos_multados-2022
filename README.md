# candidatos2022
Repositório para as matérias com os Dados Eleitorais do Tribunal Superior Eleitoral

## 1. Cruzamento: dados de multas ambientais aplicadas pelo IBAMA x Candidatos cadastrados em 2022
### 1.1. Exportando os dados
* Os dados de candidatos cadastrados em 2022 foram baixados âs 10 horas do dia 16 de agosto de 2022. A última atualização do repositório do TSE foi às 6h.
* Dados de multas do Ibama foram exportados do [portal de dados abertos]() do órgão por meio [deste script](), no dia 16 de agosto. A última atualização destes dados foi realizada às 19h do dia anterior.

### 1.2. Limpando os dados
#### Multas
* Critérios de inclusão para o cruzamento: Multas aplicadas a partir de 01/01/1994 até 15/08/2022;
* Critérios de exclusão: multas sem CPF/CNPJ; multas com os status débito "excluído", "cancelado" ou "substituído por outro AI" (veja a [lista completa]()); registros duplicados.

#### Candidaturas

### 1.3. Cruzamento
