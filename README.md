# captor2 — Ambiente de Desenvolvimento

Clone do [Captor](https://github.com/cafreitas/captor) para testes de UX/UI.

## Stack

- **Frontend:** HTML/CSS/JS single-file (`index.html` + `proposta.html`)
- **Backend:** Supabase (mesmo banco de produção)
- **Hosting:** GitHub Pages → `https://cafreitas.github.io/captor2/`

## Diferenças em relação à produção

- Faixa laranja no topo indicando ambiente DEV
- Título da aba: `Captor DEV`
- URL de reset de senha aponta para `captor2`

## Deploy

```bash
python3 deploy_captor2.py
```

## Workflow recomendado

1. Editar `index.html` localmente
2. `python3 deploy_captor2.py` → testa em captor2
3. Aprovado → porta para produção com `deploy_captor.py`

## Empresa

Quantic © 2026
