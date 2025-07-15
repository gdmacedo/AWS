# Proposta Técnica
## Plataforma B2B em AWS Cloud

## Relatório de Implementação de Serviços AWS - AWS - Amazon Web Services

---

Prezado Gestor Financeiro, Sr. José João Antônio Maria. conforme solicitação, segue a proposta.

---

Proposta Técnica – Plataforma B2B em AWS Cloud

#### 1. Amazon S3 Intelligent-Tiering  
Descrição: Classe de armazenamento que reduz custos automaticamente ao mover dados entre camadas de acesso conforme o uso. Ideal para arquivos grandes e com padrão de acesso imprevisível.  
Benefícios:
- Economia de até 68% em dados raramente acessados
- Alta durabilidade (99.999999999%) e disponibilidade
- Sem necessidade de gerenciamento manual de ciclo de vida  
Custo estimado: R$ 0,10–0,15 por GB/mês + R$ 0,01 por 1.000 objetos monitorados


#### 2. Amazon Aurora (MySQL/PostgreSQL)  
Descrição: Banco de dados relacional gerenciado, compatível com MySQL e PostgreSQL, com alta performance e disponibilidade.  
Benefícios:
- Até 5x mais rápido que MySQL e 3x mais rápido que PostgreSQL
- Failover automático, backups contínuos e escalabilidade sob demanda
- Ideal para integração entre parceiros e gestão de dados transacionais  
Custo estimado: R$ 0,40/hora por instância + R$ 0,10/GB de armazenamento



#### 3. Amazon VPC + Security Groups  
Descrição: Rede privada virtual com grupos de segurança que atuam como firewalls para controlar o tráfego de entrada e saída.  
Benefícios:
- Segmentação segura entre distribuidores, farmácias e clientes
- Regras configuráveis por IP, porta e protocolo
- Sem custo adicional para uso de Security Groups  
Custo estimado: R$ 0 (incluso na configuração da VPC)

---

Resumo Financeiro Estimado

| Item                          | Infraestrutura Tradicional | AWS Cloud (estimado) |
|------------------------------|-----------------------------|-----------------------|
| Armazenamento de arquivos    | R$ 5.000/mês                | R$ 1.200/mês          |
| Banco de dados gerenciado    | R$ 4.000/mês                | R$ 1.800/mês          |
| Segurança e rede privada     | R$ 3.000/mês                | R$ 0 (Security Groups)|
| **Total Mensal**             | **R$ 12.000**               | **R$ 3.000–4.000**    |
| **Economia Potencial (%)**   | —                           | **-70% aproximadamente** |

---


Atenciosamente, fico a disposição para esclarecer qualquer duvida.


Glener Diniz Macedo - Gerente do Departamento de Engenharia de Software. 

**Empresa:**  
Foot on the Keyboard Software Engineering.