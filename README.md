# Projeto resília - Visualizando a situação 
O quarto projeto em grupo do módulo IIII da RESÍLIA EDUCAÇÃO.
Que consiste em montar um dashboard com base no conjunto de dados
escolhidos pelo grupo, a fim de realizar uma
apresentação com a exploração dos dados.   



## 🔎 **Perguntas elaboradas com base no banco de dados:**  


### 1) Top 5 personagens/atores que ficaram mais tempo na série  

    comando:
        SELECT id, gender, name_char, name_actor, episodes, first_ap, last_ap FROM characters WHERE last_ap - first_ap ORDER BY id ASC LIMIT 5;  
        
    
    
  <img alt="tabela alunos" src="https://raw.githubusercontent.com/jonathanfalcao/Game-of-Thrones-MySQL-M4/main/MySQL/img.dashboard/1.jpg">  
  
  
  
  ***

