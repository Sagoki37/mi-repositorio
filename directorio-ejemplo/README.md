# Rama para la estructura inicial
git checkout -b estructura-inicial

# Agrega los archivos y haz commit
git add .
git commit -m "Creada estructura inicial del repositorio con archivos y directorios"
git push -u origin estructura-inicial

# Merge a main
git checkout main
git merge estructura-inicial
git push

git checkout -b contenido-mejorado

git add .
git commit -m "Actualizado el archivo poema.txt con un poema corto"
git push -u origin contenido-mejorado

# Merge a main
git checkout main
git merge contenido-mejorado
git push

git commit -m "Añadido archivo himnonacional.txt con tres estrofas del himno nacional."
git commit -m "Creada estructura inicial del repositorio con archivos y directorios."
git commit -m "Actualizado el archivo poema.txt con un poema corto."

git log --oneline
