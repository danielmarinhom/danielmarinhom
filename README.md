CREATE TABLE perfil (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    country VARCHAR(50),
    pronouns VARCHAR(20),
    skills TEXT
);

INSERT INTO perfil (name, age, country, pronouns, skills)
VALUES ('Arthur', 16, 'Brazil', 'he/him', 'HTML, CSS, Javascript, C++, SQL');
