# SpringMVCApp
- приложеие SpringMVCAppWebXML осуществляется с помощью xml файлов
1. Добавление зависимостей в pom.xml
2. Реализация applicationContext.xml 
3. Реализация контроллера и представления(без модели)
- приложение SpringMVCAppJavaConfig с помощью Java кода
1. замена web.xml файла java классом AbstractAnnotationConfigDispatcherServletInitializer реализующим интерфейс org.springframework.web.WebApplicationInitializer с реализацией всех деталей
2. замена applicationContext.xml файла java классом SpringConfig в котором реализуются бины для замены шаблонизатора thymeleaf
