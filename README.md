Tabela de dados com 7 colunas e 40 linhas baseado na obra de Game of Thrones.

CREATE DATABASE gameofthrones;

USE gameofthrones;

CREATE TABLE characters ( 
id int not null auto_increment primary key,
gender varchar(10), 
name_char varchar(200), 
name_actor varchar(200), 
episodes int not null, 
first_ap int not null, 
last_ap int not null);

INSERT INTO characters (gender, name_char, name_actor, episodes, first_ap, last_ap) VALUES
("M","Tyrion Lannister", "Peter Dinklage", 67, 2011, 2019), 
("F", "Cersei Lannister", "Lena Headey", 62, 2011, 2019), 
("F", "Daenerys Targaryen", "Emilia Clarke", 62, 2011, 2019), 
("M", "Jon Snow", "Kit Harington", 62, 2011, 2019), 
("F", "Sansa Stark", "Sophie Turner", 59, 2011, 2019), 
("F", "Arya Stark", "Maisie Williams", 59, 2011, 2019), 
("M", "Jaime Lannister", "Nikolaj Coster-Waldau", 55, 2011, 2019), 
("M", "Jorah Mormont", "Iain Glen", 52, 2011, 2019), 
("M", "Samwell Tarly", "John Bradley", 48, 2011, 2019), 
("M", "Theon Greyjoy", "Alfie Allen", 47, 2011, 2019), 
("M", "Lord Varys", "Conleth Hill", 46, 2011, 2019), 
("M", "Davos Seaworth", "Liam Cunningham", 42, 2012, 2019), 
("F", "Brienne of Tarth", "Gwendoline Christie", 42, 2012, 2019), 
("M", "Petyr 'Littlefinger' Baelish", "Aidan Gillen", 41, 2011, 2017), 
("M", "Bran Stark Isaac", "Hempstead Wright", 40, 2011, 2019), 
("M", "Sandor 'The Hound' Clegane", "Rory McCann", 38, 2011, 2019), 
("F", "Missandei", "Nathalie Emmanuel", 38, 2013, 2019), 
("M", "Bronn", "Jerome Flynn", 37, 2011, 2019), 
("M", "Podrick Payne", "Daniel Portman", 35, 2012, 2019),
("M", "Grey Worm",	"Jacob Anderson",	34,	2013,	2019),
("M", "Eddison Tollett",	"Ben Crompton",	34,	2012,	2019),
("M", "Tormund Giantsbane",	"Kristofer Hivju",	33,	2013,	2019),
("M", "Grand Maester Pycelle",	"Julian Glover",	31,	2011,	2016),
("F", "Melisandre",	"Carice van Houten", 29,	2012,	2019),
("M", "Tywin Lannister",	"Charles Dance",	27,	2011,	2015),
("F", "Gilly",	"Hannah Murray",	27,	2012,	2019),
("F", "Margaery Tyrell",	"Natalie Dormer",	26,	2012,	2016),
("M", "Joffrey Baratheon",	"Jack Gleeson",	26,	2011,	2014),
("F", "Catelyn Stark",	"Michelle Fairley",	26,	2011,	2016),
("M", "Barristan Selmy",	"Ian McElhinney",	25,	2011,	2015),
("M", "Stannis Baratheon",	"Stephen Dillane",	24,	2012,	2015),
("F", "Gendry",	"Joe Dempsie",	24,	2011,	2019),
("M", "Hodor",	"Kristian Nairn",	23,	2011,	2016),
("M", "Qyburn",	"Anton Lesser",	22,	2013,	2019),
("M", "Grenn",	"Mark Stanley",	22,	2011,	2014),
("M", "Robb Stark",	"Richard Madden",	22,	2011,	2016),
("M", "Loras Tyrell",	"Finn Jones",	21,	2011,	2016),
("F", "Shae",	"Sibel Kekilli",	20,	2011,	2014),
("M", "Ramsay Bolton",	"Iwan Rheon",	20,	2013,	2016),
("M", "Roose Bolton",	"Michael McElhatton",	20,	2012,	2016);

SELECT * FROM characters;


// Top 5 personagens/atores que ficaram mais tempo na série

// Top 5 personagens/atores que mais aparecem na série

// Top 5 personagens/atores que menos aparecem na série

// Top 5 personagens/atores mulheres mais que aparecem na série

// Top 5 personagens/atores homens que mais aparecem na série
