CREATE TABLE perfil (<br>
    <pre>id INT PRIMARY KEY,<br>
    name VARCHAR(50),<br>
    age INT,<br>
    country VARCHAR(50),<br>
    pronouns VARCHAR(20),<br>
    skills TEXT<br></pre>
);

INSERT INTO perfil (name, age, country, pronouns, skills)<br>
VALUES ('Arthur', 16, 'Brazil', 'he/him', 'HTML, CSS, Javascript, C++, SQL');
