# ELO — Mensagens Efêmeras

**Categoria:** Aplicativo experimental de comunicação  
**Status:** **Em desenvolvimento e homologação; sem auditoria independente de segurança.**  
**Demonstração experimental:** [ELO na Cloudflare](https://elo-mensagens.elo-turn-credenciais.workers.dev/)

## Problema e objetivo
Explorar conversas temporárias entre dispositivos, equilibrando privacidade, usabilidade, confiabilidade das conexões e engenharia de segurança.

## Recursos documentados no projeto
- Conversas efêmeras e expiração de mensagens.
- Convites por **QR Code** ou link.
- Conferência de identidade por **cinco emojis**.
- Contatos confiáveis opcionais, armazenados no dispositivo.
- Mensagens e imagens de visualização única.
- Conversas simultâneas na mesma interface (limite provisório documentado: até quatro).
- Comunicação em tempo real por **WebRTC DataChannel** e TURN.
- Camada criptográfica experimental com **Double Ratchet via Olm/vodozemac** e componente pós-quântico híbrido **ML-KEM-768**.
- Projetos móveis com **Capacitor** para Android e iOS.
- Testes internos e análise de falhas, sem validação externa independente.

## Tecnologias
| Área | Tecnologias documentadas |
| --- | --- |
| Interface | React e TypeScript |
| Comunicação | WebRTC, TURN |
| Infraestrutura | Cloudflare Workers e Durable Objects |
| Mobile | Capacitor |
| Criptografia | Web Crypto API, Olm/vodozemac, ML-KEM-768 |
| Desenvolvimento | Prototipação, análise de código e testes com apoio de IA |

## Uso de inteligência artificial
Ferramentas de IA apoiam a especificação, desenvolvimento, inspeção de código, diagnóstico e preparação de testes. Isso não equivale a uma auditoria de segurança.

## Limitações e responsabilidade
- **Não implementa o Signal Protocol completo nem o Triple Ratchet.**
- Não é um produto de segurança auditado e **não deve ser utilizado para comunicações de alto risco**.
- O código-fonte e detalhes internos ficam privados.
- A demonstração pode mudar ou ficar temporariamente indisponível durante o desenvolvimento.

[Experimentar a demonstração](https://elo-mensagens.elo-turn-credenciais.workers.dev/)
