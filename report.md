# Отчёт о тестировании Приложения "Money Transfer"
## Краткое описание
26.03.2020  было проведено тестирование кода:
```java
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```
## Описание процесса тестирования
Записали код в новом классе Main.java среде среде IntelliJ IDEA и запустили на выполнение.
Процесс завершился без ошибок ```Process finished with exit code 0```.

## Результаты
1. Приложение запустилось и выдало значение = 0.8999999999999999. Ожидаемый результат = 0,9.
2. [Баг-репорт](https://github.com/DementevSlava/-1.2.Homework-2/issues/1)