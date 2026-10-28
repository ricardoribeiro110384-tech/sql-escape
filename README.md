# SQL Escape — O laboratório bloqueado

Jogo educativo em português com cinco fases de investigação usando SQL real (SQLite via sql.js).

## Conteúdos

SELECT, WHERE, ORDER BY, CREATE TABLE e ALTER TABLE. Inclui pistas, dicas, explicações de erros e progresso salvo no navegador.

## Executar

Sirva esta pasta por HTTP, por exemplo com `python -m http.server 8000`, e abra `http://localhost:8000`. Não exige instalação de dependências. Mantenha todos os arquivos juntos, incluindo `sql-wasm.wasm`.

## GitHub Pages

Em Settings → Pages, selecione Deploy from a branch, branch main e pasta / (root), e salve.

## Arquivos

- index.html: interface
- style.css: aparência responsiva
- game.js: fases e lógica
- sql-wasm.js e sql-wasm.wasm: sql.js 1.15.2
- SQLJS-LICENSE.txt: licença da dependência

Os dados são fictícios e pertencem à narrativa. O progresso é local ao navegador.
