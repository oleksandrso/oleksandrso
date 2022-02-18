# Oleksandr Sotnichenko
### Glad to see you! On my Page :house_with_garden: you can find main information about me
### My Contacts:
[![Telegram](https://github.com/oleksandrso/attachments/blob/main/img/telegram%20contact.png)](https://t.me/oleksandrso "oleksandrso")
[![Email](https://github.com/oleksandrso/attachments/blob/main/img/email.png)](mailto:alex.worksot@gmail.com "alex.worksot@gmail.com") [![Instagram](https://github.com/oleksandrso/attachments/blob/main/img/instagram.png)](https://www.instagram.com/alexandrsot/ "alexandrsot") [![YouTube](https://github.com/oleksandrso/attachments/blob/main/img/youtube.png)](https://www.youtube.com/channel/UCJIE-9PfiwK0igG1vwZcvEg "YouTube")





## Full Stuck QA Egineer:

-  Automation  Specialist :computer:
-  Manual Specialist :hand:
-  Team lead :gun:
-  Teacher & Mentor :mortar_board:



## Technologies what i ~~know~~:
### Development of autotests: 
 ![Intelij IDEA](https://github.com/oleksandrso/attachments/blob/main/img/Intelij_IDEA.png "IntelliJ IDEA— интегрированная среда разработки программного обеспечения для многих языков программирования, в частности Java, JavaScript, Python, разработанная компанией JetBrains") ![Android Studio](https://github.com/oleksandrso/attachments/blob/main/img/android-studio.png "Android Studio- среда разработки программного обеспечения для  Андроид девайсов разработанная компанией JetBrains") ![xCode](https://github.com/oleksandrso/attachments/blob/main/img/xcode.png "xCode-среда разработки программного обеспечения для Apple девайсов разработанная компанией Apple") ![Java](https://github.com/oleksandrso/attachments/blob/main/img/Java.png "Java— строго типизированный объектно-ориентированный язык программирования общего назначения, разработанный компанией Sun Microsystems") ![Selenium](https://github.com/oleksandrso/attachments/blob/main/img/Selenium.png "Selenium— это инструмент для автоматизации действий веб-браузера. В большинстве случаев используется для тестирования Web-приложений, но этим не ограничивается") ![Selenide](https://github.com/oleksandrso/attachments/blob/main/img/Selenide.png "Selenide— это фреймворк для автоматизированного тестирования веб-приложений на основе Selenium") ![JUnit5](https://github.com/oleksandrso/attachments/blob/main/img/JUnit5.png "JUnite5— библиотека для модульного тестирования программного обеспечения на языке Java") ![Gradle](https://github.com/oleksandrso/attachments/blob/main/img/Gradle.png "Gradle— система автоматической сборки, построенная на принципах Apache Ant и Apache Maven, но предоставляющая DSL на языках Groovy и Kotlin вместо традиционной XML-образной формы представления конфигурации проекта") ![Appium](https://github.com/oleksandrso/attachments/blob/main/img/Appium.png "Appium— это бесплатный кроссплатформенный инструмент с открытым исходным кодом, который помогает автоматизировать приложения как для Android, так и для iOS") ![Rest-Assured](https://github.com/oleksandrso/attachments/blob/main/img/Rest-Assured.png "Rest-Assured— DSL для тестирования REST-сервисов, который встраивается в тесты на Java. Это решение стало популярным из-за своей простоты и удобного функционала")

### Building infrastructure 
![Github](https://github.com/oleksandrso/attachments/blob/main/img/Github.png "Github— крупнейший веб-сервис для хостинга IT-проектов и их совместной разработки") ![Jenkins](https://github.com/oleksandrso/attachments/blob/main/img/Jenkins.png "Jenkins— программная система с открытым исходным кодом на Java, предназначенная для обеспечения процесса непрерывной интеграции программного обеспечения") ![Docker](https://github.com/oleksandrso/attachments/blob/main/img/Docker.png "Docker— программное обеспечение для автоматизации развёртывания и управления приложениями в средах с поддержкой контейнеризации, контейнеризатор приложений") ![Selenoid](https://github.com/oleksandrso/attachments/blob/main/img/Selenoid.png "Selenoid— это программа, которая позволяет управлять браузерами и Android-эмуляторами с помощью специальных драйверов") ![Browserstack](https://github.com/oleksandrso/attachments/blob/main/img/Browserstack.png "Browserstack— это облачная платформа для тестирования, которая предоставляет разработчикам возможность тестировать свои веб-сайты и мобильные приложения в браузерах, операционных системах и реальных мобильных устройствах")

### Visualization of test results & Test managment
![Allure Report](https://github.com/oleksandrso/attachments/blob/main/img/Allure_Report.png "Allure Report— позволяет представить данные о запуске тестов в виде простого и удобного HTML-отчета") ![Allure TestOps](https://github.com/oleksandrso/attachments/blob/main/img/Allure_EE.png "Allure TestOps— это платформа управления качеством программного обеспечения, объединяющая автоматическое и ручное тестирование, которая позволяет управлять всем, что связано с тестированием, в одном месте") ![Jira](https://github.com/oleksandrso/attachments/blob/main/img/Jira.png "Jira— коммерческая система отслеживания ошибок, предназначена для организации взаимодействия с пользователями, также используется для управления проектами")![Telegram](https://github.com/oleksandrso/attachments/blob/main/img/Telegram.png "Telegram— специальные аккаунты в Telegram, созданные для того, чтобы автоматически обрабатывать и отправлять сообщения")

## Something Task on 2022 year:
- [x] ~~learn English~~
- [ ] make new project
- [ ] Create new self-help course
___
> ### Some feedback about me
  > - >Feedback 1
  > - >Feedback 2
  > - >Feedback 3

___

## Some code for example:
```JAVA
@Tag("Smoke")
    @ParameterizedTest(name = "Поиск {0} в duckduckgo.com")
    @DisplayName("Поиск в duckduckgo.com")
    @ValueSource(strings = {"Selenide","Allure"})
    void duckSearchCommon(String searchValue) {

        open("https://duckduckgo.com");
        $("#search_form_input_homepage").setValue(searchValue).pressEnter();
        $(".module__title__link").shouldHave(text(searchValue));
    }
```

