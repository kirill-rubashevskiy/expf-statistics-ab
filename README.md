# Учебные кейсы интенсива EXPF по математической статистике и A/B-тестам

В репозитарии собраны учебные кейсы [интенсива](https://expf.ru/ab_course) EXPF по математической статистике и A/B-тестам, который я прошел в мае – июне 2023 года.

Стек:
- EDA: `Matplotlib`, `pandas`, `seaborn`
- Статистические инструменты: `SciPy`, `statsmodels`

| Кейс                                                                                                                                         | Индустрия                            | Описание                                                                                                                                                                                                                                                          |
|----------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Анализ аудитории сервиса подписки на репетиторов по ЕГЭ](./tutors-service-users-analysis)                                                   | `EdTech`                             | Проанализировал успеваемость аудитории сервиса подписки на репетиторов по ЕГЭ в зависимости от программы обучения и года сдачи ЕГЭ.                                                                                                                               |
| [Проверка гипотез в связи с редизайном кнопки на главной странице сервиса подписки аналитику в соц. сетях](./button-redesign-tests)          | `SaaS`, `Subscription Services`      | Проанализировал результаты эксперимента по редизайну кнопки на главной странице сервиса и проверил две гипотезы: есть ли значимое изменение в большую или меньшую сторону у клика на целевую кнопку, и изменилось ли время, проведенное на сайте в рамках сеанса. | 
| [Анализ промежуточных результатов A/B-теста для сервиса по доставке еды](./food-delivery-ab)                                                 | `Доставка еды`                       | Проанализировал промежуточные результаты A/B-теста для сервиса по доставке еды («спящим» пользователям отправили промокод на скидку 30% на заказ) и рассчитал время, необходимое на проведение эксперимента, исходя из ожидаемого и фактического lift'а.          |                                                                                                                                                                                                                                                   |
| [Множественная проверка гипотез при проведении A/B-теста для приложения для удаления мусора на физическом носителе](./gc-app-multiple-tests) | `Shareware`, `Subscription Services` | Провел множественную проверку гипотез при проведении A/B-теста для приложения для удаления мусора на физическом носителе с использованием корректирующей поправки.                                                                                                |
| [Бутстрап vs t- и u-тесты](./bootstrap-vs-tests)                                                                                             | N/A                                  | Провел статистическую проверку гипотез с использованием бутстрапа и t- и u-тестов и сравнили полученные результаты.                                                                                                                                               |
| [Применение 𝐶𝑈𝑃𝐸𝐷 для снижения дисперсии метрики](./cuped)                                                                                  | N/A                                  | Посчитал $CUPED$ для 6 ковариат с разными статистическими параметрами для снижения дисперсии метрики.                                                                                                                                                             |
