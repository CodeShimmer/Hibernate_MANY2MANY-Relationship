# Hibernate_MANY2MANY-Relationship
22:49:12,533  INFO [main] Version:15 - Hibernate Annotations 3.2.0.GA
22:49:12,617  INFO [main] Environment:500 - Hibernate 3.2.1
22:49:12,637  INFO [main] Environment:518 - loaded properties from resource hibernate.properties: {hibernate.connection.driver_class=org.h2.Driver, hibernate.service.allow_crawling=false, hibernate.max_fetch_depth=5, hibernate.dialect=org.hibernate.dialect.H2Dialect, hibernate.format_sql=true, hibernate.generate_statistics=true, hibernate.connection.username=sa, hibernate.connection.url=jdbc:h2:mem:db1;DB_CLOSE_DELAY=-1;LOCK_TIMEOUT=10000, hibernate.bytecode.use_reflection_optimizer=false, hibernate.connection.password=****, hibernate.connection.pool_size=5}
22:49:12,640  INFO [main] Environment:667 - Bytecode provider name : cglib
22:49:12,701  INFO [main] Environment:584 - using JDK 1.4 java.sql.Timestamp handling
22:49:13,071  INFO [main] Configuration:1423 - configuring from resource: /hibernate.cfg.xml
22:49:13,072  INFO [main] Configuration:1400 - Configuration resource: /hibernate.cfg.xml
22:49:14,410  INFO [main] Configuration:1538 - Configured SessionFactory: null
22:49:14,709  INFO [main] AnnotationBinder:387 - Binding entity from annotated class: com.M2m.student.Student
22:49:14,949  INFO [main] EntityBinder:340 - Bind entity com.M2m.student.Student on table STUDENT1
22:49:15,306  INFO [main] AnnotationBinder:387 - Binding entity from annotated class: com.M2m.student.Course
22:49:15,308  INFO [main] EntityBinder:340 - Bind entity com.M2m.student.Course on table COURSE1
22:49:15,710  INFO [main] DriverManagerConnectionProvider:41 - Using Hibernate built-in connection pool (not for production use!)
22:49:15,711  INFO [main] DriverManagerConnectionProvider:42 - Hibernate connection pool size: 1
22:49:15,715  INFO [main] DriverManagerConnectionProvider:45 - autocommit mode: false
22:49:15,807  INFO [main] DriverManagerConnectionProvider:80 - using driver: com.mysql.jdbc.Driver at URL: jdbc:mysql://127.0.0.1:3306/STUDENTS
22:49:15,808  INFO [main] DriverManagerConnectionProvider:86 - connection properties: {user=Kyte, password=****}
22:49:17,228  INFO [main] SettingsFactory:81 - RDBMS: MySQL, version: 5.7.19-log
22:49:17,229  INFO [main] SettingsFactory:82 - JDBC driver: MySQL-AB JDBC Driver, version: mysql-connector-java-5.0.8 ( Revision: ${svn.Revision} )
22:49:17,301  INFO [main] Dialect:151 - Using dialect: org.hibernate.dialect.MySQL5Dialect
22:49:17,327  INFO [main] TransactionFactoryFactory:31 - Using default transaction strategy (direct JDBC transactions)
22:49:17,333  INFO [main] TransactionManagerLookupFactory:33 - No TransactionManagerLookup configured (in JTA environment, use of read-write or transactional second-level cache is not recommended)
22:49:17,334  INFO [main] SettingsFactory:134 - Automatic flush during beforeCompletion(): disabled
22:49:17,336  INFO [main] SettingsFactory:138 - Automatic session close at end of transaction: disabled
22:49:17,337  INFO [main] SettingsFactory:145 - JDBC batch size: 15
22:49:17,338  INFO [main] SettingsFactory:148 - JDBC batch updates for versioned data: disabled
22:49:17,341  INFO [main] SettingsFactory:153 - Scrollable result sets: enabled
22:49:17,341  INFO [main] SettingsFactory:161 - JDBC3 getGeneratedKeys(): enabled
22:49:17,342  INFO [main] SettingsFactory:169 - Connection release mode: auto
22:49:17,346  INFO [main] SettingsFactory:193 - Maximum outer join fetch depth: 5
22:49:17,347  INFO [main] SettingsFactory:196 - Default batch fetch size: 1
22:49:17,347  INFO [main] SettingsFactory:200 - Generate SQL with comments: disabled
22:49:17,348  INFO [main] SettingsFactory:204 - Order SQL updates by primary key: disabled
22:49:17,348  INFO [main] SettingsFactory:369 - Query translator: org.hibernate.hql.ast.ASTQueryTranslatorFactory
22:49:17,358  INFO [main] ASTQueryTranslatorFactory:24 - Using ASTQueryTranslatorFactory
22:49:17,359  INFO [main] SettingsFactory:212 - Query language substitutions: {}
22:49:17,360  INFO [main] SettingsFactory:217 - JPA-QL strict compliance: disabled
22:49:17,360  INFO [main] SettingsFactory:222 - Second-level cache: enabled
22:49:17,360  INFO [main] SettingsFactory:226 - Query cache: disabled
22:49:17,361  INFO [main] SettingsFactory:356 - Cache provider: org.hibernate.cache.NoCacheProvider
22:49:17,361  INFO [main] SettingsFactory:241 - Optimize cache for minimal puts: disabled
22:49:17,362  INFO [main] SettingsFactory:250 - Structured second-level cache entries: disabled
22:49:17,378  INFO [main] SettingsFactory:270 - Echoing all SQL to stdout
22:49:17,402  INFO [main] SettingsFactory:277 - Statistics: enabled
22:49:17,406  INFO [main] SettingsFactory:281 - Deleted entity synthetic identifier rollback: disabled
22:49:17,413  INFO [main] SettingsFactory:296 - Default entity-mode: pojo
22:49:17,672  INFO [main] SessionFactoryImpl:161 - building session factory
22:49:19,008  INFO [main] SessionFactoryObjectFactory:82 - Not binding factory to JNDI, no JNDI name configured
22:49:19,083  INFO [main] SchemaExport:154 - Running hbm2ddl schema export
22:49:19,125  INFO [main] SchemaExport:179 - exporting generated schema to database
22:49:28,162  INFO [main] SchemaExport:196 - schema export complete
Hibernate: 
    insert 
    into
        STUDENT1
        (STUDENT_NAME) 
    values
        (?)
Hibernate: 
    insert 
    into
        COURSE1
        (COURSE_NAME) 
    values
        (?)
Hibernate: 
    insert 
    into
        COURSE1
        (COURSE_NAME) 
    values
        (?)
Hibernate: 
    insert 
    into
        STUDENT1
        (STUDENT_NAME) 
    values
        (?)
Hibernate: 
    insert 
    into
        STUDENT_COURSE
        (STUDENT_ID, COURSE_ID) 
    values
        (?, ?)
Hibernate: 
    insert 
    into
        STUDENT_COURSE
        (STUDENT_ID, COURSE_ID) 
    values
        (?, ?)
Hibernate: 
    insert 
    into
        STUDENT_COURSE
        (STUDENT_ID, COURSE_ID) 
    values
        (?, ?)
Hibernate: 
    insert 
    into
        STUDENT_COURSE
        (STUDENT_ID, COURSE_ID) 
    values
        (?, ?)
