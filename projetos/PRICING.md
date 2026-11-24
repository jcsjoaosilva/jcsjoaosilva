# PricingHub — Precificação e análise de margens

**Categoria:** Ferramenta de negócio / meios de pagamento  
**Visibilidade do código:** Privado

## Problema e proposta de valor
Apoiar decisões de preço em operações de pagamentos, simulando custos e identificando quando a condição comercial proposta fica abaixo do patamar mínimo definido.

## Funcionalidades documentadas
- Simulação de MDR por bandeira e modalidade de pagamento.
- Cálculo de taxa mínima *blended*, margem líquida e impacto financeiro por linha.
- Alertas visuais para cenários abaixo da taxa mínima.
- Telas de **Premissas, Negócios, Executivo, Comparação e Proposta**.
- Configuração de componentes de custo e faixas progressivas de volume.
- Comparação lado a lado de cenários.
- Salvamento local de simulações e compartilhamento de cenários via URL.
- **Exportação em Excel e PDF**.
- Modo escuro e transições de navegação.

## Tecnologias e formatos
| Área | Tecnologia ou recurso |
| --- | --- |
| Front-end | HTML, CSS e JavaScript |
| Exportação Excel | SheetJS / xlsx.js |
| Geração PDF | html2canvas e jsPDF |
| Navegação | View Transitions API |
| Persistência local | localStorage |
| Importação CSV | Não confirmada no README original |

## Atuação em produto e uso de IA
Tradução de regras de negócio em funcionalidades, prototipação, análise de cenários e evolução de interface com apoio de ferramentas de IA. A precificação é apresentada como lógica de negócio; **não se afirma que o cálculo seja executado por modelo de IA**.

## Projeto relacionado
[PrincingHub-TSA — motor de custos operacionais](PRICING-TSA.md), com consolidação de custos e indicadores.

> Esta é uma apresentação funcional. Fórmulas comerciais detalhadas, condições de clientes, valores e código-fonte permanecem privados.
