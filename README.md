CREATE TABLE perfil (
    &nbspid INT PRIMARY KEY,
    &nbspname VARCHAR(50),
    &nbspage INT,
    &nbspcountry VARCHAR(50),
    &nbsppronouns VARCHAR(20),
    &nbspskills TEXT
);

INSERT INTO perfil (name, age, country, pronouns, skills)
VALUES ('Daniel', 16, 'Brazil', 'he/him', 'HTML, CSS, Javascript, C++, SQL');
