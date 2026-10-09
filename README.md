# Planilha de Simulação de Investimentos

Planilha desenvolvida para simular investimentos mensais, projetar o crescimento do patrimônio e sugerir a distribuição dos aportes entre diferentes tipos de Fundos Imobiliários.

📊 Seções da Planilha

⚙️ Configurações

Permite definir o salário e o rendimento mensal da carteira, calculando automaticamente uma sugestão de investimento correspondente a 30% do salário informado.

💰 Investimento Mensal

Permite definir o valor do investimento mensal e o prazo da simulação, apresentando a taxa de rendimento considerada, a projeção do patrimônio acumulado e a estimativa de dividendos mensais.

📈 Cenários

Compara as projeções de patrimônio acumulado e dividendos mensais em diferentes períodos: 2, 5, 10, 15, 20 e 30 anos.

🎯 Perfil de Investimento

Permite selecionar o perfil de investimento e apresenta a distribuição sugerida dos aportes entre os diferentes tipos de Fundos de Investimento Imobiliário (FIIs), de acordo com o perfil escolhido: Papel, Tijolo, Híbridos, FOFs, Desenvolvimento e Hotelarias.

📉 Gráfico de Distribuição

Apresenta visualmente os percentuais sugeridos para cada tipo de FII.

📌 Percentuais dos Perfis

Os percentuais de distribuição dos investimentos foram definidos com base nos conteúdos apresentados durante as aulas do curso. Esses percentuais são uma proposta ilustrativa, não uma recomendação financeira nem uma distribuição oficial de mercado.

🧮 Funções do Excel

VF (Valor Futuro)

A função VF é utilizada para projetar o patrimônio acumulado ao longo do tempo, considerando a taxa de rendimento mensal, o prazo da simulação e os aportes mensais. Também é utilizada na seção de cenários para calcular projeções em diferentes períodos.

PROCV (Procura Vertical)

A função PROCV é utilizada para buscar, na tabela auxiliar da aba Planilha2, o percentual de alocação correspondente ao perfil de investimento selecionado e ao tipo de FII. O percentual retornado é utilizado para calcular o valor destinado a cada categoria.

🏷️ Intervalos Nomeados

Foram criados intervalos nomeados para facilitar a leitura e a manutenção das fórmulas:

aporte: valor do investimento mensal.

qtd_anos: prazo da simulação em anos.

rendimento_carteira: rendimento mensal da carteira.

salario: salário informado.

sugestao_investimento: sugestão de investimento de 30% do salário.

taxa_mensal: taxa utilizada na projeção do patrimônio.

🎨 Alterações em Relação à Ferramenta Original

Foram realizadas alterações visuais na ferramenta original, incluindo a substituição do banner, a personalização das cores, a modificação dos gráficos e a reorganização do layout geral.
