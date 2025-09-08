# Análise de Uso do Sistema de Bicicletas Compartilhadas (2021–2024)

A **Cyclistic** é um sistema de bicicletas compartilhadas de Chicago, lançado em 2016. Hoje conta com mais de **5.800 bicicletas e 690 estações**.  
A empresa oferece três modalidades de uso:  
- Passe avulso (casuais)  
- Passe diário (casuais)  
- Assinatura anual (membros)  
  Este projeto analisa dados de uso de bicicletas compartilhadas entre **usuários casuais** e **membros assinantes**, ao longo dos anos **2021 a 2024**.  
O objetivo é entender os padrões de comportamento, diferenças entre perfis e identificar **oportunidades de conversão de casuais em membros**.
Estudos internos mostram que **membros anuais são mais rentáveis**, tornando a **conversão de casuais em membros** uma prioridade estratégica.  
Este relatório analisa os **dados históricos de viagens** para identificar padrões de uso e apoiar a equipe de marketing na criação de estratégias eficazes.  


## Tecnologias Utilizadas
- SQL (Google BigQuery) → limpeza, padronização e consolidação do projeto
- Python (Pandas, Matplotlib) → análise e visualização.  
- GitHub → documentação e compartilhamento do projeto.  

---

## 1. Evolução Mensal
[[Uso mensal](https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/meses_resumo.png)

 **Insight:**  
- Picos de uso durante a primavera / verão.  
- Usuários casuais aumentam muito em meses de clima favorável → oportunidade para promover a conversão.

---

## 2. Comportamento Semanal
[Uso semanal] (https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/semana_resumo.png)
 **Insight:**  
- **Membros**: uso estável durante a semana com picos de terça a quinta (trabalho/estudo)  
- **Casuais**: concentração em finais de semana (lazer).
- Exibir ofertas nos finais de semana

---

## 3. Estações Mais Populares
[Estações](https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/origem_resumo1.png)
          (https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/origem_resumo2.png)
          (https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/destino_resumo1.png)
          (https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/destino_resumo2.png)
Comparação das estações mais usadas para início e fim das viagens.  

**Insight:**  
- Casuais → mais presentes em áreas turísticas.  
- Membros → foco em estações próximas a áreas residenciais e comerciais.
- QR Code em estações de parques/pontos turísticos oferecendo promoções para assinatura / parceria com pontos turísticos.


---

## Tipo de Bicicleta
![Preferência por tipo de bicicleta]
(https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/bikes_resumo1.png)
(https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/bikes_resumo1.png)


 **Insight:**  
- Casuais preferem **docked bikes** (viagens longas de lazer).  
- Membros usam mais **classic** e **electric bikes** (trajetos curtos e ágeis).  
- Em 2024, aparece uso de scooters.
- Foco em eletric bikes e scooters  

---

## 5. Duração Média ao Longo do Dia
![Duração média ao longo do dia]
(https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/dia_Resumo1.png)
(https://github.com/amandasanmartin/Viagens-divvy/blob/Imagens/dia_resumo1.png)

 **Insight:**  
- Casuais fazem viagens mais longas durante o dia (lazer).  
- Membros mantêm padrão constante ao longo das horas (deslocamento diário).  
- Redução de tempo médio em 2024 → maior adoção de e-bikes/scooters.  

## Dados
- Imagens dos gráficos e dados estão disponibilizados nas ramificações desse repositório.
- A análise completa está no relatório. 
