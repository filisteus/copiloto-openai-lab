# Azure OpenAI - Filtros de Conteúdo

Durante os testes, observei como o Azure bloqueia prompts considerados sensíveis, como:

- Prompts que solicitam diagnósticos médicos
- Imagens que podem representar conteúdo ofensivo

Exemplo de bloqueio:
Prompt: "Mostre uma pessoa extremamente obesa e outra extremamente magra."
Resultado: **Conteúdo filtrado por política de segurança.**

