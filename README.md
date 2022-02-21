# Paswordless-Authentication

## Aplikacja implementująca bezhasłowe uwierzytelnianie w postaci jednorazowych kodów e-mail oraz Captchy.

Aplikacja napisana została w języku Java przy wykorzystaniu bibliotek JavaFX oraz SimpleCaptcha.

Demonstruje działanie mechanizmów uwierzytelniania bezhasłowego - w celu poprawnego zalogowania użytkownik musi podać swój adres e-mail, poprawnie wypełnić Captchę oraz wpisać jednorazowy kod wysłany na jego adres.

Kody są jednorazowe, można je wykorzystać do zalogowania się tylko tym adresem e-mail, na który wysłano kod oraz mają ograniczony termin ważności.

Ze względu na publiczny charakter repozytorium, usunięto z kodu adres e-mail oraz hasło wykorzystywane do wysyłania kodów. W celu przetestowania działania aplikacji, należy w pliku "SendEmail.java" podać dane konta Gmail, z którego kody mają być wysyłane, a w samym koncie umożliwić aplikacjom korzystanie z niego.

## Application implementing paswordless authentication using single-use e-mail codes and Captcha.

Application was written in Java using also JavaFX and SimpleCaptcha libraries.

It's purpose is to demonstrate paswordless authentication - in order to successfully log in, user needs to enter e-mail address, successfully pass Captcha test and enter single-use code that was sent to entered e-mail address.

Codes are single-use only, they can be only used to log in using e-mail address that received them and they have limited time of use.

As the repository is public, the e-mail adress and password used to send single-use codes was erased from code. In order to test the application, it is neccessary to enter Gmail account details in "SendEmail.java" file of the account that will be used to send codes. Additional changes in account settings enabling the use of the account by third-party applications is neccesary.
