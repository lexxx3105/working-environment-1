# Webpack5

[Руководство по настройке Webpack](https://webpack.js.org/guides/)
[Руководство по настройке GitHub Actions](https://docs.github.com/en/actions/quickstart)

# Домашнее задание к занятию "1. Рабочее окружение"
![CI](https://github.com/lexxx3105/working-environment-1/actions/workflows/web.yml/badge.svg)

**Важно**: все задачи к данной лекции можно выполнить в виде одного репозитория (т.е. допускается не делать отдельные репозитории на каждую задачу).

### Continuous Deployment

#### Описание

Воспользуйтесь пошаговой инструкцией ниже, чтобы развернуть тестирование, сборку и deployment на GitHub Actions и GitHub Pages.

В качестве шаблона для развёртывания используйте [проект](https://github.com/netology-code/ahj-code/tree/master/env).

Не забудьте поставить бейджик со статусом в `README.md`.

**В качестве результата пришлите проверяющему ссылку на ваш GitHub-проект.**

### Инструкция:
1. Скачать репозиторий https://github.com/netology-code/ahj-code/tree/master/env
2. Создать новый репозиторий на github
3. Скопировать в новый репозиторий папку `env`
4. Настроить новый репозиторий. Указать в нём использование GitHub Action для публикации приложения, вместо публикации из ветки (gh-pages)
   ![alt text](./github-setup.png)
5. В файле `README.md` в строке:
```md
![CI](https://github.com/<OWNER>/<REPOSITORY>/actions/workflows/web.yml/badge.svg)
```
Заменить `<OWNER>` на ваш ник на github;

Заменить `<REPOSITORY>` на название вашего репозитория;