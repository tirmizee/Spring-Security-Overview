 
 #### @SpringBootApplication to use auto-configuration
 
@SpringBootApplication คือการรวม 
 
 - @EnableAutoConfiguration
 - @ComponentScan
 - @SpringBootConfiguration
 
       @ComponentScan
       @EnableAutoConfiguration
       @SpringBootConfiguration
       public class MyApplication {

           public static void main(String[] args) {
               SpringApplication.run(MyApplication.class, args);
           }

       }
 
 #### 90.1 Switch off the Spring Boot Security Configuration
 
 หากคุณกำหนด @Configuration ด้วย WebSecurityConfigurerAdapter ในแอปพลิเคชันของคุณ มันจะปิดการตั้งค่าความปลอดภัยเริ่มต้นของ webapp ใน Spring Boot
 
