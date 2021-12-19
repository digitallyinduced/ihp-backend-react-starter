# IHP React Starter

## Usage

On first start install the npm dependencies:

```bash
npm install
```

Set the `BACKEND_URL` in `.env` to your project's url:

```bash
# .env
BACKEND_URL="https://REPLACE ME.di1337.com"
```

After this you can start the web server and esbuild watcher:

```bash
npm run start
```

## Bundling for Production

```bash
export BACKEND_URL="https://REPLACE ME.di1337.com"
npm run build
```