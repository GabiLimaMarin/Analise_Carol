# Analise_Carol
A pergunta: Quais estruturas do sitema visual de abelhas, descontado o efeito do tamanho, são diferentes entre as abelhas diurnas e noturnas? ou Quais estruturas visuais são importantes para o hábito noturno em abelhas?
Todas as etapas da análise:

1) Determinei que deve ser Regressão Logística porque os dados não têm distribuição multinormal nem homogeniedade de variância e, portanto, não pode ser realizada uma análise discriminante linear. A quadrática não libera os coeficientes, que é o que me interessa no momento.

2) Padronizei as variáveis preditoras

3) Tirei os resíduos de todas as medidas do sistema visual como resultado do tamanho da abelha para descontar o efeito que o tamanho tenha nessas medidas
4) Avaliei Colinearidade

3) Ajustei o modelo com t
