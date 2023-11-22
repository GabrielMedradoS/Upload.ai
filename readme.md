## nlw upload.ai

<p align='center'>
<b height="50%" width="50%">upload.ai</b>
</p>

<p align="center">
    <img alt="Platform" src="https://img.shields.io/static/v1?label=Platform&message=PC&color=030712&labelColor=262626">
    <a href="">
        <img src="https://img.shields.io/badge/Nlw-Upload.ai-030712?&labelColor=262626"></img>
    </a>
    <img alt="Repository size" src="https://img.shields.io/github/repo-size/GabrielMedradoS/Upload.ai?color=030712&labelColor=262626">
    <a href="">
        <img alt="License" src="https://img.shields.io/static/v1?label=License&message=MIT&color=030712&labelColor=262626">
    </a>
</p>

<p align="center">
    <a href="#projeto-">Projeto</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#tecnologias-">Tecnologias</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#layout-">Layout</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#licença-%EF%B8%8F">Licença</a>
</p>

### Layout 🚧

#### Screenshot:

<div align='center'>
<img src=".github/nlw upload.ai.png" alt="widget" width="100%">
</div>

## Projeto 💻

- Projeto consiste em criar um serviço web usando uma ai

## Rodar o projeto 🚴🏻‍♂️

#### On your machine:

##### Front-end

<details>
    <summary>Dependencies</summary>

```json
{
  "name": "upload-ai-web",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "tsc && vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "@ffmpeg/ffmpeg": "^0.12.7",
    "@ffmpeg/util": "^0.12.1",
    "@radix-ui/react-icons": "^1.3.0",
    "@radix-ui/react-label": "^2.0.2",
    "@radix-ui/react-select": "^2.0.0",
    "@radix-ui/react-separator": "^1.0.3",
    "@radix-ui/react-slider": "^1.1.2",
    "@radix-ui/react-slot": "^1.0.2",
    "axios": "^1.6.2",
    "class-variance-authority": "^0.7.0",
    "clsx": "^2.0.0",
    "lucide-react": "^0.292.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "tailwind-merge": "^2.0.0",
    "tailwindcss-animate": "^1.0.7"
  },
  "devDependencies": {
    "@types/node": "^20.9.0",
    "@types/react": "^18.2.15",
    "@types/react-dom": "^18.2.7",
    "@typescript-eslint/eslint-plugin": "^6.0.0",
    "@typescript-eslint/parser": "^6.0.0",
    "@vitejs/plugin-react": "^4.0.3",
    "autoprefixer": "^10.4.16",
    "eslint": "^8.45.0",
    "eslint-plugin-react-hooks": "^4.6.0",
    "eslint-plugin-react-refresh": "^0.4.3",
    "postcss": "^8.4.31",
    "tailwindcss": "^3.3.5",
    "typescript": "^5.0.2",
    "vite": "^4.4.5"
  }
}
```

</details>

```bash
# Clone the repository
$ git clone https://github.com/GabrielMedradoS/Upload.ai.git

# Access the project folder at the command prompt
$ cd upload-ai-web

# Install the dependencies
$ npm install

# Run the script "start"
$ npm run dev

# The project will start at the door: 5173 - access http://localhost:5173
```

##### Back-end

<details>
    <summary>Dependencies</summary>

```json
{
  "name": "upload-ai-server",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "dev": "tsx watch src/server.ts"
  },
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "@types/node": "^20.9.2",
    "dotenv": "^16.3.1",
    "prisma": "^5.6.0",
    "tsx": "^4.1.3",
    "typescript": "^5.2.2"
  },
  "dependencies": {
    "@fastify/cors": "^8.4.1",
    "@fastify/multipart": "^8.0.0",
    "@prisma/client": "^5.6.0",
    "ai": "^2.2.25",
    "fastify": "^4.24.3",
    "openai": "^4.19.1",
    "zod": "^3.22.4"
  }
}
```

</details>

```bash
# Clone the repository
$ git clone https://github.com/GabrielMedradoS/Upload.ai.git

# Access the project folder at the command prompt
$ cd upload-ai-server

# Install the dependencies
$ npm install

# Run the script "start"
$ npm run dev

# The project will start at the door: 3333 - access http://localhost:3333
```

## Tecnologias 🛠

<div>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5"  height="30" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-plain-wordmark.svg" alt="css3"  height="30" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" height="30" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" height="30" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg"
  alt="typescript" height="30" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" alt="tailwind" height="30" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
</div>

#### documentation 📜

_`Aula 1 :`_

- [Vite | documentation](https://vitejs.dev/)
- [Shadcn/ui | documentation](https://ui.shadcn.com/docs/installation/vite)
- [Tailwind](https://tailwindcss.com/docs/installation/using-postcss)

_`Aula 2 :`_

- [Node | documentation](https://nodejs.org/en/docs)
- [Fastify | documentation](https://fastify.dev/docs/latest/Guides/Getting-Started/)
- [Prisma | documentation](https://www.prisma.io/docs/getting-started)
- [Cloudflare | documentation](https://developers.cloudflare.com/r2/get-started/)
- [Amazon S3 | documentation](https://docs.aws.amazon.com/sdk-for-javascript/v3/developer-guide/getting-started-nodejs.html)
- [Fastify-multipart](https://github.com/fastify/fastify-multipart)
- [Express-multer](https://expressjs.com/en/resources/middleware/multer.html)
- [Zod | documentation](https://www.npmjs.com/package/zod)

_`Aula 3 :`_

- [ffmpegwasm | documentation](https://ffmpegwasm.netlify.app/docs/getting-started/installation)

## Licença ⚖️

This project is under the MIT license. See the archive [LICENSE](https://github.com/GabrielMedradoS/Upload.ai/blob/master/License) for more details.

## Autor ✍🏾

| <a href="https://github.com/gabrielmedrados/"><img src="https://user-images.githubusercontent.com/73303001/126536001-655e3cbd-facd-4de1-992f-b8d9d3656ace.jpg" width="100" alt="perfil"/><br>
| :-------------------------: |
| <a href="https://github.com/gabrielmedrados/"> Gabriel Medrado |</a> |

[![Linkedin Badge](https://img.shields.io/badge/-GabrielMedrado-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-medrado-de-souza-9a30b3206/)
[![Gmail Badge](https://img.shields.io/badge/-gabriel.medradoo@hotmail.com-1769ff?style=flat-square&logo=Gmail&logoColor=white)](mailto:gabriel.medradoo@hotmail.com)
