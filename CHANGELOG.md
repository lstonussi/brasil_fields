## [0.6.0] - Novo método em UtilBrasilFields.
- Criação do método `obterTelefone()` na classe `UtilBrasilFields`;
- Parâmetro `ponto` em `UtilBrasilFields.obterCep()`.

## [0.5.1] - Nova documentação.

## [0.5.0] - Novo aplicativo de exemplo.
- Inclui `KmInputFormatter`()`;
- Criação dos métodos `obterCpf()`, `obterCnpj()` e `obterCep()` na classe `UtilBrasilFields`;
- Parâmetro `ponto` no `CepInputFormatter()`. 

## [0.4.0] - Inclui package intl

- Novos métodos para obter as datas em formato `String` à partir de um objeto `DateTime`:
  - `UtilData.obterDataDDMMAAAA`
  - `UtilData.obterDataMMAAAA`
  - `UtilData.obterDataDDMM`
  - `UtilData.obterHoraHHMMSS`
  - `UtilData.obterHoraHHMM`

## [0.3.2] - Corrige TextSelection.collapsed

## [0.3.1] - Ajustes para versão 1.20

- Troca `WhitelistingTextInputFormatter.digitsOnly` por `FilteringTextInputFormatter.digitsOnly`

## [0.3.0] - Novos formatters

- CpfOuCnpjFormatter

## [0.2.0] - Novos formatters

- PesoInputFormatter
- AlturaInputFormatter

## [0.1.0] - Adiciona análise estática

- Adiciona análise estática com o package `pedantic`.
- Renomeia CartaoCreditoInputFormatter para CartaoBancarioInputFormatter.

## [0.0.9] - Novos formatters

- CartaoCreditoInputFormatter
- ValidadeCartaoInputFormatter

## [0.0.8+1] - Corrige caminho screenshots

## [0.0.8] - Adiciona HoraInputFormatter

## [0.0.7+2] - Corrige formato data UTC

## [0.0.7+1] - Corrige export data_util

## [0.0.7] - Nova documentação da API

## [0.0.6] - Inclui classe UtilData

## [0.0.5] - Atualiza README

- Melhora descrição e exemplos do arquivo.

## [0.0.4] - Melhora documentação no projeto de exemplo

## [0.0.3] - Inclusão de modelos para

- Estados;
- Meses;
- Regioes;
- Dias da Semana;

## [0.0.2] - Inclusão DataFormatter

- Novo formatter para campos do tipo data (01/01/1900) .

## [0.0.1] - Versão inicial

- Formatters para: CEP, CNPJ, CPF, real (moeda), telefone fixo e celular.
- Modelos com listas e mapas: estados, meses, regioes, semana (dias úteis e nã úteis).
