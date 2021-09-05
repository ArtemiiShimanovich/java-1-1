# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

17/08/2021 - 17/08/2021 было проведено компонентное позитивное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/ArtemiiShimanovich/java-1-1/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг-репорт в issue

В качестве тестовых данных использовались данные https://www.freeformatter.com/:
* VISA: 4024007156275629 Result is OK
* MasterCard: 5351759149010972 Result is OK
* Diners Club - Carte Blanche: 30342093706406 Result is OK
* JCB: 3532611185352189 Result is OK
* American Express (AMEX): 344031191825330 Result is OK
* Diners Club - North America: 5473573613711806 Result is OK
* Discover: 6011443697824353 Result is OK
* Diners Club - International: 36638258469530 Result is OK
* Maestro: 6763245796131857 Result is OK
* Visa Electron: 4913608600377897 Result is OK
* InstaPayment: 6377449788076538 Result is OK

Тестирование производилось в следующем окружении:
* ОС windows 10 версия 2004, 19041.1165 64 бит
* Версия Java 11
* Chrome browser Версия 92.0.4515.159 (Официальная сборка), (64 бит)