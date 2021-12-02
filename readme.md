# Autoscaling

## Aplicación de buenas prácticas

## Generación de pruebas de stress

# Agrega paquetes extras
sudo amazon-linux-extras install epel -y
 
# Instala stress
sudo yum install stress -y
 
# Comienza el stress
sudo stress --cpu 1
