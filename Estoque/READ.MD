**Estoque**
Projeto para fazer diversas melhorias no estoque, utilizando do coletor e impressoras de etiquetas
Dentre essas melhorias estão
Processo de impressão de etiquetas e guarda pelo coletor
Etiquetas para caixas de transferencia
Trocar o sistema de endereçamento para numeros
Gerar codigos 2D para locações
Fazer o processo de guarda exigir que leia o codigo 2D da locação

**Sendo feito atualmente:**
Logica para ter N estoquistas por tarefa

**O que será feito após: **
Etiquetas para caixa de redistribuição

**Isto está divido entre três projetos**
| Projeto |                          Descrição                         |
|:-------:|:----------------------------------------------------------:|
|   DBF   |                   Parte de gerar a tarefa                  |
|    ws   | Web service que o coletor irá consumir para a parte logica |
| coletor |      Aplicativo principal que irá ter as funções acima     |