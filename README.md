# Prova de programação

1.	Criar formulário com os seguintes campos: <br>
  a.	Nome (campo texto) <br>
  b.	E-mail (campo e-mail) <br>
  c.	Tipo de documento (dropdown list) <br>
    i.	CPF (deve ser feita a validação do CPF para que não sejam aceitos números inválidos) <br>
    ii.	Passaporte (letras e números – max 15) <br>
    iii.	Identidade (somente números – max 10) <br>
  d.	Número de documento (segundo o tipo de documento selecionado) <br>
2.	Criar um api rest que envie os dados do formulário em formato JSON <br>
  a.	service: "1" <br>
  b.	forms_id_form: "988" <br>
  c.	forms_admins_id_admin: "36" <br>
  d.	content_reg: {"id_form":"988","admins_id_admin":"36","title_form":"prueba (988)","description_form":"prueba","fields_form":[{"type":"TEXT","fieldId":"fieldType1_combo","name":"nombre","value":"[valor_del_campo]","restrict":"NameCharactersAndNumbers"},{"type":"TEXT","fieldId":"fieldType2_combo","name":"email","value":"[valor_del_campo]","restrict":"NameCharactersAndNumbers"},{"type":"TEXT","fieldId":"fieldType3_combo","name":"tipodoc","value":"[valor_del_campo]","restrict":"NameCharactersAndNumbers"},{"type":"TEXT","fieldId":"fieldType4_combo","name":"numdoc","value":"[valor_del_campo]","restrict":"NameCharactersAndNumbers"}],"date_form":"2019-04-29 00:00:00"}
  e.	date_reg: "2019-04-29" <br>
3.	Os dados devem ser enviados a seguinte URL: http://hechoparaliderar.com/SIAF/api/php/proxys/regsproxy.php <br>
