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

# Funções FIRST e LAST

- Identificam o primeiro e o último valor de uma sequência. Pelo FIRST, o primeiro valor é 0 e diminui sequencialmente. Pelo LAST, o último valor é 0 e aumenta sequencialmente.

<img width="880" alt="image" src="https://user-images.githubusercontent.com/81119854/208744328-355afb71-1c1f-49bc-a429-086fdd438f82.png">

<img width="859" alt="image" src="https://user-images.githubusercontent.com/81119854/208744382-1c6c6a3f-d09d-4566-92ff-c1b9fe15b5e1.png">

<img width="862" alt="image" src="https://user-images.githubusercontent.com/81119854/208744458-69c0b21c-8ae7-4c65-b876-fa06c6fc5f4a.png">

<img width="581" alt="image" src="https://user-images.githubusercontent.com/81119854/208744992-9fba2809-57ad-4280-a20b-df0bf91831a1.png">

<img width="821" alt="image" src="https://user-images.githubusercontent.com/81119854/208746044-45fd2f91-9566-4d04-9ad0-e6b90b591c54.png">

- Se colocarmos o campo Teste da Posição como filtro, podemos filtrar apenas os verdadeiros, ou seja, o primeiro e o último dia de compra para o produto mais vendido da nossa base de dados. 

<img width="595" alt="image" src="https://user-images.githubusercontent.com/81119854/208747291-b8420b4d-530b-4275-b15e-12d2e214ef57.png">

<img width="1038" alt="image" src="https://user-images.githubusercontent.com/81119854/208747378-efa67a0c-74f1-4682-aab7-14e05c0ad1ed.png">

# Função INDEX

- Precisamos identificar os estados que possuem mais de 50 códigos postais diferentes. 

<img width="882" alt="image" src="https://user-images.githubusercontent.com/81119854/208972000-1274c106-e983-441c-9f8b-9fe9d51c8b51.png">

<img width="739" alt="image" src="https://user-images.githubusercontent.com/81119854/208972102-dd0c8542-6bf0-4199-86f3-598595092aa9.png">

- Mudamos o cálculo do índice para enumerar pelo código postal:

<img width="602" alt="image" src="https://user-images.githubusercontent.com/81119854/208972237-b6c645a7-2344-42b2-92bd-51f857f8bfa7.png">

<img width="520" alt="image" src="https://user-images.githubusercontent.com/81119854/208972281-60800026-68a4-4e65-8515-b4d5780e777d.png">

- Agora criamos um filtro com índice. Clicamos em OK. É o filtro que queremos.

<img width="1054" alt="image" src="https://user-images.githubusercontent.com/81119854/208972604-bdfb26cc-d3f7-4569-9e2d-53e37a38e5b5.png">

- Contudo, o cálculo desse filtro também deve ser feito usando o código postal. Nesse caso, estados com mais de 50 códigos postais, ou seja, com índice acima de 50.

<img width="518" alt="image" src="https://user-images.githubusercontent.com/81119854/208972837-32b8c75b-70a9-4ad9-b603-80960e792c1c.png">

<img width="987" alt="image" src="https://user-images.githubusercontent.com/81119854/208972927-492e536e-35c3-40ff-8ff1-e92566d66d80.png">

- Resultado: Califórnia e Texas.

<img width="631" alt="image" src="https://user-images.githubusercontent.com/81119854/208972998-3cab5c93-1166-461d-b98d-4eeb58a431a4.png">

# Função RANK

- Vamos apresentar os três maiores valores de venda de produtos de cada região. 

<img width="746" alt="image" src="https://user-images.githubusercontent.com/81119854/208981934-d077bcd0-fbeb-4b90-a33a-0e0c40817455.png">

<img width="692" alt="image" src="https://user-images.githubusercontent.com/81119854/208982229-7f160983-5547-4708-9c67-06ddee85728a.png">

- Adicionamos o campo Rank como linha e mudamos seu tipo para discreto:

<img width="743" alt="image" src="https://user-images.githubusercontent.com/81119854/208982403-23b46dcf-ff47-4f6d-b9a6-7689b3cff099.png">

- Mudamos sua ordem para ficar na frente do nome do produto: 

<img width="697" alt="image" src="https://user-images.githubusercontent.com/81119854/208982502-c28cd270-ca99-4b3a-9482-5b5c6b3ea9c3.png">

- Temos que classificar o nome do produto de forma decrescente em relação à soma de vendas:

<img width="329" alt="image" src="https://user-images.githubusercontent.com/81119854/208982747-85b4c1b3-9a8d-46f8-b2a3-76d02df9ef63.png">

- Escolhemos uma barra para visualização: 

<img width="1225" alt="image" src="https://user-images.githubusercontent.com/81119854/208983404-8b07eb50-d916-4f7e-bfbd-1eb65c40d773.png">

- Escolhemos o campo Rank como filtro. Depois escolhemos o cálculo usando o nome do produto: 

<img width="1064" alt="image" src="https://user-images.githubusercontent.com/81119854/208983584-b25d6ee3-370d-4b65-8c57-c5ded92571de.png">

- Na sequência, escolhemos apenas as três primeiras posições do rank: 

<img width="603" alt="image" src="https://user-images.githubusercontent.com/81119854/208983783-2c6324f1-d0ed-4f6d-b576-def7b7887fc8.png">

<img width="1403" alt="image" src="https://user-images.githubusercontent.com/81119854/208984137-2efa1117-f044-4e7f-94a8-1d56c10197ec.png">

- Lembrar de rankear em relação ao nome do produto (cálculo usando). 

# Função SIZE

- Vamos identificar os estados com vendas para 5 ou menos cidades. 

