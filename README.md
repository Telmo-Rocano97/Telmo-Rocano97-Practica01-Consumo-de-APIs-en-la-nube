# Telmo-Rocano97-Practica01-Consumo-de-APIs-en-la-nube
Telmo-Rocano97/Practica01-Consumo-de-APIs-en-la-nube

1.	Identificar gráficamente la arquitectura web de la aplicación a desarrollar. 

Captura de Pantalla 2021-04-12 a la(s) 17.41.21![image](https://user-images.githubusercontent.com/62858551/114483744-89a82b00-9bce-11eb-9922-01468285e953.png)

2.	Generar una llave para consumir los servicios web de la API (opcional, depende de la API seleccionada).
2.1.	Primero procedemos a registrarse o ingresar con la cuenta creada
Captura de Pantalla 2021-04-12 a la(s) 17.50.55![image](https://user-images.githubusercontent.com/62858551/114483860-c07e4100-9bce-11eb-8670-5926a35ae3b0.png)

2.2.	Ahora vamos a crear la app “Practica 1”

<img width="403" alt="Captura de Pantalla 2021-04-12 a la(s) 20 36 44" src="https://user-images.githubusercontent.com/62858551/114483931-e1df2d00-9bce-11eb-839d-3d8a0f118eec.png">

2.3.	Procedemos a crearnos las llaves que sean necesarias para poder hacer el uso de la Api

<img width="692" alt="Captura de Pantalla 2021-04-12 a la(s) 20 36 50" src="https://user-images.githubusercontent.com/62858551/114483946-e99ed180-9bce-11eb-8062-c0a9531853e9.png">

3.	Crear un repositorio en GitHub con el nombre “Practica01 – Consumo de APIs en la nube” 
3.1.	Creamos el repositorio con el nombre solicitado 

Captura de Pantalla 2021-04-12 a la(s) 20.36.56![image](https://user-images.githubusercontent.com/62858551/114483969-f4596680-9bce-11eb-8a59-17dd521dccae.png)

8.	Desarrollar una aplicación con HTML + CSS + Javascript + Web Services para buscar información y visualizar toda la información disponible a través de la API.  
<img width="323" alt="Captura de Pantalla 2021-04-12 a la(s) 20 37 00" src="https://user-images.githubusercontent.com/62858551/114483988-fc190b00-9bce-11eb-8011-1a719d96ee6b.png">

10.1.	HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Spotify Web API </title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="estilos.css">
</head>
<body>
    
    <div class="container">        
        <form action="">
            <input type="hidden" id='hidden_token'>
            <div class="col-sm-6 form-group row mt-4 px-0">
                <label for="Gener" class="form-label col-sm-2">Genero:</label>
                <select name="" id="select_genre" class="form-control form-control-sm col-sm-10">
                    <option>Seleccionar</option>                    
                </select>
            </div>
            <div class="col-sm-6 form-group row px-0">
                <label for="Genre" class="form-label col-sm-2">Playlists:</label>
                <select name="" id="select_playlist" class="form-control form-control-sm col-sm-10">
                    <option>Seleccionar</option>                    
                </select>
            </div>                  
            <div class="col-sm-6 row form-group px-0">
                <button type="submit" id="btn_submit" class="btn btn-success col-sm-12">Buscar</button>
            </div>          
        </form>        
        <div class="row">
            <div class="col-sm-6 px-0">
                <div class="list-group song-list">
                    
                </div>                                             
            </div>
            <div class="offset-md-1 col-sm-4" id="song-detail">                
            </div>
        </div>   
    </div>
    <script src="api.js" type="text/javascript"></script>
</body>
</html>

css

.btn.dropdown-toggle  {
    width:150px;
    text-align:left;
}

span.caret {
    position: absolute;
    left: 90%;
    top: 45%;
}

label {
    padding-top:5px;
}

.form-label {
    padding-left:0px !important;
}

img {
    width:140px;
    height:140px;
}

.btn-success {
    background-color: #dfe7d8!important;
}

.btn-success:hover {
    background-color: #df4125!important;
}

img.track {
    border: 1px solid #c73939;
}

body {
    background-color: #ffdd90;
    background-image: url("https://novastan.org/en/wp-content/uploads/sites/8/2021/02/Spotify.png");
  }
  
  
Procedemos a verificar que nuestro proyecto esta funcionando correctamente. 
Captura de Pantalla 2021-04-12 a la(s) 20.37.10![image](https://user-images.githubusercontent.com/62858551/114483998-05a27300-9bcf-11eb-853f-47ad33827b67.png)


CONCLUSIONES:  
•	Identificar arquitecturas web utilizando servicios en la nube
•	Consumir APIs y manipular objetos JSON.  
•	Aplicar diferentes tipos de estilos en el proyecto
•	Creacion de llaves para las API

RECOMENDACIONES:  
•	Aplicar conceptos de interacción humano máquina para el desarrollo de la GUI. 
•	Tener conocimientos previos acerca de las API
•	Consumir las API y obtener sus claves 
•	Diseñer un modelo sobre como funcionaria la aplicación.

