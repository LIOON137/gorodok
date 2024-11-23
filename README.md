CREATE TABLE gorodok (
empId INTEGER PRIMARY KEY,
name varchar(50),
status varchar(50)
);

— insert
INSERT INTO gorodok VALUES (0001, 'Fedor', 'gorozhanin');
INSERT INTO gorodok VALUES (0002, 'Alex', 'gorozhanin');
INSERT INTO gorodok VALUES (0003, 'Nicolay', 'gorozhanin');
INSERT INTO gorodok VALUES (0004, 'Sasha', 'gorozhanin');
INSERT INTO gorodok VALUES (0005, 'Kirill', 'gorozhanin');
INSERT INTO gorodok VALUES (0006, 'Stas', 'bandit');
INSERT INTO gorodok VALUES (0007, 'Erema', 'bandit');
INSERT INTO gorodok VALUES (0008, 'Petr', 'doctor');
INSERT INTO gorodok VALUES (0009, 'Gena', 'sherif');

— fetch
SELECT * FROM gorodok WHERE status = 'bandit';
