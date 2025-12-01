# 🗄️ Amazon RDS – Construção de Servidor de Banco de Dados e Integração com Aplicação Web  

---

## 🔎 Resumo
Executei um laboratório prático onde provisionei uma instância **Amazon RDS for MySQL (Multi-AZ)**, configurei a rede e os *security groups*, e integrei o banco com uma aplicação web hospedada em uma instância **EC2**. O objetivo foi validar conectividade, persistência de dados e comportamento Multi-AZ em um ambiente controlado (sandbox).

---

## 🧰 Habilidades adquiridas
- Planejamento e implementação de camadas de rede para bancos de dados (VPC, Subnet Groups).  
- Configuração de **Security Groups** para isolamento e controle de acesso entre camadas.  
- Provisionamento de instâncias **Amazon RDS** com deploy Multi-AZ.  
- Integração de aplicação web (EC2) com RDS via endpoint e credenciais.  
- Testes práticos de persistência, leitura/escrita e validação de replicação Multi-AZ.  
- Boas práticas de governança básica: uso de subnets privadas e princípio do acesso restrito.

---

## 🛠️ Tecnologias utilizadas
- **AWS**: RDS (MySQL), EC2, VPC, Security Groups, DB Subnet Groups.  
- **Banco de Dados**: MySQL 8.0.x (instância RDS).  
- **Servidor de Aplicação**: Instância EC2 rodando o app de exemplo (Address Book Application).  
- **Ferramentas/recursos do laboratório**: console AWS (Management Console) em ambiente sandbox educacional.

---
## 📁 Estrutura do repositório

`conhecendo-RDS-AWS`
```
├── rds-imagem/
└── README.md
```
