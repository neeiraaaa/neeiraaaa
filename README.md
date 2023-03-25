### Добро пожаловать! :slightly_smiling_face:
Меня зовут Ирина. Я - инженер по тестированию программного обеспечения :woman_technologist: </br>

  
  [![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=neeiraaaa
)](https://github.com/GithubRedMouth/github-readme-stats)

- Контакты:

  Email: neeiraaaa@gmail.com
<p>
  &#8287;&#8287;&#8287;&#8287;&#8287;
  <a href="https://t.me/neeiraaaa"><img width="37px" alt="Telegram" title="Telegram" src="./images/icons/tg.png"/></a>
  &#8287;

</p>

## 💻Стек и инструменты

<p  align="center">
  <code><img width="5%" title="Python" src="./images/icons/python.png"></code>
  <code><img width="5%" title="PyCharm" src="./images/icons/pycharm.png"></code>
  <code><img width="6%" title="Pytest" src="./images/icons/pytest.png"></code>
  <code><img width="6%" title="Selene" src="./images/icons/selene.png"></code>
  <code><img width="5%" title="Allure Report" src="./images/icons/allure_report.png"></code>
  <code><img width="5%" title="Github" src="./images/icons/Git-Logo-Black.png"></code>
  <code><img width="5%" title="Jenkins" src="./images/icons/jenkins.png"></code>
  <code><img width="5%" title="Selenoid" src="./images/icons/selenoid.png"></code>
  <code><img width="5%" title="Appium" src="./images/icons/Appium-01.png"></code>
  <code><img width="5%" title="Selenium" src="./images/icons/selenium.png"></code>
  <code><img width="5%" title="Browserstack" src="./images/icons/browserstack.png"></code>

</p>

## Тестирование UI
:link: Тестовый проект: <a target="_blank" href="https://github.com/neeiraaaa/qa_quru_jenkins">UI_tests</a></br></br>
:heavy_check_mark: Реализованы автотесты UI на сайт DEMOQA </br></br>
:round_pushpin: Что особенного:

- [x] Page Object
- [x] Инкапсуляция
- [x] Интеграция с Allure report


## Тестирование REST API
:link: Тестовый проект: <a target="_blank" href="https://github.com/neeiraaaa/qa_quru_api_4">API_tests</a></br></br>
:heavy_check_mark: Реализованы автотесты Rest API на reqres.in и demowebshop.tricentis.com.</br></br>
:round_pushpin: Что особенного:

- [x] Шаблоны форматирования логов запросов
- [x] Проверка ответа сайта через Shema
- [x] Управление конфигом через pytest


## :computer: Запуск тестов из терминала
```bash
pytest tests/test_demoshop.py --env=prod
pytest tests/test_reqres.py --env=prod
```

## Тестирование мобильного приложения
:link: Тестовый проект: <a target="_blank" href="https://github.com/neeiraaaa/qa_quru_Android_Studio">Mobile_tests</a></br></br>
:heavy_check_mark: Реализованы автотесты мобильного приложения Wikipedia на эмуляторе мобильного устройства.</br></br>
:round_pushpin: Что особенного:

- [x] Интеграция с Browserstack
- [x] Степовой подход для описания Allure Step
- [x] Различные файлы конфигураций для запуска тестов

## :computer: Запуск тестов из терминала
```bash
env -S "context=browserstack" pytest .
env -S "context=emulation" pytest .
```

