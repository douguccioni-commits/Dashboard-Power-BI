# Dashboard de Gestão de Recursos Humanos (People Analytics)

Este projeto foi desenvolvido para monitorar indicadores estratégicos de Recursos Humanos, como absenteísmo, horas extras, bônus e distribuição salarial.

## 🎯 O Desafio
A base de dados original (`RH.csv`) estava em um formato "plano" (uma única tabela com todas as informações), o que dificultava a análise cruzada e a performance.

## 🛠️ Solução e Modelagem
Realizei a normalização dos dados, criando um **Modelo Estrela (Star Schema)** para otimizar as consultas e a navegação:
*   **Tabela Fato:** `fEventos ou fRH` (contém os registros mensais de faltas, bônus e horas extras).
*   **Tabelas Dimensão:** `dFuncionarios`, `dDepartamentos`, `dCargos`, `dCidades`, `dMotivos`.

## 📊 Principais Insights
*   O cargo de Supervisor e Assistente concentram o maior volume de horas extras.
*   A maior parte das ausências é motivada por Licença Médica e Faltas Injustificadas.
*   Existe uma variação salarial atípica dentro dos mesmos níveis de cargo, o que pode indicar necessidade de revisão na política de remuneração.

## 💻 Tecnologias Utilizadas
*   **Power BI** (Visualização e Modelagem)
*   **DAX** (Criação de medidas e KPIs)
*   **Power Query** (Limpeza e transformação)

## 📸 Visualização do Dashboard
![Print do Dashboard](COLOQUE_AQUI_O_NOME_DA_IMAGEM.png)
