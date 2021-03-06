# Какие правила ROYALEX использует для рекомендации комиссии за транзакции с Ethereum?

Настройка рекомендации комиссии для транзакций Ethereum в ROYALEX предусматривает два варианта: Рекомендуемая (для обработки в течение 0-20 минут) и Пользовательская, где пользователь устанавливает желаемую сумму комиссии вручную.

Общим правилом здесь является выбор более высокой комиссии (выше рекомендуемой) для транзакций, в которых присутствует степень срочности или сумма транзакции достаточно высокая.

Например, транзакции по обмену одной криптовалюты на другую с помощью смарт-контракта часто подразумевают временной период, в течение которого должна произойти данная сделка. В таких случаях сделка должна быть подтверждена (включена в блокчейн Ethereum), не оставаясь слишком долго в состоянии ожидания, иначе сделка не состоится.

ROYALEX получает "рекомендуемую" плату за транзакцию из блокчейна Ethereum, используя один из его собственных способов оценки платы за транзакцию с учетом нагрузки на сеть.

Чтобы минимизировать вероятность того, что транзакция не пройдет или застрянет при использовании рекомендуемых значений комиссии, ROYALEX рекомендует еще более высокие комиссии по мере увеличения стоимости транзакции.

- для сумм <= 500$ добавьте 5% (сверх рекомендованного сетью значения)
- для сумм <= 1000$ добавьте 10%
- для сумм > 1000 и <= 5000 добавьте 15%
- для сумм > 5000 и <= 10000 добавьте 20%
- для сумм > 10000 добавьте 25%

Советуем выбирать не менее рекомендованного ROYALEX значения комиссии, если требуется срочная операция и сумма транзакции высокая. Рекомендуемые значения увеличат скорость подтверждения транзакции.

