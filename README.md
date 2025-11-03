## Infraestrutura Automatizada com AWS CloudFormation

# 1. Conceitos Fundamentais

# 1.1 Infraestrutura como Código (IaC)

É a prática de gerenciar e provisionar infraestrutura por meio de código, em vez de processos manuais.
Permite versionamento, automação e repetibilidade do ambiente.

# 1.2 AWS CloudFormation

Serviço da AWS que cria e gerencia recursos automaticamente com base em arquivos de template escritos em YAML ou JSON.
Esses templates descrevem recursos como EC2, VPCs, S3, RDS, entre outros.

Principais benefícios:

Automação de deploys de infraestrutura.

Redução de erros humanos.

Reprodutibilidade de ambientes.

Integração com CI/CD.

# 1.3 Templates CloudFormation

Um template é um arquivo de configuração declarativo que define os recursos a serem criados.
Estrutura básica:

Parameters: Entradas configuráveis.

Resources: Componentes da AWS a serem criados.

Outputs: Informações exibidas após a execução do stack.

Mappings e Conditions: Permitem lógica condicional e parametrização.

# 1.4 Stacks

Um stack é o conjunto de recursos criados a partir de um template CloudFormation.
Pode ser atualizado, deletado ou replicado conforme necessário.

# AWS CloudFormation Lab

## Descrição
Este projeto demonstra a criação de uma infraestrutura automatizada utilizando **AWS CloudFormation**, aplicando o conceito de **Infraestrutura como Código (IaC)**.

## Objetivos
- Implementar recursos AWS de forma automatizada.
- Documentar o processo técnico.
- Compartilhar aprendizados e resultados.

## Arquitetura Implementada
Descreva brevemente quais recursos foram criados (por exemplo: EC2, S3, VPC).

## Como Executar
1. Faça login no Console AWS.  
2. Acesse **CloudFormation > Create Stack**.  
3. Faça upload do arquivo `template.yaml`.  
4. Clique em **Next** e siga os passos para criar o stack.

## Resultados
- Capturas de tela do stack criado.  
- Outputs e validações do ambiente.

## Aprendizados
- Benefícios da automação com CloudFormation.  
- Estrutura de templates YAML.  
- Boas práticas de versionamento com GitHub.

## Recursos
- [Documentação AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)

