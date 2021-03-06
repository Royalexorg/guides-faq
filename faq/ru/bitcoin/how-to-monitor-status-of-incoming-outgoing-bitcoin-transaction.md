# Как контролировать статус входящих/исходящих транзакций Bitcoin?

Кошелек ROYALEX позволяет пользователям отслеживать статус своих транзакций.

- Как только пользователь отправляет транзакцию Bitcoin, она должна появиться со статусом " в ожидании" на вкладке Транзакции, как для отправителя, так и для получателя. Транзакция отображается со статусом " в ожидании" до тех пор, пока она не будет включена в блокчейн.

- Статус транзакции меняется на " отправлена" для отправителя и "получена" для получателя, как только она будет включена в блокчейн. Это событие также означает, что транзакция получила первое подтверждение.

- Приложение кошелька отображает статус "отправка" как для отправителя, так и для получателя до тех пор, пока не пройдет как минимум 3 блока (транзакция имеет 3 подтверждения).

Пока не пройдет 3 блока, ROYALEX не отразит сумму транзакции на балансе получателя и не позволит ему потратить полученные средства в других транзакциях.

Помимо мониторинга статуса транзакций в ROYALEX, пользователи могут использовать для мониторинга один из общедоступных проводников блоков Биткоина (например, [https://btc.com](https://btc.com)).

Для мониторинга статуса ожидающих транзакций на внешних ресурсах пользователям необходим идентификатор транзакции, который можно найти в ROYALEX.