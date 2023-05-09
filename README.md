# Estudo estatístico do transporte ferroviário de carga 
# Projeto: Avaliar o transporte ferroviário de cargas identificando o impacto de variáveis econômicas na movimentação mensal

Equipe de pesquisa:

Scrum master - Matheus Roque

Product Owner - Lucas Nobre



________________________________________
🛠️ Ferramentas e Tecnologias utilizadas:

•	GitHub

•	Jira software

•	5W2H

•	Google coolab

•	PowerBI

---------------------------------------
📜 Desenvolvimento da 1ª sprint

Identificação das concessões

Mapeamento das concessões/portos

Destacar local de origem e destino final de cada concessão

Matéria prima transportada pelas ferrovias

filtragem entre as maiores concessões identificadas:

• RUMO

• MRS

• VLI

📊 Base para análise de dados:

https://fatecspgov-my.sharepoint.com/:x:/r/personal/lucas_siqueira29_fatec_sp_gov_br/_layouts/15/Doc.aspx?sourcedoc=%7BFB67DDA4-08C6-4B00-B38F-EEB9029D903C%7D&file=Transporte%20de%20Carga%20-%20Origem%20Destino-%202006%20-%20janeiro%202023.xlsx&action=default&mobileredirect=true

---------------------------------------------------
✅ Apresentação 1ª Sprint

https://fatecspgov-my.sharepoint.com/:p:/r/personal/lucas_siqueira29_fatec_sp_gov_br/_layouts/15/Doc.aspx?sourcedoc=%7B7DBCEF9F-82C0-4BB1-B7D9-6AF504E9CD1D%7D&file=Apresenta%C3%A7%C3%A3o%20-%20Sprint%201%20ppt.pptx&action=edit&mobileredirect=true

-------------------------------------------------
📜 Desenvolvimento da 2ª sprint

Foi feito o levantamento do PIB estadual com relação a movimentação do minério de ferro na concessão MRS no ano de 2021 e 2022, com base nessa análise foi desenvolvido com dados estátisticos na ferramenta google colab uma regressão linear ao qual o resultado R² não se comporta de forma coerente com o ideal

 OLS Regression Results                            
==============================================================================
Dep. Variable:                    PIB   R-squared:                       0.006
Model:                            OLS   Adj. R-squared:                 -0.004
Method:                 Least Squares   F-statistic:                    0.5678
Date:                Mon, 01 May 2023   Prob (F-statistic):              0.453
Time:                        13:59:03   Log-Likelihood:                -100.77
No. Observations:                 100   AIC:                             205.5
Df Residuals:                      98   BIC:                             210.7
Df Model:                           1                                         
Covariance Type:            nonrobust                                         
==============================================================================
                 coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------
const          0.2657      0.133      1.999      0.048       0.002       0.529
DADOS         -0.0173      0.023     -0.753      0.453      -0.063       0.028
==============================================================================
Omnibus:                       33.900   Durbin-Watson:                   0.012
Prob(Omnibus):                  0.000   Jarque-Bera (JB):                8.439
Skew:                          -0.395   Prob(JB):                       0.0147
Kurtosis:                       1.817   Cond. No.                         11.7
==============================================================================




