# Java CI/CD Pipeline

Лабораторная работа: настройка пайплайна CI/CD для Java-приложения (Maven + Docker) с использованием GitHub Actions.

## 1. Локальная сборка и запуск Docker
Приложение успешно собирается в Multi-stage Docker и запускается.
**<img width="880" height="162" alt="изображение" src="https://github.com/user-attachments/assets/e7979b80-dd9f-4228-8b43-4029cd1bc931" />
**

## 2. Успешный запуск пайплайна (GitHub Actions)
Пайплайн собирает проект, запускает тесты (JUnit 5) и собирает Docker-образ. Все этапы завершились успешно.
**<img width="711" height="222" alt="изображение" src="https://github.com/user-attachments/assets/0555db39-190a-44d3-9d2e-d0bc1e66b714" />
**

## 3. Логи сборки и тестирования Maven
Шаг `Build and test` успешно выполнил `mvn clean verify`, все тесты пройдены.
**<img width="1159" height="713" alt="изображение" src="https://github.com/user-attachments/assets/163256d7-267b-410b-b7b2-60277fd587e0" />**

## 4. Логи сборки Docker-образа
Шаг `Build Docker image` успешно собрал образ на основе `eclipse-temurin`.
**<img width="1085" height="681" alt="изображение" src="https://github.com/user-attachments/assets/f80c8eff-3b3b-4b9c-b0c3-b8fa3c350642" />**

## Вывод
Настроен полный цикл CI для Java-приложения. Автоматизированы сборка (Maven), тестирование (JUnit 5) и контейнеризация (Docker). Все задачи выполнены.
