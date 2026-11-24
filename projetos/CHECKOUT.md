# Checkout-Payzen — Integração experimental de pagamentos

**Categoria:** Checkout / integração com gateway  
**Visibilidade do código:** Privado

## Objetivo
Investigar a experiência de pagamento e a atualização dinâmica de configurações de um formulário PayZen Krypton em ambiente de teste.

## Funcionalidades documentadas
- Formulário de pagamento com chave pública e **formToken** configuráveis.
- Troca de **formToken** em tempo real, sem reinjetar o script, via `KR.setFormConfig()`.
- Feedback de transação: sucesso ou erro.
- Fluxos de cartões de crédito e débito com diversas bandeiras suportadas pela integração.

## Tecnologias
- **HTML, CSS e JavaScript.**
- **PayZen Krypton Client V4.0.**

## Formatos
Não há evidência documental de importação CSV, Excel ou geração PDF nesse protótipo.

## Aprendizados de produto
Experiência de checkout, integração de provedor, ciclo de tokens e tratamento de estados de transação.

> Esta apresentação não divulga tokens, credenciais, parâmetros de ambiente, dados de cartão nem código-fonte.
