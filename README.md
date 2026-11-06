# Minha Grade BCC

App para acompanhar a matriz sugerida do **Bacharelado em Ciência da Computação da UFABC (PPC 2023)**, com o BC&T incluído. Toque numa matéria para marcar: cursando → aprovada → limpa.

- Funciona offline e pode ser instalado no celular (PWA).
- As marcações ficam salvas no próprio aparelho (`localStorage`).
- Para passar para outro aparelho, use **Backup / trocar de aparelho**.

## Estrutura

```
index.html      a página (HTML + CSS + JavaScript)
manifest.json   nome, ícone e cores do app instalado
sw.js           service worker: guarda os arquivos para funcionar offline
icons/          ícones do app
```

## Rodar no computador

```bash
python3 -m http.server 8000
# abra http://localhost:8000
```

Fonte da matriz: Projeto Pedagógico do BCC UFABC 2023. Confira sempre no SIGAA.
