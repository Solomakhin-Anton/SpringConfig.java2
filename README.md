# Java-code configuration
_(продолжение)_

## Задание

1. Внедрим зависимости вручную.

## Решение

1. Удаляем все аннотации `@Component`, `@Autowired` и `@ComponentScan`.
2. В классе `SpringConfig` создаем бины.
3. При создании бина `musicPlayer()` мы должны ему внедрить зависимости в конструктор - `rockMusic` и `classicalMusic`, для этого на вход отправляем методы.
4. При создании бина `computer()` ему внедрим бин `musicPlayer()`.
5. Запускаем - все работает как раньше.