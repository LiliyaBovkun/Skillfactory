# Skillfactory

В описании кратко укажите:

→ основные цели и задачи проекта;

получить базовые навыки самостоятельного проведения разведывательного анализа данных

→ краткую информацию о данных;

В данных достаточно мало пустых значений, заполнять их средними значениями нет смысла
Если удалить из данных все строки, где есть хотя бы одна пустая ячейка, то выборка раликально сократится с 395 строк до 97 строк, поэтому удалять такие строки нельзя
Выбросы найдены столбцах с данными о семейных отношениях и пропущенных занятиях, их получилось легко устранить
Положительная корреляция между образованием матери и результатом экзамена выглядит лонично, так как в нашем обществе именно мать - тот человек, который наиболее вовлечен в образование детей. Но на этих данных корреляция слабая. Это может быть обусловлено тем, что не все матери из выборки имеют возможность следить за успеваемостью детей и помогать им, включая тех, у кого есть высшее образование. Возможно, уровень преподавания существенно вырос и программа усложнилась, и матери не могут помогать детям, даже несмотря на формально неплохое образование
Обнаружена умеренная обратная корреляция с количеством внеучебных неудач.Содержание этого столбца не ясно, поэтому сложно выдвигат гипотезы, кроме как, что такие личные качества как стрессоустойчивость могут влиять на количество внеучебных неудач и на результат экзамена, но оставить этот столбец для модели стоит
При анализе номинативных переменных с помощью графиков с помощью теста Стьюдента обнаружены столбцы влияющие на результат - address, Mjob, higher, romantic
Но если посмотреть на диаграммы размаха, то кажется, что не стоит также исключать столбцы Fjob и internet. Возможно стоит сгруппировать работу отца в две категории - teacher и other. На диаграмме internet по значению No видны выбросы, которые могут быть ошибками в данных и влиять на результат теста Стьюдента
Для модели предлагается следующие столбцы: Medu, failures, address, Mjob, Fjob, higher, internet, romantic

→ этапы работы над проектом.
посмотреть на данные
оценить нужно ли удалять, либо заполнять пустые значения
анализ количественных переменных
анализ номинативных переменных
формулирование выводов

→ ответы на вопросы саморефлексии:

1. Какова была ваша роль в команде?
сама себе команда

2. Какой частью своей работы вы остались особенно довольны?
эту работу я могла бы сделать лучше, особенна никакой не довольна

3. Что не получилось сделать так, как хотелось? Над чем ещё стоит поработать?
почти все не получилось как хотелось из-за болезни

4. Что интересного и полезного вы узнали в этом модуле?
возможно статистика не так скучна и сложна, модуль понравился

5. Что является вашим главным результатом при прохождении этого проекта?

что я смогла сделать основные этапы

6. Какие навыки вы уже можете применить в текущей деятельности?

7. Планируете ли вы дополнительно изучать материалы по теме проекта?
Да
