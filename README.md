
<!DOCTYPE html>
<html>
<head>
  <title>Fotoboat</title>
</head>

<body>

 Hola y bienvenido

<link rel="stylesheet" href="assets/css/pyscript.css" />
<script defer src="assets/js/pyscript.js"></script>

<div id="micontenido">
 
    <py-script>

from PIL import Image

y = 1

while y ==1:
  x = input('Escribe aquí el nombre de la foto:')

  if x == 'barco':
    im = Image.open('barco.jpeg')
  elif x == 'campo':
    im = Image.open('campo.jpeg')
  elif x == 'gay':
    im = Image.open('gay.jpeg')
  elif x == 'mago':
    im = Image.open('mago.jpeg')
  else:
    print('No se ha encontrado ningun resultado')
  
  im.show()

 
     </py-script> 
 
</div>

</body>
</html> 
