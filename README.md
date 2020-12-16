Отчёт о тестировании части функционала Credit Card Number Validator

Краткое описание
16.12.20 - 16.12.20 было проведено функциональное тестирование наработок функционала Credit Card Number Validator.

На тестирование затрачено: 30 минут

В результате тестирования дефекты не выявлены.

Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
- Инструкция по установке IntelliJ IDEA https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md

В качестве тестовых данных использовались данные сервиса по генерации валидных номеров для карт:
- https://www.freeformatter.com/credit-card-number-generator-validator.html
А именно: 
VISA:
- 4716519811071048
- 4916792070143554
- 4539783662611181523
MasterCard:
- 5179569382983029
- 2720991908459923
- 5315597200698144
American Express (AMEX):
-347320253550580
-344960861733988
-349741618721921Discover:
-6011758527325424
-6011305729247756
-6011580644503827127JCB:
-3541000395582000
-3543839425173084
-3529767914148656077
Diners Club - North America:
-5525639182287821
-5586803439888445
-5574958499357394
Diners Club - Carte Blanche:
-30126175332334
-30593879481180
-30149833172173
Diners Club - International:
-36143325238265
-36726072339474
-36862177575967
Maestro:
-6763687764102826
-5893593660827893
-5038575878037205
Visa Electron:
-4917112114406165
-4844249350750654
-4913476182866012
InstaPayment:
-6386282435237156
-6399091963759894
-6370304116860128

Тестирование производилось в следующем окружении:

- Windows 10 Корпоративная х64
- openjdk 11.0.9.1 2020-11-04
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
