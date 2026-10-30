# EpicSlice — Referência rápida JTBD × PBB

Leia este arquivo quando precisar de lembretes densos durante o fatiamento.

## JTBD (Ulwick) — checklist do Job Statement

Formato: `verbo + objeto + clarificador contextual`

Perguntas:
1. Quem é o job executor (usuário final)?
2. Qual é o job completo (não só um passo da solução atual)?
3. O job está agnóstico a produto/tecnologia?
4. Separei outcomes (métricas) do job?
5. Separei emotional/social jobs do job funcional?

Outcomes: `direção + métrica + objeto de controle + contexto`  
Job Map universal: define → locate → prepare → confirm → execute → monitor → modify → conclude

## PBB (Caroli & Aguiar) — canvas em 4 blocos

1. Produto / Problemas / Expectativas  
2. Personas (perfil, faz, espera)  
3. Features (+ problemas e benefícios laterais)  
4. PBIs via Steps Map → ARO → User Story 3Ws

Escrita PBB → Story:
- Quem = Persona  
- O quê = PBI ARO  
- Por quê = benefício da feature / outcome JTBD

## Qualidade

- INVEST + 3Cs + BDD (≤5 ACs)  
- TAPAs: Tangível, Atômica, Preciosa, Acessível  
- DoR: story + INVEST + ACs + cabe na sprint  
- Habilitadores em ARO (exploratório/técnico), nunca fake US de desenvolvedor  
- COORG: Classificar → Ordenar features → ORGanizar PBIs

## Anti-padrões

- Situação ≠ Job  
- Feature sem benefício  
- PBI sem persona  
- Épico disfarçado de story  
- Fatia só de backend/frontend sem valor  
- Refinar backlog inteiro de uma vez
