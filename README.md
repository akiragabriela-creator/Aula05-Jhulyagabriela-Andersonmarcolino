# Atividade - Aula 05: Alarme Automotivo

## Resumo da Solucao
- Regra 1 (Alerta de Bateria): Far�is acesos (C=1) e igni��o desligada (B=0) -> Coverline(B)
- Regra 2 (Alerta de Seguran�a): Porta aberta (A=1) e igni��o ligada (B=1) -> A * B

## Expressao Final e Minitermos
- Expressao da Saida S: S = not(A)*not(B)*C + A*not(B)*C + A*B*not(C) + A*B*C
- Minitermos (Soma de Produtos): sum(m1, m5, m6, m7)
