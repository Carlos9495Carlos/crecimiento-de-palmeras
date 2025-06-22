Para que el código tenga sentido, necesita descargar el archivo .csv "palmeras definitivo" y leerlo con "read_delim" tal que así:
palmeras_definitivo <- read_delim("dirección del archivo",
                       delim = ";", 
                       locale = locale(encoding = "ISO-8859-1"))
