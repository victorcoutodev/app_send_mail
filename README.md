# app_send_mail
web application using the library PHPMailer

Import a biblioteca PHPMailer

No script Processa_envio.php coloque as atribuicoes corretas para e-mail e senha.

 $mail->Username = 'Example@example.com';        // SMTP username
 $mail->Password = '12345';                           // SMTP password
 
 //Recipients
 $mail->setFrom('Example@example.com', 'Example');          // add a sender
 
 É possivel adicionar mais uma camada de seguranca a aplicacao retirando o script Processa_envio do diretorio publico da aplicacao e
 realizando um Require do script em questao, porém, por fins de estudo optei por nao realizar esta parte do processo.
