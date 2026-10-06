# Playbook do Núcleo de Experiência

Este repositório aloja o playbook do Núcleo de Experiência da TIS, publicado pelo GitHub Pages em https://tis-experience.github.io/playbook/.

Trata-se da apresentação original que esteve disponível em https://tis-experience.github.io/nucleo-de-experiencia-nos-projectos/ até Outubro de 2026. O repositório anterior deixou de a servir e o endereço actual passa a ser o indicado acima.

## Execução local

```bash
npm install
npm run dev
```

Para gerar a versão de produção:

```bash
npm run build
```

O resultado fica na pasta `dist`, com o `index.html` gerado a partir de `index.dev.html` pelo script `scripts/postbuild.mjs`.
