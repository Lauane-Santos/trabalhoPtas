# iniciando projeto
npm init
yarn add sequelize express pg
yarn add sequelize-cli nodemon --dev

# Iniciando projeto
yarn sequelize init

# Adicionado modelo
yarn sequelize-cli model:create --name usuario --attributes nome:string,usuario:string,senha:string
Alterar configurações do banco

# Persistir modelo no banco
yarn sequelize-cli db:create
yarn sequelize-cli db:migrate

# Adicionar dataDefault
defaultValue: Sequelize.fn('NOW')

# Criar um seed
yarn sequelize-cli seed:generate --name adicionar-usarios

# Configurações do git Local
git init
git config user.name "Lauane-Santos"
git config user.email "lauane.o.santos@gmail.com"  

# GitIgnore
.gitignore

git add . 
git commit -m "Mensagem inicial"
git remote add origin https://github.com/Lauane-Santos/trabalhoPtas.git

# Criar Token de acesso caso não tenha

# Enviar código
git push origin main -f

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
