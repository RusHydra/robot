# Требования к системе

## Производительность
**`NFPER1`** Система должна поддерживать 100 одновременных сессий.<br>
**`NFPER2`** Система должна обеспечить обработку 5000 заказов в сутки.<br>

## Безопасность

**`NFSEC1`** Система должна предусматривать аутентификацию пользователей в системе по логину и паролю.<br>
**`NFSEC2`** Система должна предусматривать аутентификацию посетителей в системе по номеру телефона и паролю.<br>
**`NFSEC3`** Система не должна хранить в себе персональных данных пользователей.<br>

## Масштабируемость

**`NFEXT1`** Система должна обеспечить возможность увеличения количества одновременно работающих с системой пользователей в 100 раз, без снижения производительности, за счёт увеличения доступных вычислительных ресурсов.<br>

## Доступность
**`NFAVL1`** Система должна быть доступна пользователю в режиме 24/7.<br>
**`NFAVL2`** Допустимое время простоя системы не более 10 минут в сутки.<br>

## Совместимость

**`NFCOM1`** Система должна размещаться и работать на базе облачной инфраструктуры.<br>
**`NFCOM2`** Мобильное приложение должно поддерживать работу в операционных системах iOS и Android<br>
**`NFCOM3`** Мобильное приложение должно быть нативным<br>
**`NFCOM4`** Десктопный клиент должен работать в среде Windows<br>
**`NFCOM5`** Система должна обеспечивать поддержку интеграции с терминалом приёма карт на стойке заказов<br>
**`NFCOM6`** Система должна обеспечивать поддержку интеграции с терминалом приёма наличных на стойке заказов<br>
**`NFCOM7`** Система должна обеспечить возможность интеграции с платёжными системами для приёма безналичных платежей<br>

## Поддерживаемость

**`NFSUP1`** В системе должны журналироваться все события, связанные с запросами статусов оплаты у внешних систем.<br>
**`NFSUP2`** В системе должны журналироваться все события, связанные с операциями в системе лояльности.<br>

## Удобство использования
**`NFUSE1`** Система должна иметь графический интерфейс администратора, позволяющий настраивать параметры системы.<br>

## Локализация
**`NFLOC1`** Система должна поддерживать русский язык и иметь интерфейс пользователя на русском языке<br>

## Функциональные требования к системе

### Use Case диаграмма функций системы для зала ресторана

