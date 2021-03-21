```
spring.datasource.driverClassName=org.h2.Driver

spring.datasource.username=sa

spring.datasource.password=

spring.jpa.database-platform=org.hibernate.dialect.H2Dialect

spring.datasource.url=jdbc:h2:mem:testdb

spring.h2.console.enabled=true

spring.h2.console.path=/h2-console
```

```
# Go to Preference -> build,execution,deployment. -> Compiler.
Enable build project automatically
# Ctrl+ Shift+A (Windows) -> Registry
compiler.automake.allow.when.app.running
```

```
mvn sonar:sonar -Dsonar.login="admin" -Dsonar.password="admin"
```

