/*

Locação -> Cliente tem que fazer o seu registro Procuro o filme e alugo.
	  1      *        *     1         
|Cliente |  ----- /Alugar\ ----- | Filme | 
-Nome				  -Descrição
-Cpf				  -Gênero
-Telefone			  -Data Lançamento
-End.                             -Valor

- = Private
+ = publico
-------------------------------

<<entity>>
 Cliente
Persistente
------------
-Id_Cliente# int;
-Nome Str;
-Telefone Str;
-Cpf# Str;
-end Str;
------------
+Manter();


<<entity>>
 Filme/DvD
Persistente
------------
-Id_filme# int;
-Cod# int;
-Desc Str;
-Gênero bol;
-Data Lançamento Str;
-PRAZO int;
-valor float;
-status bol;
--------------
+Manter(); 


<<entity>>
 Alugar
Persistente
-------------------
-Id_alu#-Primary int
-Cod_alugar int;
-Id_cliente#-ES int;
-id_filme#-ES int;
-DataLocada date;
-------------------
+Manter();
 */
