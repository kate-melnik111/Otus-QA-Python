#PythonQAOtus

Моя первая домашняя работа Otus -Пирамида тестирования

Пирамида автоматического тестирования на текущем своём проекте:
1.	Unit tests (юнит-тесты)
2.	Integration tests (интеграционные тесты)
3.	UI tests (тесты пользовательского интерфейса)

==============================================================

Описание тестов:
-----------------------------------------------------------------
(1)	Unit tests (юнит-тесты)
-----------------------------------------------------------------
Unit tests  (50%): проверяют на корректность отдельные модули исходного кода. Тесты  пишутся самим разработчиком ещё до написания основного кода. Наши разработчики пишут все тесты на Java.
Основа набора тестов состоит из юнит-тестов (модульных тестов). Они проверяют, что отдельный юнит (тестируемый субъект) работает должным образом.

Преимущества:
1)	лучше качество кода;
2)	скорость нахождения багов: в случае, если тест провалится, разработчику будет легко обнаружить и исправить ошибку;
3)	возможность тестировать базовую функциональность без UI;
4)	unit-тесты позволяют  проводить рефакторинг кода без опасений сломать работу приложения;
5)	unit-тесты могут рассказать, как та или иная функции должны реагировать на разные входные параметры.

Недостатки:
1)	при недостаточно продуманной архитектуре проекта тесты могут мешать изменению кода, а не способствовать ему;
2)	при тестировании каждого элемента программного кода в отдельности от других, никто не сможет сказать наверняка, что произойдёт, когда мы объединим все модули вместе.

-----------------------------------------------------------------
(2)	Integration tests (интеграционные тесты)
-----------------------------------------------------------------
Integration tests (15%):  позволяют проверить, могут ли два наших модуля работать вместе. В основном, пишут у нас разработчики.

Преимущества:
1)	дают уверенность в правильной работе приложения со всеми внешними частями, с какими нужно;
2)	тестируя за пределами пользовательского интерфейса, можно тестировать входы и выходы API или сервисов без всех сложностей, которые вводит пользовательский интерфейс.

Недостатки:
1)	тесты медленнее и сложнее, чем модульные тесты, потому что им может потребоваться доступ к базе данных или другим компонентам.

-----------------------------------------------------------------
 (3) UI tests (тесты пользовательского интерфейса)
-----------------------------------------------------------------
User interface (UI) tests (35%): проверяют правильность работы пользовательского интерфейса приложения. Тесты пишутся тестировщиком на основе Selenium.

Преимущества:
1)	покрывает большую часть пользовательских действий и позволяет, со стороны юзера, потрогать приложение.
2)	проверяет взаимодействие компонентов и сервисов между собой.

Недостатки:
1)	UI-тесты гоняются дольше, чем unit-тесты, из-за сложности используемых сервисов;
2)	тесты пользовательского интерфейса сложно писать и они очень сильно зависят даже от малейших изменений.

==============================================================

Предложения по улучшению текущей пирамиды:

1)	Тесты пользовательского интерфейса медленнее и тяжелее в написании и поддержке, поэтому необходимо сводить их к минимуму.
2)	Увеличить количество модульных тестов (они недорогие, просто пишутся и легко поддерживаются). 
3)	Тестирование должно быть разносторонним, но соотношение тестов должно быть таково, что модульных количественно больше, чем GUI. Системные тесты занимают золотую середину.

Планы: 
- покрыть автотестами имеющийся функционал, который разработан давно и давно не менялся; 
- освоить Python для тестирования веб-приложений;
- стать крутым специалистом в области автоматизации тестирования ПО. 
