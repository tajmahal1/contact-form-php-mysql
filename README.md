# contact-form-php-mysql
საკონტაქტო ფორმა php-mysql ით


phpmyadmin_ში ვაკეთებთ table-ს სახელად contact ან ნებისმიერს რაც გსურთ
1. `contact_id` | int(11) | NOT NULL | A.I |
2. `user_name` | varchar(100) | NOT NULL |
3. `user_email` | varchar(255) | NOT NULL |
4. `subject` | varchar(255) | NOT NULL |
5. `content` | text | NOT NULL | 

ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
