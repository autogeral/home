<h2>Importação de Arquivos DDA recebidos do itau que serão ligados em contas a pagar</h2>

## Projeto de importação de arquivos concluida, fazendo importarções para as tabelas em DataSouce : autogeral<br>
## Nome das tabelas que recebem os registro  : dda_arquivos_headers, dda_boleto_segmento_g, dda_registro_header_lote, dda_segmento_h. Até o momento o projeto esta "Concluido", faltando realizar as seguintes implementações:<br>
## (WEB)Consulta de arquivos_header por data, listar arquivos recebedios;<br>
## (WEB)Consultar boletos por, CNPJ, codigo boleto, valor .<br>
## Previsão para entrega do projeto até 24/04, pelo fato de não conhecer tanto ferramentas como Thymeleaf, preciso de um prazo um pouco extenso .<br>
<a href = "https://github.com/autogeral/spring-dda-service.git"> Link do servico de Importação/exportação</a><br>
<a href = "https://github.com/autogeral/DDA-ItauHeader.git"> Link do Layout dos Registro </a><br>


<h2>Integração dos arquivos armazenados com Contas a pagar </h2>

## 31/03/2020 configuracao de ambiente do projeto WS. Tive dificuldade de rodar o projeto, pois o mesmo continha dependencia de outro projeto, e como estamos trabalhando Home Office eu não tinha a versão correta do mysql(5.7)<br>
##01/04/2020  Teste de Persistencia com contas a pagar.<br>
##02/04/2020  Inicio a logica proposta pelo Tuvani, a ligacao do boleto com a conta a pagar.<br>
##03/04/2020  Continuação sobre  a logica de negocio.<br>
##04/04/2020 Testes de Integração<br>
## 06/04/2020 Teste de Integração <br>
## 07/04/2020 Teste de Integração <br>
## 08/04/2020 Subir em producao <br>




