# Отчёт о тестировании Precision

## Краткое описание

20.07.2021 - 20.07.2021 было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: 10 минут

В результате тестирования выявлены следующие дефекты:
* [Некорректный расчет переменной totalBonus](https://github.com/Milaaver/Precision/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [данные задачи-легенды](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---precision)


В качестве тестовых данных использовались данные из задачи легенды:

Входные данные:
```
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

Тестирование производилось в следующем окружении:
* Windows 10 Домашняя
Версия ОС:                        10.0.19042 Н/Д построение 19042
Изготовитель ОС:                  Microsoft Corporation
* IntelliJ IDEA 2021.1.3 (Community Edition)
Build #IC-211.7628.21, built on June 30, 2021
Runtime version: 11.0.11+9-b1341.60 amd64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.

