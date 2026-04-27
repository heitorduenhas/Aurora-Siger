# Aurora-Siger - Decolagem

## O que é?:
A atividade Aurora-Siger é um projeto de simulação de uma missão espacial rumo a Marte. 

## Objetivo:
Nele, precisamos fazer um relatório de pré-decolagem, com telemetria, para garantir uma decolagem segura e uma missão bem sucedida.

# Etapas

## 1.1 Organização e descrição da telemetria
Nesta etapa, selecionei quais dados são necessários para fazer uma telemetria funcional, que realmente garantiria uma decolagem segura, e pedi para uma I.A. (Chat GPT) criar uma tabela com dados de naves fictícias.

## 1.2 Algorítimo de verificação
Aqui, estipulei faixas seguras para os dados definidos na etapa anterior e, com base nessas faixas, desenvolvi o algorítimo que vai automatizar a verificação e análise dos dados.

## 1.3 Script em python
Tendo a tabela e o algorítimo, desemvolvi um Script em Python capaz de ler e interpretar os dados da tabela e aplicar o algorítimo de verificação, retornando se a decolagem está pronta ou deve ser abortada.

## 1.4 Análise energética
Na etapa de análise energética, desenvolvi outro Script que pede para o usuário dados energéticos (Capacidade máxima, carga atual, consumo na decolágem e perdas energéticas) e calcula se a energia é sufuciente para completar a missão.

## 1.5 Análise assistida por I.A.
Aqui, pedi para uma I.A. (Chat GPT) fazer uma análise da tabela que ele criou e retornar os resultados seguintes: 
* Classificação dos dados
* Identificação de possíveis anomalias
* Sugestões de risco

## 1.6 Reflexão crítica
Para minha reflexão, criei um texto abordando questões como ética e responsabilidade, impacto social da exploração espacial e sustentabildade ecológica, mostrando como o projeto me ajudou a me desenvolver como profissional da ciência da computação, desenvolver olhar crítico a respeito da preservação do meio-ambiente e como colocar em prioridade a segurança e bem-estar das pessoas.

# Como interagir com o código:

## Análise de anomalias:
Ao executar, o código solicitará ao usuário o número da nave.  
Após digitar, o código analísa se a nave está disponível. Caso esteja, procura alguma anomalia. Se tiver alguma anomalia, ele retorna:  
Aurora-Siger x // ABORTADA  
Caso não haja anomalia, retorna:  
Aurora-Siger x // Pronta para decolar

<img width="737" height="585" alt="image" src="https://github.com/user-attachments/assets/95116c93-cebf-4a2d-8fcf-b45c972a2df3" />

## Análise energética:
Ao executar, o código solicitará os seguintes dados:
* capacidade total(KWh)
* carga atual(%)
* consumo na decolagem(KWh)
* as perdas energéticas estimadas(%)

Com isso, ele irá calcular a energia disponível e o consumo real. Com esses dois valores, ele compara o consumo real com a energia disponível. Caso o consumo for maior que a energia, a decolagem deve ser abortada, caso contrário, a energia é suficiente.

<img width="522" height="195" alt="image" src="https://github.com/user-attachments/assets/3bb14e17-1a93-4cfd-8992-e14fad735a1e" />


