# Angular avançado com module api tailwind css

- ng new <nome project> --no-standalone (cria o projeto modular)
- npm install --save tailwindcss@3.4.17 postcss autoprefixer (adiciona o tailwind)
- npx tailwindcss init (inicia o tailwind no projeto)
- npm install --save-dev json-server (pacote que cria uma API REST fake a partir de um arquivo JSON, permitindo que você simule um back-end e faça testes sem precisar de um servidor real)
- ng g m <nome module> --routing (criar módulo)
- ng g c <pasta/nome component> (criar componente)
- ng g s <pasta/nome service> (criar service)
- ng g class <pasta/nome class>

(input pesquisando sem digitar o nome completo)
1º npm remove json-server
2º npm install --save-dev json-server@0.17.4

- npm install --save angular-oauth2-oidc@19.0.0 (permite usar o (OAuth) console do google cloud)