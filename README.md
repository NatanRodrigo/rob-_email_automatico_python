📧 Automação de Envio de E-mails com Python

🔎 Descrição do Projeto

Este projeto tem como objetivo automatizar o envio de e-mails utilizando Python. A automação pode ser aplicada em diversos cenários, como:


✅ Notificações automáticas (boletins, relatórios, alertas).

✅ Lembretes de compromissos e reuniões.

✅ Confirmação de pedidos e cadastros.

✅ Disparo de e-mails em massa.


A aplicação utiliza SMTP (Simple Mail Transfer Protocol) para enviar mensagens via servidores de e-mail, podendo ser integrada com Gmail, Outlook, Yahoo, entre outros.


⚙️ Tecnologias Utilizadas

Python → Linguagem principal para a automação.

smtplib → Biblioteca padrão do Python para envio de e-mails via SMTP.

email.message → Para formatação de e-mails com HTML e anexos.

dotenv → Para armazenar credenciais de forma segura.

schedule → Para programar envios automáticos em horários específicos (opcional).

🚀 Como Funciona

Configuração do Servidor SMTP

Conectar-se ao servidor de e-mail (exemplo: Gmail: smtp.gmail.com).

Autenticação
Utilização de um e-mail remetente e uma senha de aplicativo (não a senha pessoal).
Criação da Mensagem
Definir destinatário, assunto e corpo do e-mail (pode ser em texto ou HTML).
Envio Automático
A automação pode ser agendada para disparar e-mails periodicamente.
