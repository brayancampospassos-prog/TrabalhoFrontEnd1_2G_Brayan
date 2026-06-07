# FrontEndLaSalle
# Análise e Correção de Dados de planilha

**Conclusões sobre a correção:** A segunda tabela (`Tabela_2G_Brayan_FrontEnd`) é a versão corrigida, com todos os dados corrigidos.

### Resumo das Correções
* planilhas tem uma logica visual de alinhamento de valores, onde dependendo se o conteúdo é textual ou númerico, o alinhamento muda (texto: **Esquerda** | número: **Direita**).
* Corrigimos todas as formatações pra seguir o padrao da coluna (colunas textuais n podem conter números, coluas numericas ao podem conter texto) (claro isso varia da planilha, mas nesse caso usamos essa metadologia).
* Limpamos os erros de sistema e caracteres inválidos.
* Aplicamos o sistema de "aplicar tabela" do proprio google planilhas, ou seja, agora além de um visual melhor, tem muitas outras ferramnetas disponiveis com esse modo ativado.
* Também fizemos uma simples organização, ordenamos os nomes de A até Z (usando uma própria ferramenta de filtragem no modo tabela)

### Tabela de Erros Identificados na base_2g

| Categoria do Erro | Descrição Exata do Problema | Ocorrências |
| :--- | :--- | :--- |
| **valor errada (em numero de Contrato)** | Valores decimais (`0.9`, `1.0`), com letras (`12222x`), ou com pontos (`1.000.000.000`). | **71 ocorrências** |
| **celulas vazias** | muitas celulas do projeto estavam vazias. | **+850 Ocorrências** |
| **Escrita errada, mescla de numeros com texto** | Números inseridos indevidamente dentro da coluna de Nome. (Ex: `ONIO A CARVALHO 3238427070`). | **10 ocorrências** |
| **Dados Incompletos / Nomes estranhos** | nomes imcompletos, ou oque estava escrito não era um nome (Ex: `doCod98`, `ES`). | **4 ocorrências** |
| **Erros** | apenas um erro na coluna de CEP (`#ERROR!`). | **1 ocorrência** |

---
## Links:
Planilha corrigida (revisada e completa):
* ✅ **[Planilha corrigida "Tabela_2G_Brayan_FrontEnd"](https://docs.google.com/spreadsheets/d/1zWUaGsr7g3yu7yE6X3omdbUk3TahvVrW9QK0L1Yufa0/edit?usp=sharing)**

---
Planilha original (totalmente quebrado e incorreto):
* ❌[Planilha original (quebrada) "base_2G"](https://docs.google.com/spreadsheets/u/4/d/1C6xxh9GhMj3l0QUb8Eflz-VX1DcbIqvtHu2OgK3GDBw/edit?usp=sharing)


## Nota:
Esse trabalho não teve **NENHUM** uso de inteligencia artificial, **concluções e ações feitas na planilha foram pensadas pelo grupo**, Eu brayan jhonny fiz um modulo de "Planilhas" em um curso, oque me da certo conhecimento da formatação e logica e visual de uma planilha, além de um pensamento critico e lógico sobre os dados, **Sobre o github** eu também ja usei ele as vezes pra ver alguns projetos públicos. já esse estilo de formatação que voce esta vendo nesse repositorio eu também tenho conhecimento, ele é extremamente semelheate a formatação de texto do discord, ele utiliza "#" "*" pra alterar o visual do texto. para fazer a tabela foi um pouco mais dificil, pesquisei na internet e vi alguns videos de como se faz esse tipo de tabela, foi bem facil de fazer.
---
## Trabalho feito por:
* Brayan Jhonny 2G (Noturno)
* Maria 2G (noturno)