<img width="719" alt="image" src="https://user-images.githubusercontent.com/81119854/209023363-39681f43-fd88-4ac9-9b2b-61e231e239c9.png">

<img width="866" alt="image" src="https://user-images.githubusercontent.com/81119854/209023336-f6b22e48-56b6-43cf-88ef-d8503138df31.png">

- Ao adicionarmos o campo size, ele retorna o número de linhas da tabela inteira:

<img width="706" alt="image" src="https://user-images.githubusercontent.com/81119854/209023508-013dfd97-33c2-4ae4-8640-602f4affa780.png">

- Nós queremos o número de cidades. 

<img width="627" alt="image" src="https://user-images.githubusercontent.com/81119854/209025820-834b3c09-06bc-4587-812d-f74f2bd43dcc.png">

- Nós queremos apenas que o valor do tamanho apareça uma única vez. Apenas na primeira linha:

<img width="569" alt="image" src="https://user-images.githubusercontent.com/81119854/209025947-8f8cc331-955a-45ac-9022-141c83c75aa8.png">

<img width="858" alt="image" src="https://user-images.githubusercontent.com/81119854/209025981-4dee69be-392f-4c26-a14f-75d996502f00.png">

<img width="842" alt="image" src="https://user-images.githubusercontent.com/81119854/209026022-66ccad80-1fe5-465b-a0eb-ffdce632c78a.png">

- Mas queremos apenas os estados com 5 ou menos cidades. Estados que venderam para 5 ou menos cidades. Criamos um filtro para no máximo 5 cidades:

<img width="575" alt="image" src="https://user-images.githubusercontent.com/81119854/209026492-33b3ef2d-f3ef-44e2-9608-86b381f192d6.png">

<img width="690" alt="image" src="https://user-images.githubusercontent.com/81119854/209026534-f7934733-6647-4fd6-8852-70780513e6a5.png">

- Lembrando que o contador de cidades deve estar a nível de cidade em marcas, filtro e como campo calculado. 

- Não queremos ver cidade:

<img width="507" alt="image" src="https://user-images.githubusercontent.com/81119854/209026853-e63aa99a-80bf-4b2f-93ae-1fbdabe4a627.png">

# Cálculo direcional de linhas

<img width="668" alt="image" src="https://user-images.githubusercontent.com/81119854/209149900-ae79180e-f8ca-4f63-a051-bc339ea8396e.png">

<img width="893" alt="image" src="https://user-images.githubusercontent.com/81119854/209150069-2c1d289c-3f13-467c-a1f9-0a68328cb2c3.png">

<img width="880" alt="image" src="https://user-images.githubusercontent.com/81119854/209150151-71ce2b54-dc6e-403b-a500-5fb00f0ca0ca.png">

<img width="908" alt="image" src="https://user-images.githubusercontent.com/81119854/209150204-c66a7824-52dc-4c64-a90f-0f819c5054bc.png">

<img width="895" alt="image" src="https://user-images.githubusercontent.com/81119854/209150326-fa492c57-ec2b-463a-a45f-aec612334e70.png">

# Cálculo direcional de linhas e colunas

- Arrastamos para colunas o campo segmentos: 

<img width="671" alt="image" src="https://user-images.githubusercontent.com/81119854/209155720-0884f207-6839-4152-b6a9-18f2abee3f0b.png">

- Combinações:

<img width="1039" alt="image" src="https://user-images.githubusercontent.com/81119854/209156203-d70f63cb-0d39-499c-9754-5c91fd9a2a29.png">

<img width="1010" alt="image" src="https://user-images.githubusercontent.com/81119854/209156281-39900fea-06f0-44c0-a80d-ab8ce94b02ee.png">

<img width="1019" alt="image" src="https://user-images.githubusercontent.com/81119854/209156377-848b19c1-cfbc-44aa-a0a7-b3cdf6714fe9.png">

<img width="1017" alt="image" src="https://user-images.githubusercontent.com/81119854/209156450-25b6f5ca-45a5-4587-bac9-dcdfc4427576.png">

<img width="1006" alt="image" src="https://user-images.githubusercontent.com/81119854/209156548-b091b767-0fcd-4555-9321-d24c0f7ffcdf.png">

<img width="1007" alt="image" src="https://user-images.githubusercontent.com/81119854/209156782-63abb08e-16e6-4a88-af1c-ddc5b044b31f.png">

<img width="1007" alt="image" src="https://user-images.githubusercontent.com/81119854/209156851-e292a46b-408f-4326-903e-50d2d60dc87a.png">

# Praticando direção

- Vamos criar o campo percentual de vendas direção 1.

<img width="839" alt="image" src="https://user-images.githubusercontent.com/81119854/209192587-91d911c0-0c19-47f7-bb7b-5b0b463f1afc.png">

<img width="507" alt="image" src="https://user-images.githubusercontent.com/81119854/209192868-d8767269-b7ff-4af7-be2e-8440c4ba33b7.png">

- Vamos cruzar região com modo de envio. 

<img width="616" alt="image" src="https://user-images.githubusercontent.com/81119854/209193016-5ac81bc5-0592-4368-ab59-489c0484a2e6.png">

- O percentual de vendas da tabela acima está relacionado com a tabela inteira. Para sabermos o percentual apenas do modo de envio dentro de cada região, primeiro criamos um novo campo (direção 2) e depois adicionamos esse campo na tabela a nível de painel.

<img width="1131" alt="image" src="https://user-images.githubusercontent.com/81119854/209193633-46d092d5-a73b-4edb-8646-75ec3e07c41c.png">

<img width="739" alt="image" src="https://user-images.githubusercontent.com/81119854/209193697-14062fab-c64f-45db-b135-8e3e49d1feed.png">