![PlantUML model](https://www.plantuml.com/plantuml/png/ZLJTQZj55B_VfpZaolz5IrjhFqIau2E8rs6w6TEGpMww7sWGeHgfO4iB8WWYBU8BD6rZOj8ahp3xHlxEsUni9ccBXCtkd3c_t_a-9qcguZJh15wWlqufZIXkDSzIQhHYxQUjAFIITYligbXrgAlyjchgBzDUe8clLTWCjAVyD8gfPkxDFF_13FCVpHZFq4ppwngfXFmWjJf_GZx3ysp-WUO5uV10vecHWbda5sQCtukS7yrG63hDsFEoHFigqPISHT_KKnL48L_LllfYQtUNp3s0eCr_oMy1WmFvDO7XmKpDtCng5fsgjgv7SKF75hr7vdSe3i3m83Wpmd62PrJX_2XCBE9ZCdymBPpiSvXiAB-4rTkQvzd48Do_82i2U-4u7q4jBWs9tPMhEPlbDDJeEslDTP3CNVuJAu9b_AQ7GTHJGOdP4mD8hDZ7zz8_zW55ghmQUiGfGjOGXvaj2p6kQ3iwp4fMn7q7qpCnFY-z0U8MfCHioCbDXLMDHlrK9MsTbWpxP7u3SW26iafc0S48Xqkkl2Hf8i521hh-MktINbUNR9-G-Rj8Gr4v9yD0Jvbl9fdFhuhWAhQkwfKy1qN_p04PSTCLEI085k1Wwhw3guTLfW-Har8DbjWSsyr_XkzNd28NUPg5cMsa8qA7BBWQfVy3GK_pAnVbgxXHWevTWnn_Vi6DPFwjGEvyx10F9sZxS6jzDZoftKpgYP7aTzLVU5UafvX_oxd_IbVEmIee-ImgEydxU4_My-1meOw_YcsKks1wbbQwDa-hE7tkmWusO3ER4BTcg9SBFTo0kdKRhbYDuwYQnQFDLF8ymL4XWClCU4FSkpOzCdohW-6VjUjHbbhMumtMLmcyef4VeOe4iSh8JjtQ7Bcs48FT33l_szQSGnj0T-Zi36vEZtYjqzOMVSGBuiFAMNRNgg1QsAjIBaTvnf7tAn-B3qXuvnF_Grjgm4TMa3ttWRO_BqtHfwI_JNNOy6ZL65HOHvQ6LMo5Vf0rj51P_6VRHHGEKtaf9DKYSqaS9RkUtj51wxkt8e47S66vM5mlt6lU0-_TotPn5Iohs9VCk1vKnE-h2FVREhPOjhJspEXI9fV2KibTeafSn5NExdfOZf8-tzJnQ3cxeh4S0qV3lUQ9T0c-zqxmbNM2_m00)

### Описания Use Case для зала ресторана, реализуемых в рамках MVP

Сценарии зала ресторана

### Use Case диаграмма функций системы на производстве

![PlantUML model](https://www.plantuml.com/plantuml/png/bLJVIXjV4BxVfnXofHU6ty_exqyfHUWZb5xBiZcDYybcsJzGAGMDMbiKXLxregMqVO4OZOR4nbSuvutwpV5qt2CcLaZOtJapt_VDd9bPouimAyfEEsYhLmKLNShYraP1pJXJKH5tao3VZ9CqpC8EfM6q6RRKYsAhhOYFmwJLLa4O5TsCQlgp7kgV-9_h2pqqswIlzPHqt-oO7JqrswQdH_gAVKpFxDOepAdJoZ89_uwWVG2Cz9Zmw2FUREiflY_r0Czp0FNmDhIXXOesWg3CLHJcYi9cSprEMdnGU_byQVa_qbyH0W5wmf1WF2BWz6628BevCRjc3wPJq80K1prO1xKWaDmWwnkYcNW8xVs7XBtn5ANTN1JzJVeZLyVwZe33L11mVAFb4YplyCVdW5oLZck2LgP0o-982TuowK-8WgVa1m1yeBIU29HNWXftH8pWliTtmxavVeWv9LHbRBzFpBuFbwSg4hoLX_42018Qu1fUC01uOexWTcZsRHrjlqn0Ui7YxsECkfrK65T9Vm4q-EmLk8iTu_KA51DWZ446U3sS0U-3Sni9-3_tWPkUwykfnJc3-O0p1X7V7lSDzxPNzZHjRmdgl-X5xZ3lhlH8Bi_f2lZc0JjXoGnjFd3FeNnGC0R58RSd3Fm0tXata3KWGw3SqcEYYp8N_l_1xxhzGDXdNXJG-vmDb0p9bk6K5J3PBKEqiRckikmtHUElHr3m12794Nlg4QVt7YyWqMEV82axGe3f-Q4lEPJ16GE9yvAfIkpVnZTLsfNWvSUeus4_O6JU5E2n6cLnS1dcBWy_XIBkA97Hk9F3m7RdbRtvytkfpKcLkkzZHzqoAGHyHS1b8boHXsuxJGC8bvqeRUU1LdTeOzM7jElxUdRoa1UGtUYqj4GBRlyjLcsonJohMrA-pMqQt-YMWMzqGyn6VeeHgLHiRYXWm4_4KRt-p4th4ugJg5qs5P-Bq5aU8dhUEISmru6JcUl0ucSvuES6_MczJWjk91VXeruNAcdwvpmGrIFnbsYUDo-QG_xq5CMUSIgjEkUSnwHo_3POmwFij7y1)

### Описания Use Case для производства ресторана, реализуемых в рамках MVP

Сценарии производства ресторана

## Карта пользовательских историй User Story Map

![Userstory](images/Userstorymap_1.jpg)

![Userstory](images/US_Клиент.jpg)

![Userstory](images/US_Менеджер_по_ассартименту.jpg)

![Userstory](images/US_Менеджер_по_гостеприимству_и_технолог.jpg)

**Defenition of Ready** 

- US имеет ясное и краткое описание
- DоD определены и утверждены командой
- Все необходимые ресурсы, технические спецификации и прототипы доступны
- Все зависимости от других US зафиксированы
- US приоритезирована и оценена командой
- Команда договорилась об Acceptance Criteria

**Defenition of Done** 

- Реализация US соответствует Acceptance Criteria
- Код, связанный с историей выложен в систему контроля версий
- Историю принял аналитик
- Тестовые сценарии успешно пройдены
- Изменения отражены в документации

## Карта пользовательских историй в Miro
<a id="raw-url" href="https://otus.ru/redirect/?to=https%3A%2F%2Fmiro.com%2Fapp%2Fboard%2FuXjVNomrtxc%3D%2F%3Fshare_link_id%3D601247181371">Ссылка на полную UserStoryMap в Miro</a>
