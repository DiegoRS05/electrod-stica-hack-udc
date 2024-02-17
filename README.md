Hola, esto es electrodistica, una web que te simplificará esos complicados archivos csv y te ayudará a entender bases de datos simples 
(básicamente, información sobre consumo eléctrico). Para el uso de esta web, se debe instalar el directorio de paginaweb
con todo lo que tiene dentro, y debes arrastrar ese directorio, por ejemplo, a visual studio code, donde deberás ejecutar el archivo app.py.
Una vez hayas hecho eso, o bien te sitúas en el directorio de templates y abres index.html, o bien puedes entrar en tu buscador y escribe en la zona de URL
lo siguiente: 'localhost:5000' , sin las comillas simples. Cualquiera de ambos caminos te llevará a un entorno creado por flask, donde podrás interactuar con la web.
¡IMPORTANTE! -> El arhivo que se debe subir a la web, una vez hosteada debe ser de tipo csv, y debe tener los nombres de las columnas EXATAMENTE como se enseña 
a continuación: "Código universal de punto de suministro,Fecha,Hora,Consumo,Método de obtención,datetime", siendo así 6 columnas diferentes. Para facilitar el testeo del software, se facilita un archivo ubicado en el directorio uploads, cuyo nombre es electrodatos.csv. Es una base de datos con las características pedidas.
El código está bajo licencia GPL 3.0.
Este código fue pensado, programado e implementado por Martin Hernandez, Daniel Quintero y yo, Diego Rodriguez. 
Agradecimientos al grupo de Python Coruña, en especial a Martín y a Roberto por habernos ayudado en momentos difíciles y al grupo GPUL por organizar el evento!
