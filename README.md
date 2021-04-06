# Отзыв о курсе «NoSQL» на «Отус»

Здравствуйте. Хочу поделиться своими впечатлениями от прохождения курса ["NoSQL"](https://otus.ru/lessons/nosql-bd) на платформе онлайн-образования "Отус"([otus.ru](https://otus.ru/)). 

## Вместо предисловия

Это не реклама, а именно отзыв. В первоначальный вариант внесены правки, но суть осталась. Надеюсь на конструктивную открытую критику, поскольку не являюсь аффилированным лицом и в действительности выражаю свою точку точку зрения. Соответствующую статью на ["Habr"](https://m.habr.com/ru/post/550898) заблокировали (возможно автоматически) за полученные "минусы" по критериям: "низкий технический уровень материала" (16.67%), "больше рекламы, чем пользы" (66.67%), "не соответствует тематике Хабра" (16.67%). 

```
К сожалению, вынуждены были скрыть вашу статью в черновики, 
поскольку она нарушает правила Хабра и является рекламой 
коммерческого сервиса. Вы можете предложить компании OTUS разместить отзыв в их блоге.

Убедительно просим вас не нарушать правила Хабра в дальнейшем.
```

Хотя при этом на данном ресурсе есть возможность писать подобного рода тексты с меткой "Я пиарюсь" (это только пиара личного, а не организации?).

Нарушать не буду. Но интересно, как участники Хабр-сообщества развиваются? Какими платформами дистанционного обучения пользуются, особенно в текущих ограничительных условиях школьного и высшего образования? Есть ли сравнения Skillfactory, Skillbox, GeekBrains, Otus в соотношении - "ожидание" vs "реальность"? Имеется желание развить себя в DevOps и в информационной безобастности по Web. По моему личному мнению именно Хабр это то место, где это можно обсуждать открыто и объективно, преследуя цели повышения профессионализма всего IT сообщества. Возможно Хабр сам проводит обучение такого плана?

## Почему "NoSQL" на "Отус"

Преследуемой мною целью являлось изучение возможностей взаимодействия с максимальным числом нереляционных баз данных посредством языка программирования Python в проекции на Web-разработку. При этом было необходимо понимание того, какие NoSQL-решения позволяют развернуть себя локально и на какой внутренней инфраструктуре.

Существует ряд печатных пособий по типу "Семь баз данных за семь недель. Введение в современные базы данных и идеологию NoSQL", но ничто и никогда не заменит живого ментора.

Причины выбора курса "NoSQL" именно на "Отус" были как объективными, так и субъективными.

Объективные: в 2020 году иной подобный учебный обзор нереляционных баз данных и их методик в сети Интернет был не найден. Имевшиеся на других ресурсах платные курсы касались конкретных программных решений (отдельно - или "Cassandra", или "MongoDB", или иное), а бесплатные - отталкивали описываемым поверхностным подходом.

Субъективные: ранее в 2018 году я проходил обучение на курсе ["Web-разработчик на Python"](https://otus.ru/lessons/webpython/) от "Отус". Искренне жалею, что своевременно не написал отзыв. Но, если коротко, то заголовок бы был таковым: "Web-Python на Отус - это не только Web и далеко не только Python". Он был сложным для меня, но все домашние задания и курсовая работа были успешно сданы. Этот курс дал хороший вектор, в том числе в последующем саморазвитии.

Естественно рассматриваемый курс "NoSQL" в первую очередь ориентирован на архитекторов баз данных. Но считаю абсолютно верным знать инфраструктурные аспекты и понимать области применения конкретных NoSQL-решений.

## Организация учебного процесса

Обучение на "Отус" проходит в рамках видеовебинаров в программе "Zoom", онлайн-записи которых доступны в личном кабинете учащегося. Занятия проходят 2 раза в неделю (в данном случае в 20:00 - будний день, в 10:00 - суббота). Ссылки на трансляцию публикуются за 15 минут до начала. Стандартно лекция длится около полутора часа. По окончанию обычно задается домашнее задание. Преимущественно оно ориентировано на проверку понимания изложенного материала. Проверка осуществляется самим лектором или основным куратором курса. Общение осуществляется как на самой платформе, так и с пользованием "Slack". Ближе к окончанию курса учащемуся предлагается список тем итоговой проектной работы, на которую отводится около месяца и у которой имеется промежуточная контрольная точка. По собственному опыту и тематикам прошедших защит иных учащихся курсовая работа является логичным продолжением домашних заданий.

Маленькая ремарка: на курсе "Web-Python" проверкой домашних заданий занимались привлекаемые дополнительные специалисты. Данный факт иногда приводил к расхождению в понимании того, что уже было и чего еще не было на курсе, к возможному иному их видению конечной цели самостоятельных заданий, и в итоге выражался в затяжных пересдачах. Однако, одним из моих проверяющих (в переписке значилась как "Анна") в результате самоотверженного подхода к проверке абсолютно всех моих исходных кодов и уже имевшихся у меня навыков целиком и полностью контролировался мой личный профессиональный рост. Это было то, что я ожидал и желал. Мне предлагались расширенные задачи, решение которых и по настоящее время находит отражение в моей практике. За это Анне отдельное СПАСИБО.

## Особенности курса

Не смотря на то, что курс - пилотный, преподавание было методичным и живым. Подобранный состав лекторов позволил в полном объеме раскрыть каждую заявленную тему. Лекции начинались с теоретических основ и заканчивались практикой. Кто-то строго придерживался академического часа, а кто-то заранее предупреждал, что уложиться сложно, и лекция займет большее время. Профессионализм и личный, как говорят, "боевой" опыт в освещаемых вопросах присутствовал абсолютно у всех лекторов. Ни одно из изложений не велось с листа или презентации. Преподавателями рисовались схемы и при необходимости давались дополнительные повторные или углубленные разъяснения.

В рамках обучения основным куратором курса было предложено провести вебинары по любому дополнительному направлению в рамках NoSQL-решений. В результате открытых голосований в "Slack" были назначены дополнительные вебинары, таким же образом решались вопросы переноса ряда лекций.

## Результат

Курс "NoSQL" полностью оправдал мои ожидания как проектировщика и разработчика программного обеспечения.

Одним из результатов, которым бы я хотел поделиться - это проект, описанный на [Habr](https://habr.com/ru/post/550294/). Он будет постепенно рефакториться и развиваться, но текущая версия оставлена на ваш суд как есть.

Полученный опыт на курсе "NoSQL" позволил мне на профессиональном уровне подходить к решению задач в повседневной деятельности. Особо это выражается в ходе демонстрации выявленных ошибок в программных продуктах, поддерживаемых или используемых моими коллегами, и в рамках составления рекомендаций тем, кто их разрабатывает.

## Минусы

Минусы в организации процесса или донесении материала не существенные.

В рамках курса имелся перенос пары лекций. Но обстоятельства были связаны с тем, что лекторы не просто преподаватели-теоретики, а разработчики реальных функционирующих проектов, и предновогодний цейтнот - обычное дело в контрольных сроках сдачи. Эти приоритеты естественны, понятны и оправданы. Кроме того, как не печально, пандемию тоже никто не отменял.

Также на начальном этапе не хватало тестовых данных, на которых было бы возможно обкатать то или иное NoSQL-решение без самостоятельного предусмотрения спектра возможных нюансов их обработки. Однако сами учащиеся в рамках сдачи проектных работ продемонстрировали тестовые наборы, сгенерированные самостоятельно на Python посредством [Faker](https://faker.readthedocs.io/en/master/). Вместе с тем, данный факт можно отнести и к положительной стороне, так как наборы предположительно генерировались для предметных областей, в которых осуществляется трудовая деятельность. И использование именно таких специализированных данных позволяет эффективно оценить постигаемое в сравнении с имеющимся опытом. Вместе с тем, в сети Интернет достаточно разноплановых наборов необработанных сведений, из которых достаточно выбрать наиболее ["интересный"](https://habr.com/ru/post/523182/).

Общий минус, субъективный, при опредленной специфике работы было бы замечательно иметь по окончании сертификат в печатном виде с голограммой "Отус".

## Заключение

Спасибо курсам "Отус" ("Web-Python" 2018 и "NoSQL" 2020) за приобретенный мною опыт Fullstack-разработки.

Команда "Отус", прости, что запоздало, с наступившим днем рождения! 4 года - так держать!

## P.S.

