##📋 Descrição do Projeto
Este projeto consiste no **desenvolvimento de um modelo conceitual de banco de dados para um sistema de controle e gestão de execução de ordens de serviço em uma oficina mecânica**. O sistema foi projetado para atender às necessidades operacionais de uma oficina, desde o cadastro de clientes e veículos até o gerenciamento completo das ordens de serviço, incluindo autorizações, equipes de mecânicos, serviços executados e peças utilizadas.

##🎯 Objetivo
Fornecer uma base sólida de dados que permita:

Controlar o fluxo completo de ordens de serviço

Gerenciar o histórico de veículos e clientes

Controlar autorizações de serviços com compliance legal

Administrar equipes de mecânicos e suas especialidades

Gerar relatórios e análises de negócio

##🔧 Funcionalidades Principais
Cadastro de clientes e veículos

Controle de ordens de serviço com múltiplos status

Gestão de equipes de mecânicos por especialidade

Registro de autorizações clientes com validade jurídica

Controle de serviços realizados e peças utilizadas

Gestão de estoque de peças

Histórico completo de manutenções por veículo

##🗃️ Esquema do Banco de Dados
**Entidades Principais**
Cliente - Dados dos clientes da oficina

Veículo - Veículos pertencentes aos clientes

OrdemServico - Ordens de serviço com status e valores

Autorizacao - Autorizações formais dos clientes

Equipe - Equipes de mecânicos

Mecanico - Mecânicos e suas especialidades

Servico - Catálogo de serviços disponíveis

Peca - Peças em estoque e seus valores

**Relacionamentos Chave**
Um Cliente possui vários Veículos

Um Veículo tem várias Ordens de Serviço

Cada OS requer uma Autorização específica

Equipes executam várias OSs

Mecânicos pertencem a Equipes

OSs utilizam Serviços e Peças

## 📐 Diagrama (Visão Geral)

<img width="903" height="1102" alt="oficina" src="https://github.com/user-attachments/assets/db78ab84-1ee4-4ecb-bf28-dcf457248a5f" />

