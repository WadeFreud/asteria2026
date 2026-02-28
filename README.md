# Asteria 2026
Desarrollo de un cohete de 3000 metros recuperable con despliegue de 2 cargas utiles de 1 kg en su apogeo. Asi como todos los subsistemas necesarios para su desarrollo, lanzamiento, rastreo y pronta recuperacion.
# Electronica
 ## Avionica de vuelo: 
 Rastreo continuo del cohete, transmitiendo datos crudos como aceleracion, barometro, magnetometro y gps con un modulo   lora de 433 MHz antena omnidireccional protocolo meshtatic para facilitar rastreo en caso de falla de cargas pirotecnicas. Activacion      de cargas pirotecnica de cargas utiles a 3000 metros, paracaidas secundario a 1000 metros y paracaidas primario a 300 metros.
  ## Estacion Terrena: 
  Usando un modulo de recepcion Lora 433Mhz recepcion direccional de largo alcance y una interfaz grafica que muestre      los datos procesados en el formato que requiere la competencia y graficas estaticas con limites fijos de los limites de la mision con      margen del 30%.
 ## Banco de pruebas:
 El banco de pruebas esta conformado por modulos de cuantificacion de carga, presion y probablemente temperatura,         guardando los datos en una memoria micro SD y con la capacidad de activar la carga pirotecnica del motor, asi como transmitir datos a      una distancia de 1000 metros de manera inalambrica por facilidad de instalacion y logistica. Creacion de interfaz grafica asi como         estacion terrena con boton y medidas de seguridad para evitar activacion accidental, incorporando led de bateria baja, led de encendido,   led de conexion checando cada 3 segundos y led de activacion confirmando ignicion. Baterias tienen que tener energia para 4 Horas de       encendido en espera.
# Aeroestructuras: 
Creacion y validacion de un fuselaje optimizado para mach 1.1
# Propulsion:
Creacion y pruebas de propelentes solidos de KNO3 y NH4NO3
