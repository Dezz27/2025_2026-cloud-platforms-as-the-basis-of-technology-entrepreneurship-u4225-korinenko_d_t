University: [ITMO University](https://itmo.ru/ru/) \
Faculty: [FICT](https://fict.itmo.ru) \
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/) \
Year: 2025/2026 \
Group: U4225 \
Author: Korinenko Daniil Trofimovich \
Lab: Lab1 \
Date of create: 28.11.2025 \
Date of finished: \

## Ход работы
1. Service Account с ролью Storage Admin ![1764343166618](image/lab1_report/1764343166618.png)

2. Создание виртуальной машины: ![1764344024870](image/lab1_report/1764344024870.png)

3. Данные о машине: ![1764344363461](image/lab1_report/1764344363461.png)

4. Копирование файлов и добавление их в папку: ![1764344815661](image/lab1_report/1764344815661.png)

5. Изменение роли на `Compute Viewer`: ![1764344987559](image/lab1_report/1764344987559.png)

6. После изменения роли SA как будто ничего не поменялось, потому что так же получилось скопировать файлы. Возможно, дело в том, что сервис аккаунт не был привязан каким-то образом к VM ![1764345833136](image/lab1_report/1764345833136.png)

7. Удаляем созданную VM: ![1764345913351](image/lab1_report/1764345913351.png)