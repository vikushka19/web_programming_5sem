# Лабораторная работа №1: Nginx + Docker

## 👩‍💻 Автор
ФИО: Бондаренко (Родионова) Виктория Дариусовна
Группа: 3МО-2

---

## 📌 Описание задания
Создать веб-сервер в Docker с использованием Nginx и подключить HTML-страницу.  
Результат доступен по адресу [http://localhost:8080](http://localhost:8080).

---

## ⚙️ Как запустить проект

1. Клонировать репозиторий:
   ```bash
   git clone (https://github.com/vikushka19/web_programming_5sem.git)
   cd nginx-lab
Запустить контейнеры:
```bash
docker-compose up -d --build
```
Открыть в браузере:
```http://localhost:8080```
📂 Содержимое проекта

```nginx-lab/docker-compose.yml``` — описание сервиса Nginx

```nginx-lab/code/index.html``` — главная HTML-страница

```nginx-lab/code/about.html``` — вторая HTML-страница

```screenshots/``` — все скриншоты

📸 Скриншоты работы
<img width="826" height="120" alt="version" src="https://github.com/user-attachments/assets/bf2fa6a7-88b4-4ae0-a4ff-e6c3647574b7" />
<img width="1920" height="814" alt="wlcmtnginx" src="https://github.com/user-attachments/assets/ceb608be-427f-4984-b32e-90537ab0dc59" />
<img width="1920" height="931" alt="indexhtml" src="https://github.com/user-attachments/assets/3da7a4bc-1766-47c1-8de9-d55cc700aa1d" />
<img width="1920" height="925" alt="exp1" src="https://github.com/user-attachments/assets/ca6ab8da-29fc-456e-8f8f-3d90da9da290" />
<img width="1920" height="931" alt="exp2" src="https://github.com/user-attachments/assets/919d2bb5-a3c7-4b4d-8266-69d9a24866b3" />
<img width="1920" height="1074" alt="exp3" src="https://github.com/user-attachments/assets/f47f5868-2c55-49aa-bd85-9aa17ce099a3" />



✅ Результат
Сервер в Docker успешно запущен, Nginx отдаёт мою HTML-страницу.
