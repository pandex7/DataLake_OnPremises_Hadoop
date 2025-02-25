# DataLake-On-Premises

Implementação de um Data Lake On-Premises


## About the project

Vamos implementar um projeto de um Data Lake no local. Entendendo seu conceito e diferença de um Data Warehouse.

##Why?

por que Data Lake é um conceito, não uma plataforma !!!

- Este projeto faz parte do meu portfólio pessoal, então ficarei feliz se você puder me dar algum feedback sobre o projeto, código, estrutura ou qualquer coisa que você possa relatar que possa me fazer um melhor engenheiro de dados!

Email-me: henricao_7@yahoo.com.br

Connect with me at [LinkedIn](https://www.linkedin.com/in/henrique-castro-484269203//).

## Roteiro para um lago de dados bem sucedido

As empresas hoje estão explodindo a partir de dados, incluindo dados de banco de dados, saídas de aplicativos, dados de streaming de comércio eletrônico, mídias sociais, aplicativos e dispositivos conectados à Internet das Coisas (IoT). Somos todos bem versados no Data Warehouse, projetado para capturar o núcleo dos negócios de outros sistemas de negócios, como sistemas ERP e CRM, operações de inventário e vendas que permitem aos analistas e usuários obter insights e tomar decisões importantes de negócios a partir desses dados. Mas novas tecnologias, incluindo plataformas móveis, sociais e IoT, estão aumentando volumes de dados muito maiores, expectativas mais altas dos usuários e uma rápida globalização das economias. As organizações estão percebendo que as tecnologias tradicionais não atendem às necessidades de novos negócios. Como resultado, muitas organizações estão se voltando para arquiteturas como Data Lakes, usando Apache Hadoop e outras tecnologias de Big Data. No entanto, apesar do crescente investimento em data lakes e tecnologia de big data - US $ 150,8 bilhões em 2017, um aumento de 12,4% em relação a 2016 - apenas 14% das organizações relatam implementar seu projeto de prova de conceito (PoC) de Big Data, em produção. Uma das razões para essa discrepância é que muitas organizações não veem um retorno sobre seu investimento inicial em tecnologia e infraestrutura de big data. Isso ocorre geralmente porque essas organizações não conseguem fazer a coisa certa, ficando aquém quando se trata de projetar os dados corretamente. Em (muitos) em outros casos, não há cultura baseada em dados. Em última análise, essas organizações criam "pântanos" de dados (Data Swamps) que são realmente úteis apenas em casos de uso exploratório ad-hoc (algo ainda incomum em muitas empresas, embora seja usado em pesquisa e desenvolvimento). Para organizações que vão além de um PoC, muitos estão unindo a flexibilidade de um Data Lake com boas práticas de governança e controle de dados. Essa é a chave para obter um investimento significativo em tecnologia ROI para Big Data.

Se você (Engenheiro de Dados) perguntar aos seus analistas e cientistas de dado quais dados eles querem usar no futuro, eles provavelmente dirão "Tudo disponível". Mas realmente precisamos de todos os dados que canor apenas do que é relevante para resolver determinado problema de negócios? Em geral, usamos o Data Lake para armazenar: 

• Dados transacionais brutos 
• Dados semiestruturados e não estruturados 
• Dados de streaming 
• Dados históricos que não foram migrados para sistemas de produção 
• Dados que podem ser úteis para análise no futuro

![12](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/12.png)

Os Lagos de Dados tornam-se pântanos de dados se não forem gerenciados de forma correctida. Certifique-se de que seu Data Lake tenha as seguintes características:

• Arquitetura para atender às metas de negócios da empresa 

• Gerenciamento para proteger dados 

• Integração a ser alimentada com dados de diferentes fontes

• Acessibilidade para "autoatendimento" e para oferecer aos Cientistas de Dados a oportunidade de aplicar análises em tempo real

#O Scripts para instalação e configuração do nosso Data Lake segue em anexo!!!

![1](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/1.png)

## Data Warehouse

Dados > dados estruturados e processados antes de carregar no banco de dados 

Processamento > esquema de dados gerado no momento da escrita. 

Armazenamento de alto > para grandes volumes de dados. 

Agilidade > Pouca configuração ágil e fixa. 

A segurança > estratégias de segurança maduras. 

Os usuários > Analista de Negócios, BI e Cientista de Dados.

## Data Lake

Dados estruturados > Estruturados, Semiestruturados e Não Estruturados. Dados brutos. 

Processamento > esquema de dados gerado no momento da leitura. 

O armazenamento > projetado para ser de baixo custo, independentemente do volume de dados. 

Agilidade > muito ágil. Pode ser configurado e reconfigurado conforme necessário. 

Segurança > Você ainda precisa melhorar sua segurança de dados e modelo de acesso. 

Os usuários > Cientista e Analista de Dados.

![2](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/2.png)

## O que é Dados Corporativos?

Dados Corporativos significam todo e qualquer dado mantido por qualquer uma das empresas, incluindo, mas não se limitando, dados relacionados às suas finanças, impostos, funcionários, clientes, fornecedores e produtos ou serviços.

## Construir a infraestrutura certa é fundamental
Portanto, deve ser:

• Ágil

• Segure-se

• Compatível

• Gerenciável

Qual é o custo de implementar um Data Lake On-Premise?

![3](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/3.png)

Qual é o custo da implantação de um Data Lake na Nuvem?

![4](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/4.png) 

![5](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/5.png)

Essa é uma visão geral, mas tem outros custos outros problemas, como se você quiser parar de usar o Data Lake e basta clicar em um botão está pronto. Não há problema com queima de HD ou depreciação de equipamentos e etc... e ainda tem uma VPN para garantir maior segurança.

![6](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/6.png)

Data Lake é o ponto focal de uma estratégia de gerenciamento de dados. Basicamente é um repositório central é onde você vai trazer os dados do processo de armazenamento de fontes mais variáveis, analisar e agir com esses dados eles podem ser descartados podem ser armazenados em um segundo passo do que você queria manter a história, mas basicamente e criar o ponto central do armazenamento de dados. Permitindo o que em inglês é o SCV (Single Customer View) ou seja, um único ponto de vista dos dados para o usuário final e que o usuário final pode estar com os mais variados aplicativos de um aplicativo de BI um aplicativo de aprendizado de máquina eventualmente uma ferramenta para criar visualização de relatórios e dashboards e etc... 

O volume de dados vem aumentando significativamente ao longo das décadas, é claro que estratégias anteriores de armazenamento e gerenciamento de dados não são mais suficientes para não usar mais Data Marts, Data Warehouse isso não é suficiente porque os dados mudaram suas características vem em outro formato outra velocidade em outro volume e precisamos de novas estratégias é a entrada do Data Lake. Data Lake está se tornando o ponto focal de uma estratégia de gerenciamento de dados!!!

![7](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/7.png)

Uma das maiores empresas de tecnologia do mundo concorda com essa visão. Olhe para este diagrama da Microsoft. Olha, o Azure Data Lake está no centro da estratégia de dados do ambiente do Microsoft Cloud. Você traz os dados para o Data Lake e lá você distribui para outros aplicativos ou outros repositórios e, em seguida, transforma esses dados em informações que serão úteis para a tomada de decisões

![8](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/8.png)

##Data Lake Conceito

O Term Data Lake pode ser definido com um vasto repositório de uma variedade de dados brutos em toda a empresa, que podem ser comprados, processados, analisados e entregues. Data Lake Não é um banco de dados DL é um armazenamento de dados!!! Um Data Lake adquire dados de múltiplas fontes em uma empresa em sua forma nativa e, portanto, tem formas internas modeladas nos mesmos dados para múltiplos propósitos. Os dados podem ser de qualquer tipo, desde dados estruturados ou semiestruturados até dados completamente não estruturados. Espera-se que um Data Lake resulte em significados e insights relevantes para os negócios a partir das informações extraídas dos dados, usando vários algoritmos de análise de máquina e aprendizado. Data Lake não é apenas para armazenamento que o DL é construído para processar e analisar esses dados, seja usando uma ferramenta de BI, por exemplo, ou usando uma ferramenta para modelos preditivos. Um Data Lake resulta implicitamente em um modelo de negócio para negócios, o que é bom para resolver problemas de negócios muito específicos. Um Data Lake pode representar uma entidade ao máximo com base em informações coletadas de vários sistemas que possuem esses dados. Com o Data Lake, conseguimos extrair informações de uma única entidade amostral: Quando você cria um Data Warehouse, você coleta dados de algumas fontes, então organiza esses dados e então você alimenta a DW eu tenho todas as informações sobre cada entidade lá na DW? Você pode imaginar a entidade cliente que eu tenho todos os dados que eu preciso sobre o cliente lá na minha DW? Tenho registro no meu sistema RP tenho os cliques que o usuário faz no meu site tenho os e-mails que meu usuário envia para minha empresa tenho as faturas de pagamento que esse cliente fez eu tenho as faturas e procedimento de entrega dos produtos para esse cliente tudo isso é informação da entidade cliente tudo isso está no Data Warehouse? Provavelmente não na grande maioria dos casos não é porque tem uma limitação física para você montar o DW. Quando você trabalha com o Data Lake eu posso preferir extrair tudo o que tenho de cada entidade e armazená-lo no meu Lago de Dados, Entidade cliente, produto, fornecedor e qualquer outra entidade que seja interessante para a minha análise eu extraio tudo o que tenho cada interação desse usuário com a minha empresa então eu armazená-lo no DL e depois realizar análise de dados e criar modelos preditivos. Ser capaz de prever o que o cliente pode comprar no próximo mês ou que tipo de produto o cliente gostaria de receber!!! Uma verdadeira mudança de jogo!!! É muito trabalho, mas o resultado final pode ser maior rentabilidade diferencial competitiva entre outras vantagens para a empresa. Data Lake não é a solução ideal para qualquer empresa! IMPORTANTE LEVAR ISSO EM CONSIDERAÇÃO!! Se a empresa não tem uma cultura Data Driven, ou seja, uma cultura baseada em dados e nem está planejando ter em um futuro próximo, então a empresa não será capaz de extrair da Data Lake o melhor que tem a oferecer. O Data Lake é o centro de uma estratégia de gerenciamento de dados, portanto, se a empresa não estiver preocupada em gerenciar seus próprios dados, o Data Lake será apenas mais um repositório. Só será útil como qualquer tecnologia se a empresa estiver preparada para usar uma tecnologia, por isso sempre leve isso em consideração!!!


![9](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/9.png)

## Benefícios para a empresa

Modelo de armazenamento único que descreve significativamente a representação dos dados. Centralização da coleta e armazenamento de todos os dados gerados pela empresa. Um único ponto de controle permite uma cultura baseada em dados.

## Vantagens Técnicas.

Melhor governança de dados. Permite que você trabalhe com análises preditivas através de Machine Learning e IA. Permite a construção de sistemas de recomendação e outras aplicações analíticas. Rastreamento e consistência de informações. Análise de dados históricos.

## Desvantagens Técnicas

Se não for bem gerenciado, Data Lake resulta em um Pântano de Dados

Requer um controle de segurança rigoroso, uma vez que todos os dados gerados pela empresa estarão em um único repositório Grande quantidade de armazenamento Necessidade de clusters de computador para armazenamento e processamento de dados distribuídos.

## Arquitetura do Lago de Dados

Lembrando sempre que o Data Lake não é um produto ou uma ferramenta do Data Lake é um conceito assim como o Data Warehouse é um conceito que você pode implementar um DW com o banco de dados Oracle com SQL Server, Postgre com o MySql você pode implementar um DW de várias maneiras diferentes, bem como um Data Lake pode ser implementado de várias maneiras diferentes com diferentes produtos e tecnologias diferentes. 10

Você tem duas abordagens para olhar para a arquitetura DL: Dividir por camadas. Olhe para os serviços que compõem um DL.

## <Gestão de Metadados, Rastreabilidade, Hierarquia e Linhagem>

Aquisição de dados: Os dados podem existir de múltiplas formas e requerem diferentes técnicas de extração. Processamento de dados: Os dados adquiridos podem exigir processamento para gerar informações úteis. Podemos armazenar os dados brutos e criar uma réplica com dados processados. Análise de dados: Os dados são analisados em demana, em tempo real ou em lote. Armazenamento de dados: Os dados são armazenados antes e/ou após a análise. Esta não é uma ordem obrigatória é apenas parar didaticamente mostrando o que é feito em uma arquitetura do Lago de Dados.

Um Lago Data primeiro tem que adquirir dados de algum lugar. Uma vez adquiridos os dados, temos que processá-los "Lembrando que você pode armazenar os dados e só então processar. Sim, você pode. Quem faz e implementa a arquitetura é você" Estou colocando aqui o ideal dependendo dos problemas de negócios a serem resolvidos. Eu vou processar esses dados de alguma forma ele pode vir do streaming (em tempo real) ou pode vir em formato de lote, ou seja, dados em lote dependendo de como foi a etapa de aquisição. Em seguida temos a análise de dados onde vamos extrair insights daquele dado que foi armazenado pela última vez eu tenho armazenamento e não precisa ser o último você pode adquirir o processo de dados e armazená-lo e, em seguida, analisar você pode colocar o armazenamento em qualquer etapa. -Muitas empresas optam por não armazenar diretamente os dados porque o volume é muito grande dependendo dos dados que estão chegando em tempo real se eu perder os dados em tempo real dependendo do tipo de análise que estou tentando fazer os dados não servem mais nada. -Imagine que você está fazendo uma análise de sentimento em tempo real no Twitter durante um debate para a Presidência da República que você quer saber como os humores durante o debate não me interessam depois e não antes que eu queira durante o Debate porque em cada intervalo do debate os candidatos conversam com seus assessores eles podem de acordo com o retorno do público mudar seu comportamento durante o Debate. Então, neste caso, não faz sentido dizer que o armazenamento será antes depende da arquitetura que está sendo implementada se a empresa quiser trabalhar com análise de dados em tempo real que adquiriu processos, ou seja, transforma esses dados de alguma estrutura aplica Machine Learning e, em seguida, entrega o resultado

## Aquisição de Dados

O primeiro ponto é que a empresa defina quais dados serão armazenados no Data Lake. Não adianta dizer que você quer todos os dados que não é como os gerentes trabalham muito e as empresas que eles vão tentar dizer isso. Quais dados você gostaria de ter para análise para resolver seus problemas de negócios? Você já sabe que tudo começa na definição do problema a ser resolvido.

## Processamento e Gestão de Dados

A definição de qual processamento e como será feito não é uma decisão técnica e puramente uma definição da área de negócio. Você está construindo um sistema de recomendação? Você está construindo um aplicativo de Machine Learning? Cada uma dessas aplicações exigirá um tipo diferente de processamento o que muitas empresas normalmente fazem é armazenando os dados em seu estado bruto e já aplica algum ETL durante a aquisição da Faze para que você adquira os dados já armazena em estado bruto e nos processos de próxima etapa e já entrega para uma ferramenta de análise, pois então você acelera o tempo de processamento de dados e consequentemente entregará sua aplicação analítica. Nesta etapa e onde basicamente usamos o ETL T lembrando que o ETL funcionará da mesma forma que no Data Warehouse. A mesma coisa que nos permite extrair dados de diferentes fontes e formatos diferentes transformar os dados conforme necessário e já colocar em seu Data Lake prepara-os para análise. Muitas pessoas consideram que a vantagem do Data Lake é que você os deu em formato bruto. Sim, sem dúvida é uma grande vantagem, mas dados brutos não são muito úteis para análise eu tenho que processar esses dados de alguma forma se a empresa já é capaz de fazer isso durante o ETL ideal se ele não armazenar de alguma forma em Data Lake e, em seguida, alguma ferramenta ou um cientista de dados vai olhar para esses dados e dar alguma estrutura para eles,  processo e, em seguida, preparar para o processo de análise em geral. Não há análise de dados não estruturadas, você sempre dará uma estrutura aos dados antes de analisarmos. Mesmo quando você coleta dados não estruturados antes de aplicar a uma ferramenta analítica eu primeiro dou uma estrutura em Data Lake eu posso escrever em estado bruto, mas eu tenho que processar em algum momento ou durante a fase de aquisição ou imediatamente após ou mais tarde ao fazer a análise!!!

## Análise de dados

Esta é a parte mais importante de todo o processo que você criou um Data Lake exatamente para analisar os dados e ajudar a empresa na tomada de decisões

## Armazenamento de dados

O Data Lake tem um objetivo muito maior do que armazenar dados, pode ser apenas parte de um pipeline onde eu adquiro, processo, analiso, armazeno o resultado e continuo nesse ciclo para que a empresa continue recebendo os insights de diferentes fontes.

Uma pergunta existente é: posso coletar todos os dados de uma empresa? Isso é realmente importante para análise? Essa é a pergunta a se fazer. Preciso dos registros dos servidores para gerar um sistema de recomendação para os produtos do site da empresa? Se a resposta for sim, então eu preciso dos dados! Se a resposta for não, não preciso coletar esses dados. Preciso de dados das redes sociais para criar um sistema de recomendação de vendas? Se a resposta for sim, eu coleciono de outra forma não e vá em frente!!! -Se você não tem uma estratégia bem definida para analisar esses dados você vai armazenar porque o volume de dados é muito grande e você vai armazená-lo, armazenar lá chega um momento em que a empresa vai ter que descartar os dados para liberar algum espaço de disco ou os dados são tão antigos que não tem muito uso do aplicativo que eu estou fazendo
Metadados e Gerenciamento de Segurança
Onde vamos identificar os dados que eventualmente serão armazenados no Lago de Dados ou analisados ou processados o que é esse metadados? Data de criação desse ponto de dados, data em que esses dados foram armazenados ou inseridos em seu Data Lake, data em que foram processados, data em que foi analisado, a fonte de dados que é muito importante no DW também incluímos esse tipo de metadados que você pode colocar uma Coluna por exemplo lá na DW ou você pode colocar isso em informações para a parte,  ou seja, de onde esses dados vieram? Qual foi a fonte exata da qual extraímos esse conteúdo e depois fizemos o processamento. Essas informações que descrevem os dados são o que chamamos de metadados se não, estou apenas jogando coisas dentro do lago de dados e perde completamente o propósito de você ter uma gestão eficiente de como os dados são identificados que é o gerenciamento de metadados!!!

-Rastreabilidade: Uma vez que você tenha criado algum processo de gerenciamento de metadados agora eu posso rastrear esses dados dentro do meu Data Lake. Veja o Data Lake pode ter terabytes, tetabytes em tamanho eu preciso ser capaz de rastrear o ponto de dados como ele se move para o Lago de Dados quando foi inserido como dados brutos, quando foi processado, quando foi analisado, quando eventualmente foi descartado eu posso escrever essas informações e mantê-la como algum tipo de história de metadados entre várias outras opções. Agora existe praticamente uma ciência em torno do gerenciamento de metadados (Metadata Management) que é exatamente você controlar tudo isso é para garantir informações sobre seus dados. -Também temos hierarquia e linhagem que ajudamos a definir o ciclo de vida dos dados dentro do nosso Data Lake, bem como no Data Warehouse o raciocínio não é muito diferente. -Finalmente, a questão da Segurança - Embora a linha azul não faça parte da arquitetura do Data Lake, ela suporta a arquitetura DL.

## Qualidade de dados e ciclo de vida


Se o lixo entrar, haverá lixo. Qualidade é algo a ser considerado durante todo o processo. Como posso estabelecer um critério de um padrão de qualidade que também não é fácil! Normalmente durante a fase de aquisição e processamento podemos implementar algumas práticas com o objetivo de tentar aumentar a qualidade dos dados ou pelo menos verificar a qualidade dos dados que estão entrando no Lago de Dados podemos, por exemplo, criar algum tipo de filtro, estabelecer alguma regra no ETL, já podemos aplicar algum procedimento de limpeza e transformação nos dados da amostra:  Imagine que você está coletando dados de redes sociais e esses dados contêm um monte de emoticons (Emoji) que é relevante para o seu processo de análise? Na maioria das vezes não para que eu já possa descartar esses caracteres antes mesmo de inserir os dados no Lago de Dados. 11

-Dados lógicos > apenas apontar para acessar os dados em cada empresa -Ágil> Rapidamente entregar interativamente algo -Arquitetura de dados> basicamente e você modela os conceitos de negócios - O data warehouse lógico > a governança dos dados para o propósito específico para isso eu posso usar um DW -Enterprise Access Point> Com um único ponto de controle de dados e ponto de governança -Data Virtualização > eu preciso de alguma forma garantir os sistemas estáveis e o Data Lake independente arquitetura e o ciclo de vida dos dados dependerão dos objetivos da empresa a empresa criará um aplicativo com durabilidade de um ano? Um ano e meio? Dois? Lembre-se do ciclo de vida não e apenas do lago de dados e de toda a sua arquitetura de dados!!!


![13](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/13.png)

## O roteiro de sucesso para um Data Lake deve incluir:

Extensas capacidades analíticas 

• Fontes variadas de dados 

• Acesso a diferentes ferramentas analíticas 

• Computação intensiva para a execução de algoritmos de máquina aprendendo interoperabilidade 

• Integração com diferentes sistemas heterogêneos 

• Continuidade de negócios de processamento de eventos e mensagens 

• Alta disponibilidade e tolerância a falhas 

• Recuperação de desastres (backup e restauração) 

• Recuperação de dados (recuperação contra falhas de dados e corrupção De Custo Reduzido 

• Uso de hardware de commodities (baixo custo) 

• Baixa administração aérea 

• Alto desempenho 

• Recursos multi-locação (virtualização) de compartilhamento de recursos 

• Capacidade de gerenciar vários recursos (computacionais) a partir de um único ponto Ser capaz de reunir todos esses recursos em um Data Lake é muito difícil, mas este deve ser o Roteiro e o objetivo de qualquer organização interessada em tirar o máximo do Big Data Analytics. E você, como engenheiro, é um dos responsáveis por isso.

Referências: IDC. "Guia de Gastos Semestrais de Big Data & Analytics em todo o mundo." Gartner. "Guia de Mercado para Distribuições Hadoop." Arquitetando Data Lakes (e-book gratuito) https://www.oreilly.com/data/free/architecting-data-lakes.csp

Como construir um Data Lake bem sucedido

https://mapr.com/resources/videos/how-build-successful-datalake/assets/how_to_build_a_successful_data_lake_webinar_-_160517.pdf

Aqui estão informações do Cluster/Mestre e dos escravos.

![14](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/14.png)


ver que o arquivo já está em nosso Data Lake!!! Nós já temos um arquivo armazenado! Você acabou de construir seu Data Lake.

![16](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/16.png)

Executando o trabalho e verificando a execução

![17](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/17.png)

![18](https://github.com/pand-eX/DataLake-On-Premises/blob/main/assets/18.png)

fim.
