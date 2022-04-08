## KAFKA

Repositorio donde implemento una aplicación de comunicación usando Kafka.
Este ejercicio está basado en la [siguiente implementación](https://github.com/RubenMartinezParrasBosonit/Kafka) de mi compañero [Rubén](https://github.com/RubenMartinezParrasBosonit). 

### Manual de uso 
Para lanzar y usar este servicio, se recomienda seguir el siguiente [tutorial](https://github.com/RubenMartinezParrasBosonit/Kafka/blob/main/tutorial.txt) en el cual se configuran los servidores.   

Respecto al uso de esta aplicación, es interesante dividir en dos aplicaciones, siendo una de ellas para Listener y la otra Producer.  
De esta forma evitamos crear una única aplicación la cual escucha y envía mensajes (no tiene demasiada lógica usar mensajería asíncrona para una aplicación unitaria).