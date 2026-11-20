# Evasão e sucesso acadêmico de estudantes – dados preparados para o Orange

Arquivo: [`estudantes_evasao_sucesso_academico.csv`](estudantes_evasao_sucesso_academico.csv)
(4.424 linhas × 16 colunas, separador vírgula, UTF-8, sem valores ausentes).

Recorte preparado para o trabalho da Fase 1 da disciplina de Ciência de Dados e Inteligência Artificial (PUCRS Online).
Coluna alvo: `Target` (Dropout, Enrolled, Graduate). No Orange, abra o arquivo no widget **File** e defina o papel
(Role) da coluna `Target` como *target*.

## Preparação
A partir do `data.csv` original foram feitos apenas estes passos: remoção de um caractere de tabulação no nome da coluna
"Daytime/evening attendance"; seleção de 16 das 37 colunas; decodificação dos códigos das variáveis categóricas
segundo o dicionário oficial (Course, Daytime/evening attendance, Gender, Scholarship holder, Debtor, Tuition fees up to
date). Nenhuma linha foi removida e os valores numéricos não foram alterados.

## Fonte e licença
Realinho, V., Vieira Martins, M., Machado, J., & Baptista, L. (2021). *Predict Students' Dropout and Academic Success*
[Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5MC89 – licença
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Este recorte é distribuído sob a mesma licença.
