# Criando-um-Instance-Template-e-Instance-Group-Load-Balancer

Para criar um **Instance Template**, **Instance Group** e um **Google Cloud Load Balancer**, poderemos seguir os passos abaixo:

1. **Instance Template**:
   - Navegue até o menu de navegação > Compute Engine > Instance templates.
   - Clique em "Create instance template".
   - Forneça um nome, escolha a série e configure as opções avançadas conforme necessário.

2. **Instance Group**:
   - Com o template criado, vá para a página de Instance Groups.
   - Crie um novo grupo e selecione o template que você criou.
   - Defina as configurações de autoescala e balanceamento de carga conforme necessário.

3. **Google Cloud Load Balancer**:
   - Acesse a página de Load Balancing no Google Cloud Console.
   - Crie um novo load balancer e selecione o tipo apropriado (HTTP(S), TCP/SSL, etc.).
   - Adicione o Instance Group como backend e configure as regras de roteamento.

Para cada etapa, podemos encontrar guias detalhados e instruções na documentação oficial do Google Cloud¹²³. Além disso, poderemos considerar usar o Terraform para automatizar a criação desses recursos, e há repositórios no GitHub que podem servir como referência⁴.

Quando tivermos todos os links e arquivos necessários, podemos organizá-los em um repositório, como solicitado. Certifique-se de incluir documentação clara sobre como usar cada recurso e como eles se integram ao seu projeto. Isso pode incluir links para o template no Figma, arquivos de configuração, scripts de automação e qualquer outra documentação relevante.

Vou fornecer exemplos práticos para a criação de um **Instance Template**, um **Instance Group** e um **Google Cloud Load Balancer** no **Google Cloud Platform (GCP)**.

## Exemplo 1: Criação de um Instance Template

1. **Instance Template**:
   - Navegue até o menu de navegação no Google Cloud Console: **Compute Engine > Instance templates**.
   - Clique em "Create instance template".
   - Forneça um nome para o template.
   - Escolha a série da máquina virtual (por exemplo, `n1-standard-1`).
   - Configure outras opções avançadas conforme necessário.

## Exemplo 2: Criação de um Instance Group

1. **Instance Group**:
   - Com o template criado, vá para a página de **Instance Groups**.
   - Crie um novo grupo e selecione o template que você criou.
   - Defina as configurações de autoescala e balanceamento de carga conforme necessário.

## Exemplo 3: Criação de um Google Cloud Load Balancer

1. **Google Cloud Load Balancer**:
   - Acesse a página de **Load Balancing** no Google Cloud Console.
   - Crie um novo load balancer e selecione o tipo apropriado (HTTP(S), TCP/SSL, etc.).
   - Adicione o Instance Group como backend e configure as regras de roteamento.

Lembre-se de consultar a [documentação oficial do Google Cloud](https://cloud.google.com/compute/docs/instance-groups/adding-an-instance-group-to-a-load-balancer) para obter detalhes específicos sobre cada recurso e configuração. Além disso, poderemos considerar usar o **Terraform** para automatizar a criação desses recursos. Há repositórios no [GitHub](https://github.com/GoogleCloudPlatform/terraform-google-load-balanced-vms/) que podem servir como referência.

Certifique-se de testar tudo cuidadosamente para garantir que o sistema esteja funcionando como esperado antes de considerar o desafio concluído.
