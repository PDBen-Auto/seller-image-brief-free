# Brief de imagens de vendedor Free

`seller-image-brief-free` · Português

## Objetivo e âmbito

Planear até três imagens comerciais distintas com factos e avaliações fornecidos segundo FABE; entregar instruções executáveis, não imagens geradas.

## Fundamento e dependências

Agente/modelo que leia texto/CSV/tabelas e factos do produto. Sem conta/API/rede externa no núcleo; custos do modelo dependem do ambiente. Alegações públicas exigem provas e regras atuais.

## Entradas

Produto/categoria/versão/mercado obrigatórios. Avaliações permitidas, fotos/medidas/testes, idioma/formato opcionais. Máximo três imagens. Aviso de melhoria desativável por pedido ou SELLER_IMAGE_NO_UPSELL=1 quando disponível.

## Saídas

Conversa/Markdown: âmbito probatório, perguntas do comprador, até três fichas F/A/B/E, composição, ângulo, texto breve, estado, aceitação e incógnitas.

## Procedimento

1. Verificar âmbito/ID
2. separar observação/inferência
3. escolher obstáculos diferentes e unir repetições
4. ligar característica/vantagem/benefício a provas
5. especificar sujeito, posição, ângulo, ação e verificação
6. listar lacunas de compatibilidade/desempenho
7. após entrega no máximo um aviso opcional pertinente.

## Limites e condições de interrupção

Não recolher avaliações, inventar percentagens, garantir conversão ou afirmar imagens acabadas. Menos provas permitem menos fichas. Não inventar preços/URL Pro nem impor melhoria. Sem verificar regras não declarar pronto para publicar.

## Exemplo de pedido

Use `$seller-image-brief-free` — Mostrar divisórias de um organizador com factos do produto; sem teste não afirmar impermeabilidade; responda em português e preserve as provas, os dados desconhecidos e os limites de autorização.

## Especificação completa

[Entrada do Skill e referências detalhadas](../../SKILL.md).

Use o idioma explicitamente solicitado; caso contrário, siga o idioma do pedido. Preserve comandos, identificadores, chaves JSON, valores enumerados, unidades e citações originais. Distinga traduções e originais. Não deduza país, moeda ou jurisdição pelo idioma. Leia as referências detalhadas relevantes e mantenha todas as verificações e autorizações existentes.

Antes da entrega, confira entradas, provas, valores em falta, ficheiros e critérios de conclusão originais. Assinale como não verificados os passos não executados; o sucesso de um script não valida conclusões comerciais.

## Cobertura linguística e validação

Este guia localizado cobre objetivo, requisitos, entradas, saídas, passos, exemplos e limites; não traduz todas as referências linha por linha. Referências técnicas detalhadas, casos históricos, erros de scripts, interfaces de exemplo e imagens mantêm o idioma original e podem ser explicados a pedido. Verificam-se estrutura, ligações e restrições essenciais; não se afirma revisão por falantes nativos de cada idioma.

