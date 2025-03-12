# Docker Compose Lab

### 1. Створення директорії проекту
```sh
mkdir composetest
cd composetest
```

### 2. Створення файлу `app.py` з кодом додатка

### 3. Створення файлу `requirements.txt`

### 4. Створення `Dockerfile`

### 5. Створення файлу `compose.yaml`

### 6. Запуск контейнерів за допомогою Docker Compose
```sh
docker compose up
```
**Результат:**
- Доступ до додатка за адресою `http://localhost:8000/`

### 7. Перевірка локальних образів Docker
```sh
docker image ls
```
**Результат:**
![image](https://github.com/user-attachments/assets/80ab0238-f1f7-4393-990a-ba5318b292f5)


### 8. Використання Compose Watch для автоматичного оновлення
```sh
docker compose watch
```
**Результат:**
![image](https://github.com/user-attachments/assets/eebef240-a03d-44de-bda5-a0fdaa9eb78c)


### 9. Запуск у фоновому режимі
```sh
docker compose up -d
```
**Результат:**
- ![image](https://github.com/user-attachments/assets/371b7070-4119-4d0a-aa7c-23beb7f99f56)


### 10. Перевірка запущених контейнерів
```sh
docker compose ps
```
![image](https://github.com/user-attachments/assets/83cffce5-4344-4ce8-a720-0df1091d7f71)


### 11. Зупинка запущених контейнерів
```sh
docker compose stop
```
![image](https://github.com/user-attachments/assets/2fd87015-d800-469e-b3bd-041a7b0cb729)

### 12. Повне видалення контейнерів
```sh
docker compose down
![image](https://github.com/user-attachments/assets/5487cb67-afbc-410e-a8e2-4527afc6f1d0)

