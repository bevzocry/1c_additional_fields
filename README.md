# 1c_additional_fields
Механизм редактирования дополнительных реквизитов через общую форму без необходимости вносить изменения в типовые формы, что упрощает обновление конфигурации.
Нетиповые реквизиты и табличные части добавляются непосредственно в объекты основной конфигурации с признком "ocg" в комментарии. Это облегчает доступ к нетиповым полям при написании запросов.
Общая команда настроена на отображение в командной панели формы Важное (в типовых решениях эта панель иногда скрывается). Расширение содержит общую форму, общую команду и определяемый тип.
# Настройка расширения
В расширение из основной конфигурации нужно добавить справочники, для которых должна отображаться команда редактирования дополнительных реквизитов.
Данные справочники необходимо указать в определяемом типе, после чего на типовых формах станет доступна команда "Дополнительные реквизиты".
Расширение тестировалось на конфигурации УНФ 1.6
