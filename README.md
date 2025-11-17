whatsGo

whatsgo é uma biblioteca em Go para a API web multidevices do WhatsApp.


Discussão

Para dúvidas sobre o protocolo do WhatsApp (como enviar um tipo específico de mensagem), você também pode usar a seção Perguntas e Respostas do protocolo WhatsApp nas discussões do GitHub.


Uso

A documentação no godoc inclui detalhes sobre todos os métodos e tipos de eventos.
Também há um exemplo simples no topo da página.


Funcionalidades

A maioria das funcionalidades principais já está presente:

	*Enviar mensagens para chats privados e grupos (tanto texto quanto mídia)

	*Receber todas as mensagens
	
	*Gerenciar grupos e receber eventos de alterações nos grupos
	
	*Entrar via mensagens de convite, usar e criar links de convite
	
	*Enviar e receber notificações de digitação
	
	*Enviar e receber recibos de entrega e leitura
	
	*Ler e escrever o estado do aplicativo (lista de contatos, status de fixar/silenciar chats, etc.)
	
	*Enviar e lidar com recibos de tentativa novamente quando a descriptografia falha
	
	*Enviar mensagens de status (experimental, pode não funcionar em listas de contatos grandes)


Funcionalidades que ainda não estão implementadas:

	*Enviar mensagens para listas de transmissão (também não é suportado no WhatsApp Web)

	*Chamadas
