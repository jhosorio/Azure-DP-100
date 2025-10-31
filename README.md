# Azure-DP-100
## Desafio 1

Cenário
Imagine que você é proprietário de uma sorveteria chamada Gelato Mágico, localizada em uma cidade litorânea. Você percebe que a quantidade de sorvetes vendidos diariamente tem uma forte correlação com a temperatura ambiente. No entanto, sem um planejamento adequado, você pode acabar produzindo mais sorvetes do que o necessário e ter prejuízos com desperdícios ou, ao contrário, produzir menos e perder vendas.

Para solucionar esse problema, você decide usar Machine Learning para prever quantos sorvetes serão vendidos com base na temperatura. Com esse modelo, será possível antecipar a demanda e planejar a produção de maneira eficiente.

Objetivo
O objetivo deste projeto é desenvolver um modelo de regressão preditiva que permita: 

✅ Treinar um modelo de Machine Learning para prever as vendas de sorvete com base na temperatura do dia.

✅ Registrar e gerenciar o modelo usando o MLflow.

✅ Implementar o modelo para previsões em tempo real em um ambiente de cloud computing.

✅ Criar um pipeline estruturado para treinar e testar o modelo, garantindo reprodutibilidade.

Como entregar esse projeto?

1. Crie um novo repositório no github com um nome a sua preferência
2. Crie uma pasta chamada 'inputs' e crie um documento de texto com algumas sentenças
3. Crie um arquivo chamado readme.md , deixe alguns prints descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo após a IA analisar suas sentenças
4. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

Criando um Grupo de Recusos
<img width="852" height="541" alt="image" src="https://github.com/user-attachments/assets/e18f4e83-5f28-4488-8b9c-deb318640ffe" />

Criando um recurso de Azure Machine Learning
<img width="1171" height="803" alt="image" src="https://github.com/user-attachments/assets/6d8a7c8a-354d-4194-94d5-fb3e551ead29" />

Criando uma Computação
<img width="1411" height="832" alt="image" src="https://github.com/user-attachments/assets/c9b1f3ff-c190-4def-b413-19a2a4527770" />

Criando um Cluster
<img width="1437" height="827" alt="image" src="https://github.com/user-attachments/assets/8872243c-915f-4075-b4d9-eefadd3c57e5" />

Criando um Data Asset
<img width="1445" height="866" alt="image" src="https://github.com/user-attachments/assets/ccb6d169-fe4f-45d6-bd83-beba79939c48" />

Submetendo um Automated ML job
<img width="1655" height="845" alt="image" src="https://github.com/user-attachments/assets/a9e19662-6208-42a7-bd97-e9dd97cebe3b" />

Criando um Design
<img width="929" height="731" alt="image" src="https://github.com/user-attachments/assets/c75f4068-7b79-4e21-80c8-98ca62e11fe1" />

Submetendo o Design
<img width="1161" height="837" alt="image" src="https://github.com/user-attachments/assets/deaa7ea3-a3d0-4f1b-a4d4-0ad45c4988ff" />

Trained Model
<img width="1612" height="761" alt="image" src="https://github.com/user-attachments/assets/8293aac7-0880-417d-9926-bc946ce5f73d" />

Score Model
<img width="1421" height="795" alt="image" src="https://github.com/user-attachments/assets/b516e251-6bf0-421d-b8ed-a9e78f858e59" />

Jobs
<img width="1652" height="451" alt="image" src="https://github.com/user-attachments/assets/8da2199f-85f0-416c-9f18-2e018951d4ec" />

Model-Child jobs
<img width="1516" height="860" alt="image" src="https://github.com/user-attachments/assets/b29d0c94-ce01-4c8a-a209-b980d6ea5248" />

Segue alguns insights valiosos extraídos da base de dados de vendas de sorvetes e temperatura entre julho e outubro de 2025:

📈 1. Correlação entre Temperatura e Vendas
• 	Existe uma forte correlação positiva entre temperatura e vendas: dias mais quentes tendem a ter mais vendas.
• 	A correlação linear entre as variáveis é aproximadamente 0.92, o que indica uma relação direta e significativa.

🔥 2. Faixas de Temperatura com Maior Venda
• 	As maiores vendas ocorrem em dias com temperaturas acima de 29°C.
• 	Exemplos:
• 	05/07 (30.2°C): 421 vendas
• 	10/07 (31.1°C): 390 vendas
• 	25/07 (31.0°C): 412 vendas

❄️ 3. Baixas Temperaturas, Baixas Vendas
• 	Dias com temperaturas abaixo de 23°C apresentam vendas significativamente menores.
• 	Exemplos:
• 	01/08 (22.8°C): 123 vendas
• 	08/09 (20.5°C): 123 vendas
• 	27/09 (19.4°C): 123 vendas

📅 4. Padrão de Vendas
• 	Os dias com vendas iguais a 123 unidades ocorrem com frequência em temperaturas muito baixas — pode indicar um limite mínimo de demanda.
• 	Os valores de vendas 412 unidades aparecem várias vezes em dias quentes — pode indicar um limite máximo de capacidade ou estoque.

🧠 5. Oportunidade de Otimização
• 	Com base na temperatura prevista, é possível ajustar produção e estoque para evitar perdas ou falta de produto.
• 	Ideal para integrar com previsão meteorológica e criar um modelo preditivo dinâmico.

## Desafio 2
Criando um Grupo de Recursos para AI Foundry
<img width="1251" height="801" alt="image" src="https://github.com/user-attachments/assets/36e74ba6-f9f3-4320-9d90-df4e14da422e" />

Criando um Recurso para AI Foundry
<img width="1181" height="802" alt="image" src="https://github.com/user-attachments/assets/6d33fdf5-9e0f-420b-903b-57d878cff8af" />

Interface do AI Foundry
<img width="1592" height="934" alt="image" src="https://github.com/user-attachments/assets/8c647c26-e499-409e-9e04-aeed277f74cb" />

Interface Deploy Model
<img width="1585" height="873" alt="image" src="https://github.com/user-attachments/assets/27f2cf11-f7f2-4f54-99be-20b973ba8c3b" />

Selecionando Modelo GPT-5-mini
<img width="1660" height="896" alt="image" src="https://github.com/user-attachments/assets/0341d156-7677-48a7-b761-97aeae4b2698" />

Deploy
<img width="1505" height="902" alt="image" src="https://github.com/user-attachments/assets/3c24b381-b249-4945-9f41-fd207e983150" />


