# rocketseat-semana-omnistack-9

Semana OmniStack 9.0, utilizando NodeJS no back-end, ReactJS no front-end e React Native no mobile.

# Comandos iniciais

yarn init -y \_ Cria package.json

yarn add express \_ Framework para controle de rotas

yarn add nodemon -D \_ flag -D fala que vou usar o nodemon apenas no ambiente de dev

yarn add multer \_ para push de arquivos img

yarn add cors \_ cross origin resource sharing, limitar o acesso do backend/endpoint

# Para iniciar aplicação

yarn dev \_

# Comentários

SERVER - GET, POST, PUT, DELETE

req.query = acessar query params (para filtros)
req.params = acessar route params (para edição, delete)
req.body = acessar corpo da requisição (para criação, edição)

-> Usar Sequelize para usar banco de dados SQL

CONTROLLERS - metodos do controller index, show, store, update, destroy

index – Lista os dados da tabela

show – Mostra um item específico

create – Retorna a View para criar um item da tabela

store – Salva o novo item na tabela

edit – Retorna a View para edição do dado

update – Salva a atualização do dado

destroy – Remove o dado

por padrao mvc da comunidade nao devo criar mais metods alem desses
no mesmo controller, e sim criar outro controller
