# aws-abstergo-cloud-implementation
Proposta de arquitetura cloud utilizando Amazon S3, EC2 e RDS para modernização, escalabilidade e redução de custos imediatos na Abstergo Industries.

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 12 de Junho de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Luciano  

## Introdução
Este relatório apresenta o processo de implementação de ferramentas de computação em nuvem na empresa Abstergo Industries, realizado por Luciano Silva de Arruda. O objetivo do projeto foi elencar 3 serviços AWS estratégicos, com a finalidade de realizar a diminuição de custos imediatos relacionados à infraestrutura física de TI, visando a aprovação da diretoria financeira.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos focados nas necessidades de um hub de distribuição farmacêutica. A seguir, serão descritas as etapas do projeto:

### Etapa 1: 
- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)
- **Foco da ferramenta:** Poder de computação escalável e sob demanda.
- **Descrição de caso de uso:** Migração do sistema legado de roteirização e logística para instâncias virtuais na nuvem. Em vez de manter servidores físicos caros rodando 24/7, a Abstergo utilizará o EC2 para escalar a capacidade de processamento apenas durante os horários comerciais de pico de faturamento. A empresa pagará apenas pelo tempo de computação efetivamente utilizado, eliminando custos de manutenção e ociosidade de hardware.

### Etapa 2: 
- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de dados altamente durável, seguro e de baixo custo.
- **Descrição de caso de uso:** Criação de um repositório centralizado para o arquivamento de notas fiscais, bulas, manuais de produtos farmacêuticos e registros de conformidade sanitária da Anvisa. O S3 permite armazenar um volume massivo de dados sem a necessidade de comprar novos discos físicos (storage) localmente, garantindo alta disponibilidade e proteção contra perda de dados.

### Etapa 3: 
- **Nome da ferramenta:** Amazon RDS (Relational Database Service)
- **Foco da ferramenta:** Banco de dados relacional gerenciado.
- **Descrição de caso de uso:** Hospedagem do banco de dados principal de clientes (farmácias parceiras) e transações financeiras. O RDS automatiza tarefas administrativas demoradas, como backups diários, atualizações de software e monitoramento, permitindo que a equipe reduza os gastos operacionais (OpEx) e foque no desenvolvimento de melhorias para o negócio, em vez de gerenciar infraestrutura de banco de dados.

## Conclusão
A implementação dessas ferramentas na empresa **Abstergo Industries** tem como esperado a redução drástica nos custos com compra e manutenção de servidores físicos, energia elétrica e refrigeração, o que aumentará a eficiência, a segurança de dados e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias nativas da nuvem que possam melhorar ainda mais os processos da empresa.

## Anexos

* [Documentação Oficial - Amazon EC2](https://aws.amazon.com/pt/ec2/)
* [Documentação Oficial - Amazon S3](https://aws.amazon.com/pt/s3/)
* [Documentação Oficial - Amazon RDS](https://aws.amazon.com/pt/rds/)

---

**Assinatura do Responsável pelo Projeto:**

*Luciano*
