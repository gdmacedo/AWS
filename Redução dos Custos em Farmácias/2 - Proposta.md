# Proposta Técnica
## Plataforma B2B em AWS Cloud

## Relatório de Implementação de Serviços AWS - AWS - Amazon Web Services

---

Prezado Gestor Financeiro, Sr. José João Antônio Maria. conforme solicitação, segue a proposta.

---

Carta de Solicitação – Projeto de Plataforma Virtual em AWS Cloud

De: José João Antônio Maria – Gestor Financeiro  
Para: Glener Diniz Macedo – Gerente de Engenharia de Software  
Empresa: Foot on the Keyboard Software Engineering  
Assunto: Solicitação de desenvolvimento de plataforma virtual em nuvem com análise de viabilidade técnica e econômica

Prezado Sr. Glener,

Como gestor financeiro da [Distribuidora Farmacêutica – Nome da empresa], que atua como hub de distribuição conectado a diversas empresas do setor, venho por meio desta solicitar a análise técnica e o desenvolvimento de uma plataforma virtual baseada na infraestrutura da AWS.

Reconheço que não possuo conhecimento técnico sobre computação em nuvem, mas compreendo que essa transformação representa uma oportunidade estratégica para modernizar nossa operação, reduzir custos e ampliar nossa capacidade de integração com drogarias e farmácias de varejo que atendem diretamente o consumidor final.

Solicito que esta proposta contemple:

- A concepção de uma plataforma escalável e segura em AWS
- A descrição de tecnologias recomendadas para o projeto
- Um demonstrativo de redução de custos comparado à infraestrutura tradicional

Acreditamos que essa iniciativa poderá posicionar nossas empresas como líderes em inovação no setor farmacêutico.

Atenciosamente,  
José João Antônio Maria  
Gestor Financeiro – [Distribuidora Farmacêutica]  
📞 [Telefone] | 📧 [Email]

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