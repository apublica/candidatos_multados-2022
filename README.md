## Cruzamento: dados de multas ambientais aplicadas pelo IBAMA x Candidatos cadastrados em 2022
### Exportando os dados
* Os dados de [candidatos cadastrados em 2022](https://dadosabertos.tse.jus.br/dataset/candidatos-2022/resource/435145fd-bc9d-446a-ac9d-273f585a0bb9) foram baixados âs 10 horas do dia 16 de agosto de 2022. A última atualização do repositório do TSE foi às 6h.
* Dados de multas do Ibama foram exportados do [portal de dados abertos](https://dadosabertos.ibama.gov.br/dataset/multas-ambientais-distribuidas-por-bens-tutelados) do órgão no dia 16 de agosto. A última atualização destes dados foi realizada às 19h do dia anterior.

### Limpando os dados
#### Multas
* Critérios de inclusão: Multas aplicadas a partir de 01/01/1994 até 15/08/2022;
* Critérios de exclusão: multas sem CPF/CNPJ; multas com os status débito "excluído", "cancelado" ou "substituído por outro AI" (veja a [lista completa](https://github.com/apublica/candidatos_multados-2022/blob/main/situacao_debito.csv)); registros duplicados.
* A coluna CPF/CNPJ foi duplicada e renomeada como "CPF_limpo", e desta foram retirados os caracteres ".", "-" e "/" para padronização.

#### Candidaturas
* Critérios de inclusão: Todas as candidaturas registradas até a última atualização da base exportada.

### Cruzamento
* A partir das colunas de CPF, fizemos o cruzamento dos dados. 445 multas foram associadas à 254 CPFs de candidatos. A lista completa de [multas](https://github.com/apublica/candidatos_multados-2022/blob/main/multas.csv) e [candidatos](https://github.com/apublica/candidatos_multados-2022/blob/main/candidatos_multados.csv).
