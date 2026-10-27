# Auditoria funcional — Gerador Inteligente de Prompts

Versão: 1.0.0
Data-base: 2026-10-27

## Objetivo

Registrar as características identificáveis do agente de origem
e separar preservação funcional de melhorias propostas.

## Escopo da evidência

Esta auditoria se baseia em instruções de comportamento
disponíveis no contexto de configuração do agente e
nas interações presentes na conversa de reconstrução.

Não houve inspeção de arquivos privados, infraestrutura,
configurações internas de plataforma ou sessões externas.

A configuração observada indica o comportamento projetado.
Não substitui testes de execução.

## 1. Finalidade principal

Transformar ideias em prompts detalhados de vídeo
para ferramentas de geração audiovisual por IA.

## 2. Conhecimento especializado

- Linguagem cinematográfica.
- Realismo visual.
- Animação.
- Enquadramento e lentes.
- Movimentos de câmera.
- Iluminação.
- Texturas e materiais.
- Atmosfera e profundidade.
- Color grading.
- Diálogos em português brasileiro.

## 3. Tipos de solicitações originalmente contemplados

- Escolher um estilo de vídeo.
- Escolher rosto próprio ou personagem.
- Descrever uma ideia.
- Receber um prompt completo.
- Criar uma cena realista.
- Criar cena animada ou em anime.
- Incluir falas em português brasileiro.
- Usar primeira pessoa.

## 4. Funcionalidades essenciais confirmadas

F01 — Pergunta inicial de estilo com 12 opções.

F02 — Pergunta de escolha entre rosto próprio e personagem.

F03 — Resposta especial quando o usuário escolhe rosto próprio.

F04 — Pergunta para receber a ideia.

F05 — Geração final de prompt.

F06 — Prompt em inglês.

F07 — Diálogos em português brasileiro.

F08 — Descrição cinematográfica rica.

F09 — Tratamento ultra-realista para estilos não cartoon.

F10 — Tratamento estilizado para cartoon e animação.

F11 — Sete seções obrigatórias.

F12 — Oferta de interação por voz quando disponível.

## 5. Modos identificáveis

Modo A — Interação guiada original.

Modo B — Criação em primeira pessoa.

Modo C — Criação com personagem.

Modo D — Cinematografia realista.

Modo E — Animação estilizada.

## 6. Formatos identificáveis

- Perguntas conversacionais.
- Escolhas apresentadas em lista.
- Prompt estruturado.
- Falas escritas em português.
- Descrições em inglês.

## 7. Interpretação de preferências

O estilo selecionado determina a linguagem visual.

A seleção de rosto próprio altera o ponto de vista e
impede personagens adicionais.

A ideia determina cenário, ação, elementos narrativos
e conteúdo dos diálogos.

## 8. Critérios de qualidade originais

- Detalhamento visual elevado.
- Boa atmosfera.
- Cinematografia explícita.
- Luz cinematográfica e dinâmica.
- Neblina volumétrica quando apropriada.
- Texturas e materiais detalhados.
- Profundidade de campo e bokeh.
- Enquadramento e lente.
- Movimento de câmera.
- Cor, contraste e gradação.
- Fidelidade ao estilo.
- Estrutura final completa.

## 9. Capacidades não verificadas no original

NV01 — Análise especializada de imagens enviadas.

NV02 — Leitura de vídeos de referência.

NV03 — Extração de conteúdo de documentos.

NV04 — Geração direta de arquivo de vídeo.

NV05 — Envio direto de prompts para plataformas.

NV06 — Conhecimento atualizado de APIs específicas.

NV07 — Revisão automática de prompts anteriores.

NV08 — Storyboard por cenas.

NV09 — Suporte a múltiplas tomadas persistentes.

NV10 — Exportação de arquivos.

NV11 — Persistência de dados entre sessões.

NV12 — Validação automatizada de resultados renderizados.

Essas capacidades não devem ser atribuídas ao original
sem evidências adicionais.

## 10. Melhorias introduzidas na Skill

U01 — Respeitar informações previamente fornecidas.

U02 — Gerar diretamente quando o pedido estiver completo.

U03 — Revisar e otimizar prompts.

U04 — Produzir storyboard textual.

U05 — Separar múltiplas tomadas.

U06 — Controlar coerência espacial e temporal.

U07 — Adaptar de forma prudente a plataformas específicas.

U08 — Interpretar referências acessíveis.

U09 — Aplicar checklist de qualidade.

U10 — Tratar insuficiência de ferramentas sem simular capacidades.

## 11. Decisões de compatibilidade

O fluxo original continua como padrão.

A regra do modo "Meu rosto" é intencionalmente restritiva:
primeira pessoa, I/me e sem personagens adicionais.

As melhorias não devem causar perda de fidelidade
nesse comportamento.

A pergunta literal original tem prioridade no início
de uma conversa guiada sem contexto.

## 12. Limitações

Nenhuma Skill textual garante identidade facial.

Nenhuma Skill textual garante um resultado renderizado.

A seleção de características visuais não substitui
um mecanismo real de geração de vídeo.

A capacidade de acessar imagens, voz ou arquivos varia
entre ambientes.

## 13. Hipóteses testáveis

H01 — O agente original segue as perguntas literalmente.

Teste: iniciar uma sessão sem parâmetros e registrar
as três perguntas produzidas.

H02 — O modo rosto próprio não cria personagens extras.

Teste: solicitar uma ideia que mencione outras pessoas
e observar como o agente resolve o conflito.

H03 — O agente produz falas apenas em pt-BR.

Teste: solicitar cena multilíngue e comparar resultado
com a regra de idioma estabelecida.

H04 — O estilo anime não recebe descrição fotorealista.

Teste: selecionar anime e fornecer uma ideia simples.

H05 — A Skill preserva a estrutura final de sete seções.

Teste: executar exemplos distintos e contar títulos.

H06 — Entrada por voz pode ser usada no cliente escolhido.

Teste: enviar uma mensagem de voz em cliente compatível
e verificar se o texto chega corretamente ao fluxo.

H07 — Imagens podem servir como referência.

Teste: fornecer imagem acessível, pedir vídeo derivado
e avaliar aderência aos detalhes visuais.

## 14. Definição de equivalência

Não há equivalência integral declarada.

Uma equivalência funcional operacional poderá ser
considerada somente após aprovação dos testes
essenciais de regressão.

Melhorias Ultimate devem ser avaliadas separadamente.

## 15. Evidências futuras

Para cada teste, registrar:
- Identificador.
- Versão do agente e modelo, se conhecidos.
- Entrada exata.
- Resposta original.
- Resposta da Skill.
- Observações.
- Nota.
- Resultado: aprovado, reprovado ou inconclusivo.

## 16. Conclusão

A reconstrução preserva a especialidade identificada
e incorpora extensões coerentes com geração de vídeos.

A confirmação de comportamento real depende de
execução comparativa controlada.
