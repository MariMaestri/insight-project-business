## Dashboard Looker Studio: O Ciclo de Vida Empresarial no Paraná

Projeto académico de Análise de Dados desenvolvido pela FAE em parceria com o SEBRAE, focado na Análise Estratégica do Ecossistema Empresarial Paranaense. Através da inteligência de dados, o *dashboard* avalia o ciclo de vida empresarial para gerar inteligência de mercado e guiar decisões de negócios a nível estadual.

🔗 **[Clique aqui para acessar ao dashboard interativo no Looker Studio]([https://www.google.com/search?q=%23](https://datastudio.google.com/reporting/afbe08f4-6960-420f-b430-67a903edced7))**

## 📊 Metodologia e Escopo

A análise mapeia 1.838.142 empresas ativas [página: 3] distribuídas por todos os 399 municípios do Paraná [página: 3, 8], projetando cenários até o ano de 2025. O projeto está dividido em quatro fases fundamentais do ecossistema: O Nascimento, A Sobrevivência, A Estabilidade e A Oportunidade [página: 2, 4, 6, 8].

* **Fontes de Dados:** Base primária fornecida pelo SEBRAE.
* **Tratamento Inicial:** Limpeza, padronização e higienização estrutural realizadas no Microsoft Excel.

### Regras de Negócio e Indicadores Exclusivos

Para transformar dados brutos em ferramentas de decisão, a equipa desenvolveu métricas proprietárias:

* **Score de Resiliência:** Um indicador composto (0 a 100) que reflete a preparação de um município para sustentar empresas a longo prazo. A fórmula atribui pesos específicos: baixa inaptidão (30%), PIB *per capita* (25%), taxa de maturidade (25%) e IDH-M (20%) [página: 9].
* **Quadrante Mágico de Investimento:** Inspirada em matrizes de consultoria, esta ferramenta cruza o IPC Total (potencial de consumo) com o Saldo CAGED (saldo de contratações) [página: 8]. Classifica as cidades em quatro zonas de mercado: Estrela (alto consumo e geração de empregos), Aposta, Madura e Risco [página: 8].

## 💡 Principais Insights Exploratórios

* **Rotas de Consumo de Alta Renda:** Curitiba domina o potencial de consumo, impulsionada pelas classes B1 e A [página: 6]. O eixo Curitiba-Londrina-Maringá revela-se a zona ideal para investimentos com foco em alto volume e rendimento urbano [página: 6].
* **Liderança em Resiliência:** O município de Araucária destaca-se como o grande líder do estado, atingindo 74,13 pontos no *Score* de Resiliência, graças à combinação de baixo encerramento de empresas e alto PIB *per capita* [página: 9].
* **Oportunidades Fora do Radar:** Indianópolis surge como a "Cidade Surpresa". Apesar de possuir menos de 50 mil habitantes, atinge um *score* impressionante de 71,84 devido ao seu excelente PIB [página: 9], apresentando-se como uma aposta altamente rentável e menos saturada.

## ⚙️ Detalhes Técnicos e Modelação no Looker Studio

Para viabilizar a análise sem recorrer a bancos de dados relacionais externos, o projeto explorou funcionalidades avançadas da ferramenta de visualização:

* **Combinação de Dados (Data Blending):** Foram criadas mesclagens estratégicas diretamente no *Looker Studio* (ex: "PIB vs Inaptas" e "Ativas x Inaptas"), permitindo o cruzamento de indicadores macroeconómicos municipais com os registos de CNPJs.
* **Governança e Lógica de Filtros:** A precisão das visualizações foi assegurada por um rigoroso sistema de regras. Destaca-se a implementação do "Filtro Empresas Inaptas" (construído com 5 cláusulas lógicas combinadas) e parametrizações de âmbito (restrição regional `UF = PR` e segmentação por porte: MEI, ME, EPP, GOV, SFL).
* **Tratamento Cartográfico e de Outliers:** Aplicação de regras de exclusão/inclusão para municípios que distorciam a escala da base de dados (ex: isolamento ou exclusão de Mirador, Curitiba, Araucária e Indianópolis para visualizações comparativas específicas).

## 👥 Equipa FAE

Este projeto foi desenvolvido em colaboração por:

* **Isabella Soberay** 
* **Luana Barrios**
* **Mariane Maestri**
* **Suzana Faucz**

## Visualização do Dashboard
<img width="604" height="352" alt="PG 1" src="https://github.com/user-attachments/assets/e4a2722f-d808-408e-a9bf-02756cdf0aef" />
<img width="602" height="500" alt="PG 2" src="https://github.com/user-attachments/assets/29edbeca-62f1-4e76-b38b-9676c4348b34" />
<img width="602" height="453" alt="PG 3" src="https://github.com/user-attachments/assets/2006f3f1-6dbe-4fdb-82b4-789563c369ae" />
<img width="602" height="452" alt="PG 4" src="https://github.com/user-attachments/assets/5dc761ee-9f14-4443-a3ce-87dd74e77042" />
<img width="602" height="450" alt="PG 5" src="https://github.com/user-attachments/assets/510a4a60-c137-4900-af86-2465f5c8a7cd" />
<img width="601" height="449" alt="PG 6" src="https://github.com/user-attachments/assets/e0d12977-06fa-4250-b7f3-f497821a2316" />
<img width="601" height="449" alt="PG 7" src="https://github.com/user-attachments/assets/50a8e05f-c7a0-4087-8d27-7af56cad65bc" />
<img width="601" height="626" alt="PG 8" src="https://github.com/user-attachments/assets/c27df30e-49ed-4804-984e-1250d3e6fbce" />
<img width="602" height="601" alt="PG 9" src="https://github.com/user-attachments/assets/842f999e-e8e1-4436-9c5f-2578dfb3f25a" />






