# Spring-Security-Overview

### Authentication

Spring Security ให้การสนับสนุนที่ครอบคลุมสำหรับสำหรับการทำ Authentication

#### ภาพรวมของ Spring Security Module

<p align="center">
  <img src="https://user-images.githubusercontent.com/15135199/95062787-a3504d80-0727-11eb-92a9-90e12434b9f8.png" width="250">
</p>

 #### FilterChain
 
 Client ส่ง Request ไปยัง Application และ Container จะทำการสร้าง FilterChain ซึ่งมี Filters และ Servlet ที่ประมวลผล HttpServletRequest 
 
