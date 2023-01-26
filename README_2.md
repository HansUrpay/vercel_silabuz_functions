# CREAR PROYECTO CON NEXT (FRAMEWORK DE REACT) Y DEPLOY EN VERCEL 
- instalar vercel en global `npm i -g vercel`
- instalar `npx create-next-app@latest --typescrypt`
    en las preguntas responder:
    1. usar typescript en este proyecto? YES
    2. usar ESLINT? YES
    3. usar exprimental `app/` directory? NO
    4. what import alias? dar ENTER

- guardar en repo de github

- ejecutar `vercel login`
    seleccionar login con github

- ejecutar `vercel deploy`
    responder:
    1. set up and deploy en esta ruta? YES
    2. Which scope do you want to deploy to? - hansurpay (ENTER)
    3. Link to existing project? NO (porque es nuevo)
    4. What’s your project’s name? YES
    5. In which directory is your code located? YES (en la raiz)
    6. Want to modify these settings? NO
