# new_project_laravel

**1. Introdução:**

O objetivo principal deste projeto é estabelecer uma estrutura fundamental que permita o desenvolvimento de novos sistemas. Esses sistemas serão construídos com base na estrutura do Laravel. A escolha do Laravel como base para o desenvolvimento dos novos sistemas devido ser um framework bem estabelecido e amplamente utilizado que oferece uma ampla gama de ferramentas e recursos para agilizar o desenvolvimento de aplicativos web. Com isso, a equipe de desenvolvimento terá a vantagem de uma experiência de desenvolvimento mais fácil, otimizada e moderna. Isso é possível devido às características robustas e amigáveis do Laravel, que permitem que os desenvolvedores foquem mais na lógica de negócios do que em questões técnicas complexas.
Uma das principais vantagens dessa estrutura é a configuração de um ambiente de desenvolvimento apropriado. Esse ambiente é pré-configurado para ser utilizado com Docker, uma tecnologia que permite a criação e gerenciamento de ambientes isolados (contêineres) para aplicativos. Isso garante que todos os membros da equipe tenham um ambiente consistente e idêntico para desenvolvimento, evitando problemas de compatibilidade e facilitando a colaboração.
O uso do Docker como parte integrante do ambiente de desenvolvimento traz benefícios significativos. Isolar o ambiente de desenvolvimento em contêineres Docker oferece portabilidade, escalabilidade e consistência. Isso significa que a configuração do ambiente não é dependente da máquina local de cada desenvolvedor, tornando o processo de desenvolvimento mais ágil e uniforme.

**2. Como Utilizar:**

Para começar a utilizar este projeto, siga os passos abaixo:

**Passo 1: Clonando o Repositório**
Inicie clonando este repositório para a sua máquina de trabalho usando o seguinte comando:

```bash
git clone <URL_do_repositório>
```

**Passo 2: Configuração Inicial**
Após clonar o repositório, você precisará configurar algumas variáveis essenciais. Comece configurando o nome da aplicação no arquivo `.env` localizado no diretório raiz do projeto. 

![Alt text](image.png)

**Passo 3: Configuração de Ambientes**
Acesse a pasta `.src/`, onde você encontrará três arquivos `.env`:

- `.env.dev`
- `.env.homolog`
- `.env.prod`

Esses arquivos já estão pré-configurados para os modos de desenvolvimento. Se o desenvolvimento estiver ocorrendo no ambiente de desenvolvimento, crie uma cópia do arquivo `.env.dev` e renomeie-o para `.env`. É importante nunca sobrescrever os arquivos `.env`, garantindo que todas as novas instâncias sigam o mesmo padrão.

**Passo 4: Personalização do Arquivo .env**
A cópia do arquivo `.env` que você criou pode ser personalizada conforme suas necessidades específicas. No entanto, sempre que realizar alterações, lembre-se de documentá-las adequadamente. Este arquivo deve conter todas as variáveis globais, conexões com bancos de dados externos e chaves de acesso para APIs externas que serão usadas no desenvolvimento geral do projeto.

Seguindo esses passos, você estará pronto para começar a desenvolver no ambiente configurado. Lembre-se de sempre manter a consistência nas configurações e de documentar todas as alterações realizadas para garantir um desenvolvimento fluido e colaborativo.

Em caso de dúvidas ou necessidade de atualizações nas configurações, consulte a documentação para garantir que todos os membros da equipe estejam alinhados e atualizados sobre as mudanças feitas. Isso garantirá um fluxo de trabalho eficiente e coeso ao longo do projeto.