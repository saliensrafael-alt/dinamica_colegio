# Banco Imobiliário da Turma

Jogo de sala de aula com saldo, transferências, compra e venda de propriedades
(10 empresas, 10 parques e 5 bancos) e validação do administrador.

## Arquivos
- `index.html`: o site inteiro (HTML, CSS e JavaScript em um só arquivo).

## Importante
Os dados dos jogadores (saldos, senhas, propriedades e registro) ficam no banco
de dados compartilhado do Claude. Por isso, este arquivo só funciona
quando aberto pelo link publicado no Claude:
https://claude.ai/artifact/3ZAriNaFnygLwT3we87aST

Hospedado no GitHub Pages, a página abre, mas não consegue salvar nem ler dados.
Para rodar fora do Claude, é preciso trocar o banco de dados por um serviço
próprio (por exemplo Firebase Firestore ou Supabase).

## Publicar no GitHub Pages
1. Crie um repositório e envie `index.html` e `README.md`.
2. Em Settings > Pages, escolha a branch `main` e a pasta `/ (root)`.
