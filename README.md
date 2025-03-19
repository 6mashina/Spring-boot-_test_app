# Spring-boot_test_app
Test

#BD

```sql
CREATE TABLE users (
    user_id SERIAL PRIMARY KEY,
    username VARCHAR(10) UNIQUE NOT NULL,
    password VARCHAR(255) NOT NULL,
);
CREATE TABLE labels (
    id SERIAL PRIMARY KEY,
    number BIGINT NOT NULL,
    text VARCHAR(255) NOT NULL,
    date DATE NOT NULL,
    image VARCHAR(255) NOT NULL
);


 INSERT INTO labels (number, text, date, image)
    VALUES
        (1001, 'Этикетка 1', '2024-03-01', 'image1.png'),
        (1002, 'Этикетка 2', '2024-03-02', 'image2.png'),
        (1003, 'Этикетка 3', '2024-03-03', 'image3.png'),
        (1004, 'Этикетка 4', '2024-03-04', 'image4.png'),
        (1005, 'Этикетка 5', '2024-03-05', 'image5.png'),
        (1006, 'Этикетка 6', '2024-03-06', 'image6.png'),
        (1007, 'Этикетка 7', '2024-03-07', 'image7.png'),
        (1008, 'Этикетка 8', '2024-03-08', 'image8.png'),
        (234251, 'Этикетка 9', '2024-03-09', 'image9.png'),
        (1010, 'Этикетка 10', '2024-03-10', 'image10.png'),
        (1011, 'Этикетка 11', '2024-03-11', 'image11.png'),
        (1012, 'Этикетка 12', '2024-03-12', 'image12.png'),
        (1013, 'Этикетка 13', '2024-03-13', 'image13.png'),
        (1014, 'Этикетка 14', '2024-03-14', 'image14.png'),
        (1015, 'Этикетка 15', '2024-03-15', 'image15.png'),
        (1016, 'Этикетка 16', '2024-03-16', 'image16.png'),
        (1017, 'Этикетка 17', '2024-03-17', 'image17.png'),
        (1018, 'Этикетка 18', '2024-03-18', 'image18.png'),
        (1019, 'Этикетка 19', '2024-03-19', 'image19.png'),
        (1020, 'Этикетка 20', '2024-03-20', 'image20.png');
```
