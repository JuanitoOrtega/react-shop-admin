Inside that directory, you can run several commands:

  npm run dev
    Starts the development server.

  npm run build
    Builds the app for production.

  npm start
    Runs the built app in production mode.

We suggest that you begin by typing:

  cd react-shop-admin
  npm run dev

/////////////////
# Instalación de paquetes
npm i eslint-config-prettier eslint-plugin-jsx-a11y eslint-plugin-prettier prettier -D

# Buscar posibles errores
npm run lint

# Reparar errores con lint:fix
npm run lint:fix

# Para trabajar con tailwind y sus componentes
npm i tailwindcss postcss autoprefixer

# Para añadir configuraciones de tailwind
npx tailwindcss init -p

# Instalamos librería para hero tailwind
npm install @heroicons/react
npm install @headlessui/react

# Instalamos librerías para manejar el inicio de sesión
npm install js-cookie
npm install axios

# Instalamos librerías para mostrar gráficos
npm install chart.js react-chartjs-2

# Instalamos librería para trabajar con formularios
npm install @tailwindcss/forms

/// User admin
admin@mail.com
admin123

// Deploy
# Lo que necesitamos hacer antes para desplegar nuestra aplicación
npm run build

# Reparar errores y/0 warning
npm run lint:fix