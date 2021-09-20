# Отчёт о тестировании homework_java2.1
## Тестирование части JAVA кода

21.09.2021 00:55 - 21.09.2021 01:35 было проведено в приложении IntelliJ IDEA.

На тестирование затрачено: 40 минуты

В результате тестирования выявлены следующие дефекты:
* [Некорректное отображение значения переменной баланса  в java коде #1](https://github.com/AbdEdem/Java2.1/issues/1#issue-1001511321)


В качестве тестовых данных использовался следующая часть JAVA кода:
```
public class Main {
  public static void main(String[] args) {
      int balance = 2_000_000_000;
      int transfer_amount = 500_000_000;
      int total = balanct + transfer_amount;
      System.out.println(total);
  }
```


Тестирование производилось в следующем окружении:
* Laptop, Windows 8Pro 64-bit
* Java v.11
* IntelliJ IDEA v2021.2.2