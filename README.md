# 🌱 Horta & Mesa — Mãos Solidárias

Interface mobile-first do sistema de controle de estoque perecível (FIFO) e check-in de famílias beneficiárias da Associação Comunitária Mãos Solidárias (ODS 2 – Fome Zero).

Arquivo único, sem build: abra `index.html` no navegador.

## Funcionalidades
- Painel do mutirão (famílias atendidas e alertas de validade)
- Check-in por CPF com máscara e bloqueio de nova retirada em menos de 7 dias
- Cadastro de lotes com prioridade FIFO por validade (entrada sanitizada contra XSS)
- Acessibilidade: alto contraste, alvos de toque ≥ 48px, foco visível

## Dados de demonstração
CPFs de teste: `123.456.789-00` (liberado) e `987.654.321-99` (bloqueado). Os dados ficam em memória; não há backend nesta versão.

## Publicar no GitHub Pages
Settings → Pages → Branch `main` / pasta `/ (root)`.
