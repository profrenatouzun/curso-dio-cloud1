# Computação em Nuvem

## O que é Computação em Nuvem?

### Introdução
A computação em nuvem é um modelo de entrega de serviços de computação através da camada de rede (como recursos de processamento, armazenamento, redes e outros). Esses serviços são fornecidos e gerenciados por provedores de nuvem.

### O que são nuvens?
São grandes repositórios de recursos (normalmente virtualizados), tais como hardware, plataformas e software, que são facilmente acessíveis através da rede. Estes recursos podem ser configurados dinamicamente de modo a ajustar-se a diferentes cargas de trabalho.

### Modelos de Serviço
1. **IaaS (Infrastructure as a Service)**: Fornece infraestrutura virtualizada (servidores, armazenamento, redes).
   - Exemplos: AWS, Microsoft Azure, Google Cloud Platform.
2. **PaaS (Platform as a Service)**: Oferece uma plataforma para desenvolvimento e execução de aplicativos.
   - Exemplos: Google App Engine, Microsoft Azure App Service.
3. **SaaS (Software as a Service)**: Disponibiliza aplicativos prontos para uso via internet.
   - Exemplos: Microsoft Office 365, Salesforce, Google Workspace.

### Tipos de Nuvem
- **Pública**: Infraestrutura compartilhada por várias organizações (ex: AWS, Azure).
- **Privada**: Infraestrutura dedicada a uma única organização (on-premise ou terceirizada).
- **Híbrida**: Combinação de nuvem pública e privada.
- **Multicloud**: Uso de múltiplos provedores de nuvem para diferentes cargas de trabalho.

---

## Conceitos Fundamentais da Computação em Nuvem

### 1. Virtualização
Tecnologia que permite criar ambientes virtuais isolados em um único hardware físico. Inclui:
- **Máquinas Virtuais (VMs)**: Sistemas operacionais independentes em um mesmo hardware.
- **Contêineres**: Virtualização mais leve, compartilhando o kernel do sistema hospedeiro.

### 2. Elasticidade e Escalabilidade
- **Elasticidade**: Ajuste dinâmico de recursos conforme a demanda.
- **Escalabilidade**: Capacidade de expandir recursos sem comprometer o desempenho.

### 3. Pagamento por Uso
Modelo onde os usuários pagam apenas pelos recursos consumidos, ideal para demandas variáveis.

### 4. Acesso pela Internet
Serviços acessíveis remotamente via internet, permitindo gerenciamento de qualquer dispositivo conectado.

### 5. Serviços Sob Demanda
Provisionamento e gerenciamento de recursos sem intervenção direta da equipe de TI.

### 6. Repositório de Recursos
Consolidação de recursos (armazenamento, rede, processamento) em um ambiente compartilhado.

### SLA (Service Level Agreement)
Contrato que define os níveis de desempenho e disponibilidade garantidos pelo provedor.

---

## Vantagens e Desafios da Computação em Nuvem

### Vantagens
1. **Escalabilidade**:
   - Vertical (Scale-Up): Aumento de recursos em um servidor.
   - Horizontal (Scale-Out): Adição de mais servidores.
2. **Flexibilidade**: Adaptação rápida às necessidades do negócio (IaaS, PaaS, SaaS).
3. **Redução de Custos**:
   - Elimina investimentos iniciais em hardware.
   - Pagamento apenas pelo uso.
4. **Acesso Global**: Recursos acessíveis de qualquer lugar com internet.
5. **Manutenção Simplificada**: Provedores gerenciam atualizações e segurança.
6. **Alta Disponibilidade**: Redundância e recuperação de desastres.
7. **Inovação**: Facilita adoção de tecnologias como IA, IoT, etc.

### Desafios e Mitigação
1. **Segurança e Privacidade**:
   - Ameaças: Ataques cibernéticos, vulnerabilidades de rede.
   - Mitigação: Criptografia, autenticação multifatorial (MFA), monitoramento.
2. **Dependência do Provedor (Vendor Lock-In)**:
   - Mitigação: Arquiteturas multi-nuvem, padrões abertos.
3. **Conectividade e Latência**:
   - Mitigação: Uso de CDNs, data centers próximos aos usuários.
4. **Gerenciamento e Controle**:
   - Mitigação: Plataformas de gerenciamento centralizado, automação.

---

## Referências
- DIAS, Carlos Luís Soares. "COMPUTAÇÃO EM NUVEM", Brasília, 2013.
- RED HAT. "Cloud computing". Disponível em: [https://www.redhat.com/pt-br/topics/cloud](https://www.redhat.com/pt-br/topics/cloud).
- AWS. "O que é XML?". Disponível em: [https://aws.amazon.com/pt/what-is/xml/](https://aws.amazon.com/pt/what-is/xml/).
