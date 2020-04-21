//==================================================== Projeto leitor QRCode:

//======================= IDEIAS PARA CONTINUAR:

Identificação do entregador para liberar requisição pra API:

	-> Opções:
	
		-> Login;
		
		-> Ao gerar QRCode, buscar o acesso e inserir a informação de alguma forma no QRCode, para ser usado na aplicação web pós leitura -> Não exige login;
		


Carregamento do roteiro pós leitura do QRCode:

	-> Opções: 
	
		-> Com react: é possível usar o FlatList e deixar a tela mais dinâmica;
	
		-> Sem react:
		
			-> Criar uma tabela de entregas e, mediante o clique, exibir informações daquela entregador;
			
			-> Buscar uma forma de criar algo semelhante ao flatlist. Links úteis:
			
				https://www.w3schools.com/howto/howto_js_list_grid_view.asp
				
				https://stackoverflow.com/questions/31604901/listview-in-html-javascript
				
				https://stackoverflow.com/questions/36500731/how-to-bind-an-object-list-with-thymeleaf


Confirmação da entrega ou não-entrega:

	-> O código html deve estar encapsulado num form de action POST, que mediante ao click no botão de entregue ou não entregue, dispara uma requisição que atualiza a informação do item da expedicao de entregue ou não;
	
		-> Melhoria: Avisar o Patrick em cada confirmação
		
			-> Por enquanto, ele deverá realizar uma nova consulta, que trará a informação se foi ou não entregue, bem como horário do registro.
			
			

//======================= PROBLEMAS:

Fazer a leitura do QRCode no browser pelo celular:

	-> Ainda não encontrei alguma forma de fazer a leitura, pois, basicamente, o código implementado não consegue reconhecer a câmera do celular. Na maioria dos comentários que li, dizem que não é possível por conta da política de uso de câmera. Encontrei um dizendo que, se for https:// aparece o pedido de permissão de uso da câmera, mas não consegui testar, pois localhost apenas roda como http. Procurando ainda uma forma de fazer funcionar;
	
	-> Possível solução: fazer direto mobile.



#**Codigo fonte disponivel no [google source](https://source.cloud.google.com/erpj-ws/entregaqrcode-web-app)**