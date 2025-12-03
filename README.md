# 1. Crea la carpeta y entra
mkdir sunny-beach-brochure
cd sunny-beach-brochure

# 2. Crea los archivos (copia el contenido de los artifacts)
# - Copia el código HTML y guárdalo como index.html
# - Copia el README.md y guárdalo como README.md

# 3. Inicializa Git
git init
git add .
git commit -m "Initial commit: Sunny Beach brochure"

# 4. Conecta con GitHub (primero crea el repo en GitHub.com)
git remote add origin https://github.com/TU_USUARIO/sunny-beach-brochure.git
git branch -M main
git push -u origin main
