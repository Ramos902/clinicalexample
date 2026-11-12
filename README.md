# clinicalexample

Landing page para clínica médica em arquivo único (`index.html`), com catálogo de especialidades e exames com busca e filtros em tempo real via Vanilla JS.

## Estrutura

- **Arquivo único**: HTML, CSS e JavaScript puros, sem bundlers, frameworks ou dependências de build.
- **Catálogo de serviços**: busca em tempo real (ignora acentos) e filtro por categoria (consultas, exames, procedimentos e check-ups).
- **Horário de funcionamento**: script em Vanilla JS calcula automaticamente se a recepção está aberta ou fechada com base no fuso horário de São Paulo.
- **Links para WhatsApp**: cada serviço gera um link direto para a recepção com mensagem já contextualizada.

## Como rodar

Abra o arquivo `index.html` diretamente no navegador ou inicie um servidor local:

```bash
python3 -m http.server 8000
# ou
npx serve .
```

## Como personalizar

Toda a parametrização é feita diretamente no script ao final do `index.html`:

- `CLINICA_CONFIG`: nome da clínica, telefones, WhatsApp, horários, endereço, e-mail e responsável técnico (CRM/RQE).
- `catalogo`: lista de serviços com título, categoria, descrição, orientação de preparo e palavras-chave para a busca.
