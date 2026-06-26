# Predição do Net Promoter Score (NPS) em E-commerce: Uma Análise Exploratória e Aplicação de Machine Learning

## Sobre o projeto
Este repositório reúne os arquivos desenvolvidos para o Tech Challenge, cujo objetivo é analisar os fatores operacionais que influenciam a satisfação de clientes em um cenário de e-commerce e propor um modelo preditivo capaz de antecipar a classificação do Net Promoter Score (NPS).

O projeto contempla desde a análise exploratória dos dados (EDA) até a implementação de um modelo de Machine Learning baseado no algoritmo Random Forest, utilizando informações relacionadas à logística, atendimento ao cliente e características dos pedidos para identificar clientes com maior probabilidade de se tornarem promotores, neutros ou detratores.

A proposta busca demonstrar como técnicas de Ciência de Dados podem apoiar decisões de negócio, permitindo ações preventivas para melhorar a experiência do cliente antes da aplicação da pesquisa oficial de NPS.

## Estrutura do repositório
```text
nps-preditivo-tech-challenge/
├── data/
│   └── desafio_nps_fase_1.csv
├── notebooks/
│   └── tech_challenge_nps.ipynb
├── reports/
│   ├── relatorio_predicao_nps.pdf
│   └── apresentacao_nps.pdf
└── README.md
```

## Base de dados
A base de dados utilizada neste projeto foi disponibilizada como parte do Tech Challenge e está disponível na pasta `data/` deste repositório.

O conjunto de dados é composto por **2.500 registros** e **19 variáveis**, contendo informações relacionadas a clientes, pedidos, logística, atendimento e satisfação. Esses dados foram utilizados na análise exploratória, na identificação dos principais fatores associados ao NPS e no treinamento e avaliação do modelo de Machine Learning desenvolvido no projeto.

## Tecnologias utilizadas
O projeto foi desenvolvido utilizando as seguintes tecnologias e bibliotecas:

* Python 3
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Random Forest
* Git e GitHub

## Como executar o projeto
1. Clone ou faça o download deste repositório:

   ```bash
   git clone https://github.com/marsrosas/nps-preditivo-tech-challenge.git
   ```

2. Abra o arquivo `tech_challenge_nps.ipynb` no Google Colab.

3. Faça o upload do arquivo `desafio_nps_fase_1.csv` para o ambiente do Google Colab.

4. Execute as células do notebook na ordem em que foram desenvolvidas para reproduzir a análise exploratória e a construção do modelo preditivo.

## Principais resultados
* A análise exploratória identificou que **atraso na entrega**, **quantidade de reclamações**, **contatos com o atendimento** e **tempo de resolução de problemas** são os fatores com maior influência na satisfação dos clientes.

* Foi desenvolvido um modelo de classificação utilizando o algoritmo **Random Forest** para prever a categoria de satisfação dos clientes (Promotor, Neutro ou Detrator).

* O modelo alcançou aproximadamente **77% de acurácia** no conjunto de teste.

* O **recall de 96% para a classe de clientes detratores** demonstra o potencial da solução para identificar consumidores com maior risco de insatisfação, permitindo a adoção de ações preventivas antes da aplicação da pesquisa de NPS.

* Os resultados reforçam o potencial da Ciência de Dados como ferramenta de apoio à tomada de decisão, contribuindo para a melhoria da experiência do cliente e para o aumento da fidelização.

## Autora
**Grupo 68**   
**Marselle Rosas da Silva** | rosas_mars@hotmail.com | rm375622

Projeto desenvolvido como parte do **Tech Challenge – Fase 1** da pós-graduação em **AI Scientist**.
