CREATE TABLE perfil (
    &nbsp id INT PRIMARY KEY,
    &nbsp name VARCHAR(50),
    &nbsp age INT,
    &nbsp country VARCHAR(50),
    &nbsp pronouns VARCHAR(20),
    &nbsp skills TEXT
);

INSERT INTO perfil (name, age, country, pronouns, skills)
VALUES ('Daniel', 16, 'Brazil', 'he/him', 'HTML, CSS, Javascript, C++, SQL');
