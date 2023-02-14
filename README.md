# Game-of-Thrones-MySQL-M4

CREATE DATABASE gameofthrones;

USE gameofthrones;

CREATE TABLE characters (
id int not null auto_increment primary key,
name_char varchar(200),
name_actor varchar(200),
episodes int not null,
first_ap int not null,
last_ap int not null);

DESCRIBE characters;

INSERT INTO characters (name_char, name_actor, episodes, first_ap, last_ap) VALUES 
("Tyrion Lannister",	"Peter Dinklage",	67,	2011,	2019),
("Cersei Lannister",	"Lena Headey",	62,	2011,	2019),
("Daenerys Targaryen",	"Emilia Clarke",	62,	2011,	2019),
("Jon Snow",	"Kit Harington",	62,	2011,	2019),
("Sansa Stark",	"Sophie Turner",	59,	2011,	2019),
("Arya Stark",	"Maisie Williams",	59,	2011,	2019),
("Jaime Lannister",	"Nikolaj Coster-Waldau",	55,	2011,	2019),
("Jorah Mormont",	"Iain Glen",	52,	2011,	2019),
("Samwell Tarly",	"John Bradley",	48,	2011,	2019),
("Theon Greyjoy",	"Alfie Allen",	47,	2011,	2019),
("Lord Varys",	"Conleth Hill",	46,	2011,	2019),
("Davos Seaworth",	"Liam Cunningham",	42,	2012,	2019),
("Brienne of Tarth",	"Gwendoline Christie",	42,	2012,	2019),
("Petyr 'Littlefinger' Baelish",	"Aidan Gillen",	41,	2011,	2017),
("Bran Stark	Isaac", "Hempstead Wright",	40,	2011,	2019),
("Sandor 'The Hound' Clegane",	"Rory McCann",	38,	2011,	2019),
("Missandei",	"Nathalie Emmanuel",	38,	2013,	2019),
("Bronn",	"Jerome Flynn",	37,	2011,	2019),
("Podrick Payne",	"Daniel Portman",	35,	2012,	2019);

// Top 10 personagens/atores que ficaram mais tempo na série

// Top 10 personagens/atores que mais aparecem na série

// Top 10 personagens/atores que menos aparecem na série

// Qual o total de personagens que apareceram somente 1 vez na série?
