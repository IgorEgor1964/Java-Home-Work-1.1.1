# ДЗ к занятию «1.1 Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»

## Задача №1 - KeyValidator

### 1. Проверка установки OpenJDK11.

- Шаг 1. Перел на сайт adoptopenjdk.net.
- Шаг 2. Выбрал опции и нажал на кнопку скачивания.
- Шаг 3. Запустил установку кнопкой "Next".
- Шаг 4. Прочитал и согласился с условиями лицензии, "Next".
- Шаг 5. Выберите опции Add to PATH, "Next".
- Шаг 6. Нажал на кнопку "Install".
- Шаг 7. Установка окончена и нажал кнопку "Finish".
 
### 2. Проверка запуска приложения.

- Открыл терминал и выполнил команду java -version.

![Java - 01](https://user-images.githubusercontent.com/77262709/109904663-4dd59800-7ce9-11eb-8a46-28467dd6843d.png)
- Программа OpenJDK11 установлена на компютер согласно руководству пользователя в соответствии с ожидаемым результатом.

### 3. Проверка работы приложения KeyValidator согласно руководству использования.

### Краткое описание.

Дата: 04.03.2020 - 04.03.2020

Тестирование приложения KeyValidator на предмет валидности и невалидности проверочных ключей.

На тестирование затрачено: 2 часа.

В результате тестирования выявлены следующие дефекты:

-https://github.com/IgorEgor1964/Java-Home-Work-1.1.1/issues/1

-https://github.com/IgorEgor1964/Java-Home-Work-1.1.1/issues/2

### Описание процесса тестирования:

В процессе тестирования использовались следующие артефакты:

- программа KeyValidator
- руководство использования программы KeyValidator
- терминал Windows 10

В качестве тестовых данных использовались данные:

- валидные и невалидные ключи
- 
- Шаг 1: открыть терминал Windows
- Шаг 2: проверить версию Java

  ![image](https://user-images.githubusercontent.com/77262709/109913870-7c0fa380-7cfa-11eb-967f-b8f763503b9e.png)
- Шаг 3: ввести валидный ключ 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 
  ![image](https://user-images.githubusercontent.com/77262709/109914150-14a62380-7cfb-11eb-88b9-f9a11b88c927.png)
- Шаг 4: ввести валидный ключ 80b427f8-92cd-3aae-ba04-3927fbe17c6
  ![image](https://user-images.githubusercontent.com/77262709/109914375-91390200-7cfb-11eb-9f0e-0fa8c1d8df36.png)  ----- БАГ
- Шаг 5: ввести валидный ключ b295bc63-9f03-3b4b-af80-969b39f8c262
  ![image](https://user-images.githubusercontent.com/77262709/109914496-d9582480-7cfb-11eb-9132-e22719fbd979.png)
- Шаг 6: ввести валидный ключ 387eedc6-12e9-3b32-9881-63b6b5e85317
- ![image](https://user-images.githubusercontent.com/77262709/109914727-54b9d600-7cfc-11eb-96c7-54d31cc7d09f.png)  ----- БАГ
- Шаг 7: ввести валидный ключ c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
  ![image](https://user-images.githubusercontent.com/77262709/109914960-baa65d80-7cfc-11eb-97c2-8cbcd66ee691.png)
- Шаг 8: ввести невалидный ключ 18252235-78e0-44a5-8720-556f0c7da17a
  ![image](https://user-images.githubusercontent.com/77262709/109915110-fa6d4500-7cfc-11eb-9b5c-d1a9a5d94ea7.png)
- Шаг 9: ввести невалидный ключ e66075b6-ddad-445e-baf6-161b3289522b
  ![image](https://user-images.githubusercontent.com/77262709/109915259-3bfdf000-7cfd-11eb-9d4b-bc721172bd83.png)
- Шаг 10: ввести невалидный ключ b6d53250-f07e-4352-a293-6102ddf7f1ca
  ![image](https://user-images.githubusercontent.com/77262709/109915416-8d0de400-7cfd-11eb-8755-ee2e4baa550d.png)
- Шаг 11: ввести невалидный ключ c2bc778a-1cb9-46c6-b435-0489649d2a42
  ![image](https://user-images.githubusercontent.com/77262709/109915518-b890ce80-7cfd-11eb-9dc5-d9946b4172f6.png)
- Шаг 12: ввести невалидный ключ 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1
  ![image](https://user-images.githubusercontent.com/77262709/109915658-e9710380-7cfd-11eb-8f95-144d3681f8cc.png)  ----- БАГ

Тестирование производилось в следующем окружении:

- Windows 10 Домашняя 20H2, 64-разрядная операционная система, процессор x64
- Java version 11.0.10 2021-01-19 LTSJava
