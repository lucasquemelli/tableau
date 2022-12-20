# Tableau Public

This is a repository where I publish my studies with Tableau Public.

This link is for the [Dashboard number 1](https://public.tableau.com/app/profile/lucas.quemelli/viz/Livro07_16707905911710/DashboardMedalhas?publish=yes).

# Exploração

<img width="1574" alt="image" src="https://user-images.githubusercontent.com/81119854/206906916-b1cf3490-8e81-4715-a766-c2891c3302c3.png">

<img width="1557" alt="image" src="https://user-images.githubusercontent.com/81119854/206907135-10f4a633-31a8-4e82-9c76-951dc19dee6f.png">

<img width="1578" alt="image" src="https://user-images.githubusercontent.com/81119854/206907618-18163bf7-51bf-461d-b678-feca116b2152.png">

<img width="1575" alt="image" src="https://user-images.githubusercontent.com/81119854/206908241-f88041a3-ae00-4f26-9339-b7fa074fd33c.png">

<img width="1576" alt="image" src="https://user-images.githubusercontent.com/81119854/206908402-c855aba5-ec8e-4f5c-9907-dad88b4a7f56.png">

# Classificar/Ordenar no Tableau

<img width="1579" alt="image" src="https://user-images.githubusercontent.com/81119854/206908568-7ce17415-9a58-4838-8bdd-b54927146311.png">

# Filtrar os 05 países com o maior número de medalhas

<img width="1580" alt="image" src="https://user-images.githubusercontent.com/81119854/206908729-c1561ed0-a155-4610-b654-820dffd981ef.png">

<img width="1556" alt="image" src="https://user-images.githubusercontent.com/81119854/206909716-aa0daa63-38d7-4cfd-bc4a-8e8d66e7610c.png">

# Escolhendo tipo DISCRETO para os valores do ano

<img width="850" alt="image" src="https://user-images.githubusercontent.com/81119854/206924715-9b4cc9ed-0109-4e4d-aaa8-1109f049ce51.png">

<img width="1573" alt="image" src="https://user-images.githubusercontent.com/81119854/206924927-6e0216b3-bb8b-4d82-a1a4-e0074bdcf090.png">

# Criando campo calculado 

<img width="915" alt="image" src="https://user-images.githubusercontent.com/81119854/207054623-27de8a73-c338-45a8-a13f-8f169196d94d.png">

<img width="797" alt="image" src="https://user-images.githubusercontent.com/81119854/207055921-ee03fdd4-5da3-426e-9e56-308c65f0d788.png">

# Criando parâmetro

<img width="1266" alt="image" src="https://user-images.githubusercontent.com/81119854/207419854-6b21ba17-0b68-446e-8763-1c6ec122a853.png">

# Mostrando parâmetro

<img width="1767" alt="image" src="https://user-images.githubusercontent.com/81119854/207420182-f3b0e332-834e-4f7d-957e-c47e4e849555.png">

# Identificando valores nulos

<img width="1421" alt="image" src="https://user-images.githubusercontent.com/81119854/207618164-43789a01-a750-4362-a3f5-3fd847a11718.png">

# Identificando o percentual de nulos

<img width="979" alt="image" src="https://user-images.githubusercontent.com/81119854/207687767-c4f2f67e-9aa6-496a-badf-34cd3e3552de.png">

# Mudando dimensão do percentual para porcentagem

<img width="1580" alt="image" src="https://user-images.githubusercontent.com/81119854/207620282-071c904b-bfc1-4cad-9da7-9053bcc0dcf0.png">

<img width="1781" alt="image" src="https://user-images.githubusercontent.com/81119854/207620561-3c6bf3e4-fd18-412f-93c1-c64adfcc7713.png">

<img width="1583" alt="image" src="https://user-images.githubusercontent.com/81119854/207620688-825c0b50-271c-48f7-b3b1-67a8ca715fa3.png">

# Corrigindo valores nulos

#### Para corrigir o problema de valores nulos na coluna Region, nós criamos um novo campo chamado Region Resolvida, da seguinte forma:

- Adicionando um novo parâmetro de número 8:

<img width="595" alt="image" src="https://user-images.githubusercontent.com/81119854/207688352-1c248772-d372-4733-a3e7-77e577bf4c2e.png">

- Criando o campo Region Resolvida:

<img width="1420" alt="image" src="https://user-images.githubusercontent.com/81119854/207686121-1e12110a-5e15-4dd3-88d6-f902fda1f9b7.png">

- Caso queiramos contruir o Campo de Region Resolvida de forma simplificada, podemos usar o Excel da seguinte maneira para segurar e arrastar:

<img width="1661" alt="image" src="https://user-images.githubusercontent.com/81119854/207712568-9cbfacea-b3f1-41fe-ac7d-47afad3de227.png">

# Descobrindo o dado nulo

- Note que na imagem anterior ainda não temos 100% dos dados para Region Resolvida iguais a "linhas com valores". Ainda resta algum registro nulo. Para identificar, basta fazer uma visão que retorne os valores de Region Resolvida por país. Na sequência, podemos adicionar como Marcas o número de registros (Number of records). Assim, identificamos o país que Region Resolvida é nulo. 

<img width="1419" alt="image" src="https://user-images.githubusercontent.com/81119854/207709891-2320b957-7e70-4253-92d7-f6dca79374f8.png">

- Basta pesquisar onde se encontra a região e adicionar manualmente no campo Region Resolvida:

<img width="1049" alt="image" src="https://user-images.githubusercontent.com/81119854/207711115-2ee7f587-9e99-478f-8c87-79022a9b350b.png">

- Resultado:

<img width="1580" alt="image" src="https://user-images.githubusercontent.com/81119854/207711325-532116cc-1af6-43e3-b816-401ceceb58fa.png">

# Separação de texto

- Abaixo, na coluna "Diagnosis", queremos apenas o código e o diagnóstico do paciente. O restante é sujeira. 

<img width="465" alt="image" src="https://user-images.githubusercontent.com/81119854/207872936-27957ba1-eca2-4891-8949-692b2224a50d.png">

- Ao carregar a planilha .csv no Tableau, o Tableau pode interpretador o separador de texto como sendo o carcter espaço, daí ele separa as informações em mais de uma coluna. Contudo, queremos apenas a coluna Diagnosis.

<img width="1519" alt="image" src="https://user-images.githubusercontent.com/81119854/207873527-fd033710-39e8-4d52-8e2e-1cc543d6a615.png">

- Para corrigir, seguimos a sequência de passos:

1. Propriedades de arquivo de texto.

<img width="1003" alt="image" src="https://user-images.githubusercontent.com/81119854/207874624-4e7a5c29-3f3d-4cd4-b128-efdfdeeccf8f.png">

2. Selecionar separador igual a Tab ou Guia (mesma coisa).

<img width="771" alt="image" src="https://user-images.githubusercontent.com/81119854/207875426-7f445d96-bb74-410a-8185-e0ab34f213ca.png">

3. Resultado: dados em uma coluna.

<img width="1524" alt="image" src="https://user-images.githubusercontent.com/81119854/207875698-c8c563bc-596c-490e-83c7-c57721cd2bfe.png">

4. Agora vamos criar um campo chamado DX. Nele, capturamos apenas o primeiro elemento de cada linha:

<img width="883" alt="image" src="https://user-images.githubusercontent.com/81119854/207878590-98e3f1fc-d718-422f-80a6-29f692a621c0.png">

- Assim, conseguimos identificar se o SEGUNDO elemento de DX se trata de um número realmente (como esperado).

<img width="626" alt="image" src="https://user-images.githubusercontent.com/81119854/207879561-61fa8fd7-1de7-40e9-9fdc-0d0747cf916b.png">

<img width="684" alt="image" src="https://user-images.githubusercontent.com/81119854/207881788-a367d33b-0095-4a34-b66f-567f5eaa254a.png">

- Para tanto, criamos uma fórmula que busca o segundo elemento de uma cadeia de caracteres e exibe ele (comprimento 1). Depois, convertemos esse valor para inteiro. Se o resultado for de fato um inteiro, então a fórmula retorna um número. Se não for, então retorna NULO. 

<img width="876" alt="image" src="https://user-images.githubusercontent.com/81119854/207882092-a8a8777a-ccc7-459c-84e9-2e98e624b3c0.png">

<img width="697" alt="image" src="https://user-images.githubusercontent.com/81119854/207883537-787b14eb-4269-49c9-8609-6f43004adf9c.png">

<img width="690" alt="image" src="https://user-images.githubusercontent.com/81119854/207883661-e6860135-37db-4424-823a-0ad7bfd20bb5.png">

- LEMBRANDO QUE, para funcionar a exibição acima, devemos colocar o campo Null Hunting como discreto (cor AZUL). 

5. Agora criamos um campo calculado para identificar quando Null Hunting é de fato nulo. Em caso afirmativo, retorna VERDADEIRO. Do contrário, retorna FALSO.

<img width="871" alt="image" src="https://user-images.githubusercontent.com/81119854/207885079-e0028a2f-b639-4fd6-94ac-9b49c3b19513.png">

<img width="803" alt="image" src="https://user-images.githubusercontent.com/81119854/207885159-20505eab-1204-428f-8d9a-3b78df715e78.png">

6. Para excluir os valores nulos, levamos a variável Exclude NULL para o campo de filtro e selecionamos apenas os campos FALSO.

<img width="999" alt="image" src="https://user-images.githubusercontent.com/81119854/207886002-e23ec9a1-2a64-4000-8932-a67ef16d6d1a.png">

<img width="769" alt="image" src="https://user-images.githubusercontent.com/81119854/207886078-eb7c6e2a-bca1-46d1-8d45-dedb4f1939de.png">

7. Agoramos vamos separar o texto do código. Para isso, basta criar um campo novo (Diagnosis Text), onde substituímos o código + espaço pelo caracter vazio dentro da coluna Diagnosis.

<img width="875" alt="image" src="https://user-images.githubusercontent.com/81119854/207887012-ffbc175e-b5ad-42d0-baa4-1f609d0524e8.png">

<img width="1445" alt="image" src="https://user-images.githubusercontent.com/81119854/207887464-026d2d2a-5381-45b9-9632-8563f221c76f.png">

8. Resultado:

<img width="816" alt="image" src="https://user-images.githubusercontent.com/81119854/207887969-ca748d52-08ed-4e5d-9fbb-5e6fd01d059a.png">

# Criando campo calculado com regex para extrair número de telefone

<img width="867" alt="image" src="https://user-images.githubusercontent.com/81119854/207933079-ad56d722-99cf-4797-bd8b-e5f5fa3bbe15.png">

<img width="857" alt="image" src="https://user-images.githubusercontent.com/81119854/207932315-d9590e85-4f1b-4da2-92ac-b34a20180fbe.png">

# Criando campo calculado com regex para extrair e-mail

<img width="870" alt="image" src="https://user-images.githubusercontent.com/81119854/207933496-fc439977-c657-4fbc-94a4-43e136c7873d.png">

<img width="1369" alt="image" src="https://user-images.githubusercontent.com/81119854/207933551-a9166b87-be21-44c9-a529-136dfbcd7bd5.png">

# Relacionamento entre tabelas

- Quando a gente arrasta uma tabela para próximo da outra, o Tableau sugere a relação automaticamente, a partir de um mesmo campo em comum entre as duas tabelas. 

<img width="821" alt="image" src="https://user-images.githubusercontent.com/81119854/208437936-bfa4dea7-bd7a-44c4-ad77-2dbf188252d9.png">

<img width="854" alt="image" src="https://user-images.githubusercontent.com/81119854/208438081-b8addca8-b0e7-401d-bb44-3636562d6529.png">

# Função TOTAL e LOOKUP com cálculo a nível de tabela

- Uma função TABLE-CALCULATION-LEVEL sempre tem que usar uma função AGGREGATE-CALCULATION-LEVEL na sua fórmula. 

- A partir da soma de vendas por clientes, conseguimos saber o valor total de vendas da tabela:

<img width="863" alt="image" src="https://user-images.githubusercontent.com/81119854/208541483-0ea3fc21-3a66-4eb3-9e3a-4c17ee15ea90.png">

<img width="888" alt="image" src="https://user-images.githubusercontent.com/81119854/208541527-3415bdc8-114d-4f7d-b978-a8a5b704e3b1.png">

- Agora vamos calcular o percentual de vendas de cada cliente por dia em relação ao total:

<img width="889" alt="image" src="https://user-images.githubusercontent.com/81119854/208542128-d3c09a6d-8a56-4530-bc68-dda02d9ab2dd.png">

- Antes de exibir os valores, precisamos alterar o tipo da variável percentual:

<img width="566" alt="image" src="https://user-images.githubusercontent.com/81119854/208542232-50a54068-e1f6-47ee-9a35-fb2b6bb43b72.png">

<img width="485" alt="image" src="https://user-images.githubusercontent.com/81119854/208542294-7cf53ad0-99b1-4e92-9734-ed04ec0f3938.png">

<img width="1258" alt="image" src="https://user-images.githubusercontent.com/81119854/208542385-b3a624b9-ff96-4613-b0a0-f03a09b9c958.png">

- Se quisermos exibir o valor do percentual de vendas dos 2 últimos dias de dezembro em relação ao total de vendas, fazemos: (1) calculamos a diferença de dias em relação ao último dia de dezembro; (2) aplicamos um filtro em que a diferença seja 0 (31 de dezembro) a 1 (30 de dezembro):

<img width="854" alt="image" src="https://user-images.githubusercontent.com/81119854/208548925-1ee457d5-b8e2-489e-a9f9-4eda334ef83b.png">

<img width="558" alt="image" src="https://user-images.githubusercontent.com/81119854/208548973-0557feec-a5e1-4a4a-9067-7f75d30ab133.png">

<img width="848" alt="image" src="https://user-images.githubusercontent.com/81119854/208549466-2e599ba4-9170-4876-aaab-8d64c9873249.png">

- Quando usamos LOOKUP para diferença de dias, o resultado final oculta linhas da tabela, mas não exclui. Quando usamos apenas a função MAX, o filtro exclui linhas da tabela e calcula um novo total (que está errado): 

<img width="770" alt="image" src="https://user-images.githubusercontent.com/81119854/208549501-3eee4b33-80f8-4cf5-8e5b-53652babafba.png">

# Função PREVIOUS (TABLE-CALCULATION-LEVEL)

- Vamos definir o orçamento como sendo 5% maior a cada ano a partir de 2017. Usando PREVIOUS:

<img width="877" alt="image" src="https://user-images.githubusercontent.com/81119854/208674883-acaf6c25-488a-480e-a478-2f4e2b47ebfb.png">

- Usando LOOKUP:

<img width="872" alt="image" src="https://user-images.githubusercontent.com/81119854/208675017-5928a090-f00c-42c7-949f-5eee33976196.png">

- Resultado:

<img width="665" alt="image" src="https://user-images.githubusercontent.com/81119854/208675087-0f2ff267-0e4f-4bcf-bddc-059c9a056bf7.png">

- (1) PREVIOUS pega o primeiro valor (ano de 2017) de vendas e depois faz o cálculo em cima das linhas anteriores do orçamento. Esse tipo de cálculo pode ser usado como projeção do orçamento a longo prazo. (2) Usando LOOKUP, o cálculo é feito em cima de cada linha de vendas. Esse cálculo pode ser usado como cálculo de curto prazo. 

# Função RUNNING

- Vamos aplicar as funções RUNNING_MIN, RUNNING_MAX e RUNNING_AVG em cima do total de vendas. 

<img width="868" alt="image" src="https://user-images.githubusercontent.com/81119854/208682754-bafd26fc-6708-4037-bdf3-2aefa99b5400.png">

<img width="867" alt="image" src="https://user-images.githubusercontent.com/81119854/208682847-efd4019e-f0ec-4123-8ca1-a4c5c4e61b51.png">

<img width="864" alt="image" src="https://user-images.githubusercontent.com/81119854/208682939-6d29eec8-893f-49ce-ac43-b9f7c1d3fe4c.png">

<img width="733" alt="image" src="https://user-images.githubusercontent.com/81119854/208683008-e3223db8-aff3-412b-a2bd-aeacc5e6a713.png">

- Cada linha com a função RUNNING aplicada na tabela acima considera os valores de vendas de todas as linhas anteriores. A primeira linha retorna o valor da primeira linha. 

<img width="1249" alt="image" src="https://user-images.githubusercontent.com/81119854/208685430-fb05baba-6290-43e8-be1f-fa401f41b578.png">

# Função WINDOW (WINDOW AVG ou média móvel)

- Média móvel dos últimos 14 dias:

<img width="867" alt="image" src="https://user-images.githubusercontent.com/81119854/208693094-e0b644af-0cf2-4b18-a04e-c13ecca940f4.png">

<img width="530" alt="image" src="https://user-images.githubusercontent.com/81119854/208693248-77967084-8eb4-44ea-8e71-6ed0d109b1e2.png">

<img width="1245" alt="image" src="https://user-images.githubusercontent.com/81119854/208693904-db6f8b3d-7715-4fa4-93a2-7faf398fe243.png">

- Para pegar a média móvel, usamos o filtro e escolhemos:

<img width="296" alt="image" src="https://user-images.githubusercontent.com/81119854/208694031-edaea89a-b832-4a24-96fb-4f71c87b34e8.png">

<img width="491" alt="image" src="https://user-images.githubusercontent.com/81119854/208694135-68e66d1a-aef9-4642-9606-6f878a9e0972.png">

<img width="1419" alt="image" src="https://user-images.githubusercontent.com/81119854/208694180-60d1131f-236d-49ad-95fc-74e0df4e365c.png">

- Inverter a ordem dos valores das medidas:

<img width="161" alt="image" src="https://user-images.githubusercontent.com/81119854/208694526-0b790ff3-7da1-4412-bd6e-521b84e58fc6.png">

<img width="1562" alt="image" src="https://user-images.githubusercontent.com/81119854/208694571-7ca9717e-50c1-4e21-b5a1-77451bb2bcb4.png">

# Sintaxe IF no Tableau

<img width="692" alt="image" src="https://user-images.githubusercontent.com/81119854/208736497-189aab46-eb3a-43f3-8b97-c90ab1360c7e.png">
