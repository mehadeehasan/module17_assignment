npx create-next-app@latest

npm install prisma --save-dev

npx prisma init --datasource-provider mysql

.env file

--DATABASE_URL="mysql://root:@localhost:3306/ostad_prisma"

npx prisma migrate dev

