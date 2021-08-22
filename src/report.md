# Отчёт о тестировании функционала валидации  номера банковской карты.

## Краткое описание

18 августа было проведено функциональное тестирование приложения валидации номера банковской карты.
На тестирование затрачено: 3.25 часов

В результате тестирования выявлены следующие дефекты:
[ Ошибка в приложении при определении валидности номера банковской карты ](https://github.com/UAzif/DZJ-1-1/issues/1)
## Описание процесса тестирования
В качестве тестовых данных использовались данные [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html#howToValidate:)
1. American Express (AMEX)
2. VISA
3. MasterCard
4. Discover
5. JCB
6. Diners Club - North America
7. Diners Club - Carte Blanche
8. Diners Club - International
9. Maestro
10. Visa Electron
11. InstaPayment

Тестирование производилось в следующем окружении:
* Windows 10 Pro, 64-разрядная операционная система, процессор x64
* openjdk version "11.0.12" 2021-07-20
* Google Chrome	92.0.4515.131	
