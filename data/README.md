# Dados

O arquivo `cancelamentos.csv` contém uma base educacional com 50.000 linhas e 12 colunas. O notebook original deste repositório indicava como origem uma pasta de materiais do projeto educacional **Python Insights**:

https://drive.google.com/drive/folders/1uDesZePdkhiraJmiyeZ-w5tfc8XsNYFZ?usp=drive_link

O endereço não pôde ser consultado automaticamente durante a revisão do projeto. Por isso, este repositório não afirma que os registros representam clientes reais nem atribui uma licença própria ao conjunto de dados.

## Qualidade identificada

- 50.000 linhas no arquivo original.
- 1.469 linhas exatamente duplicadas.
- 4 linhas com pelo menos um valor ausente.
- 48.527 registros permanecem após a limpeza usada na análise.

## Dicionário resumido

| Coluna | Descrição usada na análise |
|---|---|
| `CustomerID` | Identificador do cliente; removido das variáveis analíticas |
| `idade` | Idade do cliente |
| `sexo` | Categoria de sexo disponível na base |
| `tempo_como_cliente` | Tempo de relacionamento com a empresa |
| `frequencia_uso` | Frequência de utilização do serviço |
| `ligacoes_callcenter` | Quantidade de contatos com o call center |
| `dias_atraso` | Dias de atraso no pagamento |
| `assinatura` | Plano de assinatura |
| `duracao_contrato` | Duração do contrato |
| `total_gasto` | Total gasto pelo cliente |
| `meses_ultima_interacao` | Meses desde a última interação |
| `cancelou` | Indicador de cancelamento: 1 para cancelou e 0 para permaneceu |
