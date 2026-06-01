# Deteccao de Anomalias com Isolation Forest

## Abordagem

- Carreguei o dataset, selecionei as variaveis e padronizei com `StandardScaler`.
- Treinei `IsolationForest` e gerei rotulos (`-1` anomalia, `1` normal) e score.
- Analisei anomalias e visualizei pares de variaveis.

## Interpretacao

Normais: horario 9-17, duracao 25-60, 1 tentativa, IP habitual, paginas 9-21.
Anomalias: horario 0-3/22-23, IP diferente, muitas tentativas, duracao muito baixa/alta, paginas muito baixas/altas.

## Respostas as questoes

1. **Padroes normais:** 9-17, 25-60 min, 1 tentativa, IP habitual, 9-21 paginas.
2. **Frequentes nas anomalias:** IP diferente, horario incomum, 6-10 tentativas, duracao extrema, paginas extremas.
3. **Nem toda anomalia e problema:** pode ser uso legitimo (manutencao, auditoria, admin).
4. **Falsos positivos:** acesso noturno legitimo, VPN/IP diferente, sessao longa, power-user.
5. **Uso em:** triagem e alertas, ajuste por perfil/horario, combinacao com regras, re-treino periodico.
