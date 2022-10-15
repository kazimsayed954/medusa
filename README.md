1. **Create a new  project**

```zsh
clone this repo
```

2. **Install dependencies**

```zsh
  cd my-medusa-storefront
  yarn
```

3. **Link to your backend**

In the folder `my-medusa-storefront` you should have a `.env.template` file with the following content:

```shell
GATSBY_MEDUSA_BACKEND_URL=http://localhost:9000
```

Before you can start developing your site you first need to copy this file into a new file named `.env.development`.

```zsh
mv .env.template .env.development
```

Per default your Medusa server should be running on `localhost:9000`, but if you have changed this you will then need to replace `GATSBY_MEDUSA_BACKEND_URL` with the URL of your Medusa server.

```zsh
GATSBY_MEDUSA_BACKEND_URL=<link to your server>
```

4. **Start development**

You should now be able to start developing your site.

```zsh
yarn start
```

