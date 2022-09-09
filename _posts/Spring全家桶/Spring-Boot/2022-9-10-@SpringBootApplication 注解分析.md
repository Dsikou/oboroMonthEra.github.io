# @SpringBootApplication 注解分析

- @SpringBootApplication：它是一个复合注解，标注在一个主程序类上，说明这是一个 spring boot 应用
- @Target({ElementType.TYPE}) ：类、接口（包括注解类型）和 enum 声明
- @Retention(RetentionPolicy.RUNTIME)：运行时注解
- @Documented：将注解添加到 java doc 中
- @Inherited：允许继承
- @SpringBootConfiguration：spring boot 配置注解
- @EnableAutoConfiguration：启动自动配置注解
- @ComponentScan：组件自动扫描注解
- @Configuration：它是从 spring3 开始存在，主要用于定义配置类，替代 XML 配置文件
- @AutoConfigurationPackage：作用是将标注的组件注册到 spring 的 IOC 容器中，默认当前主程序类所在的包及其子包，这些包中的组件会被加载到容器中
