# Clínica VitaSaúde - Landing Page Institucional

Landing Page institucional e catálogo interativo para clínicas médicas e de diagnóstico, desenvolvida em arquivo único (`index.html`) com foco em performance, acessibilidade e design limpo.

## 🚀 Tecnologias

- **HTML5 Semântico**: Estrutura acessível com conformidade a leitores de tela e padrões W3C.
- **CSS Moderno**: Variáveis CSS (Custom Properties), tipografia Public Sans e design mobile-first responsivo.
- **Vanilla JavaScript**: Filtro de busca em tempo real com normalização de acentos, manipulação dinâmica do catálogo e cálculo de status de funcionamento (aberto/fechado).

## 🩺 Funcionalidades

- **Indicador de Horário em Tempo Real**: Verifica automaticamente o fuso horário de São Paulo e informa se a recepção está aberta ou o próximo horário de abertura.
- **Guia Interativo de Consultas & Exames**:
  - Busca instantânea por termo, sintomas ou especialidade.
  - Filtros por categoria (Consultas Médicas, Exames Diagnósticos, Procedimentos, Check-ups).
  - Indicador de preparo e tags com orientações práticas.
  - Link direto para atendimento no WhatsApp com mensagem pré-preenchida.
- **Corpo Clínico**: Apresentação dos médicos especialistas com dados de CRM/RQE e dias de atendimento.
- **Localização & Mapa**: Integração com Google Maps e dados de transporte/estacionamento.
- **Compliance Médico**: Rodapé com dados de direção técnica, registro CRM/RQE e alvará sanitário.
- **Botão Flutuante de WhatsApp**: Acesso rápido para agendamentos.

## ⚙️ Como Customizar

Todos os dados da clínica (nome, telefone, WhatsApp, endereço, horário e catálogo) podem ser facilmente editados no objeto `CLINICA_CONFIG` e no array `catalogo` ao final de `index.html`.

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
