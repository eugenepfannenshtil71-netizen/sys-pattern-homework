# Домашнее задание к занятию "`GitLab`" - `Пфанненштиль Евгений`


### Задание 1


1. `Gitlab локально установлен`
   <img width="1520" height="1038" alt="image" src="https://github.com/user-attachments/assets/038775da-e460-4465-b435-175d57599296" />

2. `Проект и репозиторий созданы`
<img width="3348" height="1380" alt="image" src="https://github.com/user-attachments/assets/fd7e519d-8736-4032-ab40-da857cd2fe0c" />


3. `gitlab-runner`
   <img width="1838" height="668" alt="image" src="https://github.com/user-attachments/assets/c74e3a15-0e92-4c73-90f2-3dbf49425b0a" />

   <img width="1812" height="1720" alt="image" src="https://github.com/user-attachments/assets/a986d2e2-5766-4328-a9b2-3051d97ff646" />



### Задание 2

1.
Содержимое файла .gitlab-ci.yml:

stages:
  - test
  - build

test:
  stage: test
  image: golang:1.17
  script: 
   - go test .

build:
  stage: build
  image: docker:latest
  script:
   - docker build .

2. `Сборки:`
   <img width="2420" height="1092" alt="image" src="https://github.com/user-attachments/assets/a0910fb6-3cfa-4938-9de3-64654cdd608b" />

