# Implementando sua Primeira Stack com AWS CloudFormation

## Descrição do Projeto  
Este projeto foi desenvolvido como parte do desafio proposto pela **DIO**, com o objetivo de aplicar na prática os conceitos aprendidos sobre **AWS CloudFormation**.  
A proposta consistiu em criar e gerenciar uma Stack na AWS a partir de um modelo de template, explorando o conceito de **infraestrutura como código (IaC)** e a automação de recursos em nuvem.  

---

## Objetivo  
Demonstrar a aplicação prática do AWS CloudFormation na criação de uma Stack e documentar o processo de aprendizado de forma organizada e estruturada, utilizando o **GitHub** como ferramenta de versionamento e compartilhamento técnico.  

---

## Principais Aprendizados  

Durante o desenvolvimento deste projeto, foi possível consolidar uma série de aprendizados importantes relacionados à infraestrutura em nuvem e boas práticas de automação. Entre os principais pontos, destacam-se:

### **1. Compreensão da Infraestrutura como Código (IaC)**  
Foi possível entender de forma prática como o **CloudFormation** permite definir toda a infraestrutura de forma declarativa, por meio de arquivos de configuração em **YAML** ou **JSON**.  
Essa abordagem garante **reprodutibilidade**, **padronização** e **controle de versão** dos recursos criados na AWS, evitando a configuração manual e reduzindo falhas humanas.

### **2. Estrutura de um Template CloudFormation**  
O estudo do modelo de template possibilitou compreender melhor suas principais seções:  
- **Parameters:** permitem personalizar variáveis na criação da stack;  
- **Resources:** definem os recursos a serem criados (como buckets S3, instâncias EC2, etc.);  
- **Outputs:** exibem informações úteis sobre os recursos provisionados;  
- **Mappings e Conditions:** controlam variações de configuração e comportamentos condicionais.  

Essa estrutura mostrou a flexibilidade e a capacidade de escalabilidade da ferramenta.

### **3. Automação e Gerenciamento de Recursos**  
Foi possível perceber como o CloudFormation simplifica o ciclo de vida da infraestrutura, permitindo **criar, atualizar e excluir** recursos de maneira automatizada.  
Além disso, a ferramenta facilita a **orquestração de dependências**, garantindo que os recursos sejam criados na ordem correta e com as permissões adequadas.  

### **4. Benefícios da Documentação Técnica**  
Durante o processo, foi reforçada a importância de registrar o aprendizado e documentar cada etapa técnica.  
A utilização do **GitHub** como repositório público permitiu manter um histórico do projeto, além de servir como material de estudo e portfólio profissional.  

### **5. Ampliação da Visão sobre Cloud Computing**  
A prática com CloudFormation proporcionou uma melhor compreensão sobre como os serviços da AWS se integram e como a infraestrutura em nuvem pode ser tratada como software, reforçando a importância de automação e escalabilidade no ambiente corporativo.

---

## Dificuldades e Soluções  
A principal dificuldade enfrentada foi compreender a estrutura e a sintaxe do arquivo **YAML**, especialmente no momento de definir os recursos e parâmetros de forma correta.  
Essa dificuldade foi superada por meio da análise da **documentação oficial da AWS**, estudo de exemplos práticos e testes no próprio console da AWS para validar o comportamento do template.  

---

## Referências  
- [Documentação Oficial – AWS CloudFormation](https://docs.aws.amazon.com/cloudformation/index.html)  
- [Guia de Markdown no GitHub](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
  
---
