# Fourth Coffee Azure AI Search Solution

## Descrição da Solução

- Esta solução foi desenvolvida para atender às necessidades do Fourth Coffee, utilizando recursos do Azure para aprimorar a pesquisa e enriquecer os dados na fonte. Os principais recursos necessários são um Azure AI Search, um Serviço de IA do Azure e uma Conta de Armazenamento.

## Recursos Necessários na Assinatura do Azure

- Azure AI Search:

- Crie um recurso no portal do Azure com as configurações especificadas.
Assegure que os recursos do Azure AI Search e dos Serviços Azure AI estejam no mesmo local.
Serviços de IA do Azure:

- Provisione um recurso de Serviços de IA do Azure no mesmo local do Azure AI Search.
Conta de Armazenamento:

- Crie uma conta de armazenamento com contêineres de blobs para armazenar documentos brutos.
Configuração do Azure AI Search

## Criação do Recurso:

- No portal do Azure, crie um recurso Azure AI Search com as configurações especificadas.
Aguarde a conclusão da implantação e acesse o recurso.

## Configuração do Serviço de IA do Azure:

- Provisione um recurso de Serviços de IA do Azure no mesmo local.
Aguarde a conclusão da implantação e visualize os detalhes da implantação.

## Configuração da Conta de Armazenamento:

- No portal do Azure, crie uma conta de armazenamento com os contêineres necessários.
Configure o acesso anônimo de Blob para Habilitado.
Carregamento de Documentos

## Criar Contêiner:

- No portal do Azure, crie um contêiner para armazenar avaliações de café com acesso de leitura anônimo.

## Carregar Documentos:

- Baixe as avaliações de café compactadas e extraia os arquivos.
Carregue os documentos no contêiner de armazenamento.
Indexação dos Documentos

## Configuração do Azure AI Search:

- No portal do Azure, navegue até o recurso Azure AI Search.
Selecione a opção de Importar dados para criar índices e indexadores automaticamente.

## Configuração do Assistente de Importação:

- Conecte-se ao Azure Blob Storage e configure as opções de importação.
Adicione habilidades cognitivas para enriquecer os dados.

## Configuração do Armazenamento de Conhecimento:

- Configure a projeção de imagem e selecione os campos enriquecidos desejados.
Crie um contêiner de armazenamento de conhecimento.

## Configuração do Índice e Indexador:

- Personalize o índice de destino e crie um indexador para extrair e enriquecer os dados.

## Monitoramento da Indexação:

- Volte à página do recurso Azure AI Search e monitore o status do indexador.
- Utilize o Search Explorer no portal do Azure para escrever e testar consultas, validando a qualidade do índice de pesquisa. O Search Explorer permite escrever consultas e revisar resultados em formato JSON.

## Aprendizados com o Uso de Pesquisa em IA

- O uso da pesquisa em IA proporciona:

- Enriquecimento de Dados: Habilidades cognitivas extraem informações valiosas, como locais, frases-chave, sentimentos, tags e legendas de imagens.
- Indexação Eficiente: O Azure AI Search automatiza a indexação, tornando o processo eficiente e permitindo consultas rápidas.
- Melhoria na Experiência do Usuário: Resultados enriquecidos oferecem uma experiência de pesquisa mais robusta e informativa.

## Os dados obtidos nesse artigo se encontra:

- Diretório: /insights/*
- Siga os passos descritos neste README para implementar a solução e explorar os benefícios da pesquisa em IA para o [Fourth Coffee](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html).
