## FastAPI + NextJS14 + GoogleAuth 🚀

Inscreva-se no Google Console, configure o OAuth e obtenha seu arquivo JSON de credenciais.

Adicione na URI de redirecionamento do Google: http://localhost:3000/api/google/auth e também a URL do seu domínio no Vercel.

Renomeie o arquivo para `client.json` e coloque-o no diretório `/api`. Agora você pode remover o arquivo `placeholder-client-secret.json`.

### Executar o Projeto Localmente 🏃‍♂️

Primeiro, execute o servidor de desenvolvimento:

```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev
```

Abra [http://localhost:3000](http://localhost:3000) no seu navegador para ver o resultado.

Nota: -> Se você enfrentar qualquer problema ao executar o exemplo, sinta-se à vontade para criar uma issue ou enviar um email/DM para mim.

Você pode começar a editar a página modificando `app/page.tsx`. A página é atualizada automaticamente conforme você edita o arquivo.

Este projeto usa [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) para otimizar e carregar automaticamente a Inter, uma fonte personalizada do Google.

## Saiba Mais 📚

Para saber mais sobre Next.js, dê uma olhada nos seguintes recursos:

- [Documentação do Next.js](https://nextjs.org/docs) - aprenda sobre os recursos e API do Next.js.
- [Aprenda Next.js](https://nextjs.org/learn) - um tutorial interativo de Next.js.

Você pode conferir o [repositório do Next.js no GitHub](https://github.com/vercel/next.js/) - seu feedback e contribuições são bem-vindos!

## Deploy no Vercel 🚀

A maneira mais fácil de fazer o deploy do seu app Next.js é usar a [Plataforma Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) dos criadores do Next.js.

Confira nossa [documentação de deployment do Next.js](https://nextjs.org/docs/deployment) para mais detalhes.
