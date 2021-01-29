## Simple Spring Boot.

Простое приложение на Spring Boot с минимальной конфигурацией. 

### Технологии.

 * **spring-boot-starter** - зависимость фреймворка Spring для написания приложений с минимальной конфигурацией.
 * **maven** - фреймворк для автоматизации сборки проектов на основе описания их структуры в файлах на языке POM (англ. Project Object Model).

### Функционал.

Приложение ничего не делает, просто запускается и останавливается.

```txt
      .   ____          _            __ _ _
     /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
    ( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
     \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
      '  |____| .__|_| |_|_| |_\__, | / / / /
    =========|_|==============|___/=/_/_/_/
    :: Spring Boot ::                (v2.4.2)
    
    2021-01-29 22:54:04.830  INFO 7256 --- [           main] com.simple.SimpleApplication             : Starting SimpleApplication using Java 11.0.9.1 on DELL5280 with PID 7256
    2021-01-29 22:54:04.836  INFO 7256 --- [           main] com.simple.SimpleApplication             : No active profile set, falling back to default profiles: default
    2021-01-29 22:54:06.199  INFO 7256 --- [           main] com.simple.SimpleApplication             : Started SimpleApplication in 2.546 seconds (JVM running for 4.006)
    
    Process finished with exit code 0
```

### Сборка исполняемого jar-файла в командной строке.

Используя **shell**, перейдите в корневой каталог проекта (*где находится файл pom.xml*) и введите:

    mvn clean package  
    cd target  

### Сборка исполняемого jar-файла в IntelliJ IDEA.
    
Справа раскрываем вкладку "Maven" и выбираем "package", жмем "Run".  
Готовый jar-файл будет в директории:

    src/target/simple-0.0.1-SNAPSHOT.jar


### Запуск приложения.
    
    java -jar simple-0.0.1-SNAPSHOT.jar
