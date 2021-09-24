# Dados_DFP_CVM

Código criado para puxar dados da CVM, e realizar análises financeiras de empresas listadas na Bolsa. Esse código puxa as DFP´s (Demonstrações Financeiras Padronizadas), 
que são aquelas emitidas pelas empresas todo final de ano, contento dados acumulados(no caso de DRE por exemplo) de 01 de janeiro até 31 de dezembro.

Existem 7 tipos de DFP, você deve escolher quais vai utilizar na sua análise. São elas: BPA (Balanço Patrimonial Ativo), BPP (Blanaço Patrimonial Passivo), DFC (Demonstrativo Fluxo
de Caixa), DRA (Demonstrativo Resultado Abrangente), DRE (Demonstração do Resultado no Exercício) e DVA (Demonstração do Valor Adicionado).

A função download pedirá os anos inicial e final de sua análise, e quais planilhas você deseja. 
  obs: caso você queira análisar as planilhas de BPA e BPP: você escreve BPA e pressiona enter, depois escreve BPP e pressiona enter novamente, como você não deseja mais planilhas
  basta pressionar espaço e depois enter, significando que seu terceiro item é vazio.

