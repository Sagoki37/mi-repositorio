mkdir directorio-ejemplo
echo "¡Alcanzamos por fin la victoria..." > directorio-ejemplo/himnonacional.txt
echo "Pequeñas cosas..." > poema.txt
echo "MIT License..." > LICENSE.md # Reemplaza con el texto completo de la licencia

git add .
git commit -m "Creada estructura inicial del repositorio con archivos y directorios."
git push origin main # o git push origin master, dependiendo de tu rama principal


