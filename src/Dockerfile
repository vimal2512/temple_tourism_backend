FROM node:20

WORKDIR /app

COPY . .

RUN corepack enable && corepack prepare pnpm@latest --activate
RUN pnpm install

EXPOSE 5000

CMD ["pnpm", "start"]
