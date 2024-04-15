# Laboratório Azure Cognitive

## Descrição
Esse projeto visa demonstrar a utilidade do Azure Cognitive Search utilizando AI Search para indexação e consulta de dados. 

## Problema
No exemplo realizado no laboratório, onde podemos acompanhar no site https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html , uma empresa a nível nacional de venda de cafés precisava de uma solução de mineração a partir de dados coletados dos seus clientes. Através desses dados coletados o analista teria que apresentar insigths, soluções que pudessem ajudar a empresa a continuar líder no mercado.

## Solução
De forma bem genérica podemos pensar em um jeito de incluir as opiniões dos clientes na nuvem, e após a inclusão desses dados gerar insights e/ou soluções que podem ser encontradas a partir da leitura dessa opiniões.

A coleta dos dados é armazenado em um "storage account", que  é o local onde será feito o upload dos dados coletados. No exemplo esses dados foram coletados através de documentos tipo ".docx". Mas antes de criar essa conta de armazenamento foi criado inicialmente um recurso de pesquisa de IA do Azure, pois nessa etapa será gerenciado a indexação e consulta. Essa primeira etapa é importante pois uma consulta só consegue funcionar corretamente com recursos de indexação e estará dsponível para outros serviços da Azure. 
A próxima etapa foi a cricação de um recurso de serviços da IA Azure, onde aqui a Azure já deixa soluções prontas de inteligência artificial de fácil acesso para usuário. E logo após a criação deste serviço foi criada a conta de armazenamento.
Seguindo um passo a passo nesta do solução fo feita o seguinte:
* Criar um recurso de pesquisa de IA do Azure
* Criar um recurso de serviços de IA do Azure
* Criar uma conta de armazenamento

Depois desses passos os dados já estarão armazenados e pode-se tirar as informações(insights) dessas opiniões.


## Conclusão
Essa ferramenta do Azure AI Search faz com que uma empresa consiga de forma simples utilizar a inteligência artificial para agregar conhecimeto sem ter uma equipe própria para desenvolver essas soluções. As soluções estão prontas de forma que a gerência pode concentrar em conseguir tirar proveito e insights e com isso evoluir cada vez mais.
