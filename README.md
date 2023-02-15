Tabela de dados com 7 colunas e 40 linhas baseado na obra de Game of Throne.


<bold> 1. Top 5 personagens/atores que ficaram mais tempo na série </bold><br/>
SELECT id, gender, name_char, name_actor, episodes, first_ap, last_ap FROM characters WHERE last_ap - first_ap ORDER BY id ASC LIMIT 5;
![image](https://user-images.githubusercontent.com/112404942/218892604-9bf543a4-4a11-4805-af34-1ff4caec1a7b.png)




<bold> 2. Top 5 personagens/atores que mais aparecem na série </bold><br/>
SELECT id, gender, name_char, name_actor, episodes, first_ap, last_ap FROM characters WHERE id ORDER BY id ASC LIMIT 5;
![Top5 personagens - Todos](https://user-images.githubusercontent.com/112404942/218888209-3e9a703c-af52-48e2-ad23-98675f30281c.png)


<bold> 3. Top 5 personagens/atores que menos aparecem na série </bold><br/>
SELECT id, gender, name_char, name_actor, episodes, first_ap, last_ap FROM characters WHERE id ORDER BY id DESC LIMIT 5;
![Top5 personagens - Menos aparecem](https://user-images.githubusercontent.com/112404942/218890344-6b7bc7b9-8fe3-436d-a83c-fd7772ac2478.png)




<bold> 4. Top 5 personagens/atores mulheres mais que aparecem na série </bold><br/>
SELECT id, gender, name_char, name_actor, episodes, first_ap, last_ap FROM characters WHERE gender = "F" ORDER BY id ASC LIMIT 5;
![Top5 personagens - Mulheres](https://user-images.githubusercontent.com/112404942/218888950-8a22ba8c-0436-4265-bccb-2e10e5eabd5a.png)



<bold> 5. Top 5 personagens/atores homens que mais aparecem na série </bold><br/>
SELECT id, gender, name_char, name_actor, episodes, first_ap, last_ap FROM characters WHERE gender = "M" ORDER BY id ASC LIMIT 5;
![Top5 personagens - Homens](https://user-images.githubusercontent.com/112404942/218888972-8c4b87b1-67ca-4683-954e-1ca2479ae63a.png)
