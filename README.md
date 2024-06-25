## 📈 Previsão de Estoque com Amazon SageMaker Canvas

Bem-vindo ao repositório do meu projeto de previsão de estoque utilizando o Amazon SageMaker Canvas! Este projeto foi criado com o objetivo de demonstrar como é possível construir um modelo de Machine Learning sem escrever uma única linha de código, focando na previsão de estoque para uma empresa. 🏢🔮

## 🚀 Sobre o Projeto

Neste projeto, utilizei o Amazon SageMaker Canvas, uma ferramenta de Machine Learning que permite a criação de modelos preditivos de forma visual e intuitiva. A principal vantagem é a democratização do acesso ao Machine Learning, permitindo que usuários sem conhecimento em programação possam construir, treinar e implementar modelos de previsão.

## 🎯 Objetivo

O objetivo principal deste projeto é prever o estoque de uma empresa, ajudando na tomada de decisões estratégicas sobre compras, armazenamento e distribuição de produtos. Com isso, busquei:

- Reduzir o excesso de estoque
- Evitar faltas de produtos
- Otimizar o uso do espaço de armazenamento
- Melhorar a eficiência operacional

## 🛠️ Tecnologias Utilizadas

- **Amazon SageMaker Canvas**: Plataforma usada para criar e treinar o modelo preditivo.
- **Amazon S3**: Armazenamento de dados utilizado para armazenar o dataset de treino e outros arquivos necessários.
- **Amazon QuickSight**: Ferramenta de visualização de dados para criar dashboards interativos com os resultados da previsão.

## 📊 Dataset

O dataset utilizado contém informações históricas de estoque, incluindo:

- ID do Produto
- Data
- Quantidade em Estoque
- Vendas Diárias
- Reabastecimentos

Esses dados são essenciais para entender os padrões de consumo e prever a demanda futura de cada produto.

## 🔍 Passo a Passo do Projeto

1. **Coleta de Dados**: Reuni os dados históricos de estoque da empresa.
2. **Upload dos Dados**: Carreguei o dataset no Amazon S3.
3. **Criação do Modelo**: Utilizando o SageMaker Canvas, importei os dados e construí o modelo de Machine Learning.
4. **Treinamento do Modelo**: Treinei o modelo com os dados históricos para identificar padrões e tendências.
5. **Avaliação do Modelo**: Avaliei a precisão do modelo utilizando métricas de performance.
6. **Previsão**: Gerei previsões de estoque para períodos futuros usando o modo **Time Series Forecasting**.
7. **Visualização dos Resultados**: Utilizei o Amazon QuickSight para criar dashboards interativos e facilitar a interpretação dos resultados.

## 📈 Previsão Realizada

Durante o processo de avaliação do modelo, realizei diversas previsões de estoque com base nos dados históricos disponíveis. Alguns exemplos de previsões incluem:

1. **Produto A**: Previmos um aumento na demanda para o próximo mês, recomendando um ajuste no reabastecimento para evitar faltas.
2. **Produto B**: Identificamos um padrão sazonal nas vendas, permitindo uma previsão precisa para o período de pico de vendas no final do ano.
3. **Produto C**: Observamos uma diminuição no estoque médio necessário, sugerindo uma otimização na gestão de inventário para reduzir custos.

Cada uma dessas previsões foi baseada nas análises feitas pelo modelo treinado no Amazon SageMaker Canvas, utilizando as métricas de avaliação para garantir a qualidade das recomendações feitas.

## 🖥️ Como Reproduzir Este Projeto

1. **Acesse o Amazon SageMaker Canvas**: [Link para o SageMaker Canvas](https://aws.amazon.com/sagemaker/canvas/)
2. **Carregue o Dataset**: Faça o upload do seu dataset no Amazon S3.
3. **Crie o Modelo**: Siga o guia do SageMaker Canvas para importar os dados e criar o modelo preditivo.
4. **Treine o Modelo**: Inicie o treinamento do modelo com os dados carregados.
5. **Avalie e Implemente**: Avalie o desempenho do modelo e, se satisfeito, implemente as previsões.

## 🏅 Contribuições

Contribuições são bem-vindas! Se você tem sugestões, melhorias ou encontrou bugs, sinta-se à vontade para abrir uma issue ou enviar um pull request. Vamos trabalhar juntos para tornar este projeto ainda melhor!

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Contato

Se você tiver alguma dúvida ou quiser entrar em contato, sinta-se à vontade para me mandar uma mensagem:

- **Email**: jeffersoncamp22@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/jeffersoncampina/

---

Feito com ❤️ por Jefferson Campina

---

![Machine Learning](https://media.giphy.com/media/26FPCXdkvDbKBbgOI/giphy.gif)

---

Espero que você goste deste projeto e que ele seja útil para suas necessidades de previsão de estoque. Vamos explorar juntos o poder do Machine Learning sem escrever uma linha de código! 🚀✨

---
