# Fundamentos basicos Azure

## O que é Cloud?

É um modelo *as a service* (Paga pelo o que usou)

> A pergunta pode ser respondida como uma referência ao uso das lavanderias, mais comum em países como os EUA, onde as pessoas não possuem máquina de lavar em casa e em vez de comprar uma e manter seus custos, apenas pagam pelo o que utilizam em uma lavanderia.

### On-premise:

No mundo da tecnologia, as empresas podem ter um modelo on-premise, que é o modelo na qual a empresa vai arcar com todos os custos, incluindo data centers (locais onde se colocam os servidores), refrigeração, networking (cabeamento e internet), máquinas (aquisição e manutenção), atualizações e etc.  
A empresa tem um custo alto e um controle total sobre seus servidores.

### Ambiente Cloud:

Uma empresa com o modelo on-premise pode ter servidores que não utilizam, mas mesmo assim têm gastos para mantê-los. Com isso, uma forma boa encontrada foi de fornecer a sua utilização para outras empresas ou usuários que queiram utilizar, mas não querem gastar para manter toda a estrutura física, mas sim apenas pelo o que usam.  
Com essa situação, as empresas provedoras dos servidores cobram pelo o uso de terceiros e os terceiros acessam por meio da nuvem.  
Os servidores continuam no mesmo local, mas quem paga para usar, acessa pela nuvem por meio da internet.

### Modelo híbrido:

Existem empresas que possuem o modelo on-premise e o ambiente cloud juntos para suprir suas necessidades.

---

## Plataform:

Empresas que trabalham com foco de ter ambientes com infraestrutura completa e vender para outras empresas.  
**Exemplos:** AWS (da Amazon), Azure (da Microsoft), Oracle, GCP (do Google).

---

## Regions e Zones:

Para diminuir a latência das empresas que alugam as máquinas, as empresas provedoras de serviços colocam seus data centers em locais estratégicos, espalhados em diferentes locais do mundo, para atender melhor quem vai alugar.

---

## Tipos de Nuvem:

### Nuvem Privada:
Ambiente 100% on-premise. Criam ambiente em nuvem em seu datacenter mas não fornecem acesso para alguém fora da organização.

### Nuvem Pública:
Provedor de hosting. Acessada via conexão de rede segura (geralmente é a internet).

### Nuvem Híbrida:
A mistura entre nuvem privada e pública.

---

## CapEx - Despesas de capital:

O gasto inicial com a infraestrutura física. O valor se reduz com o tempo.

## OpEx - Despesas operacionais:

Pagar pelo que usa, gastar com produtos e serviços conforme o necessário, você é cobrado imediatamente.

---

## Benefícios Da Nuvem:

- **Alta Disponibilidade**  
  Empresa entrega no contrato SLA a porcentagem de disponibilidade e seus respectivos custos, acima de 99%. Variando entre 99%; 99,9%; 99,999%.

- **Escalabilidade**  
  Capacidade de ajustar recursos para atender à demanda, seja pra cima ou pra baixo.

- **Elasticidade**  
  Se ocorrer um salto repentino (para cima ou para baixo) na demanda, seus recursos podem ser expandidos ou diminuídos automaticamente ou manualmente.

- **Confiabilidade**  
  Devido ao design descentralizado (datacenters em várias regiões), a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. Podendo ter recursos implantados em todo o mundo.

- **Previsibilidade**  
  Permite você avançar com confiança no desempenho e no custo.

- **Segurança**  
  Oferece ferramentas de segurança, mas é importante lembrar que muitas delas devem ser implementadas pelo cliente.

- **Governança**  
  Auditoria, para verificar se está tudo em ordem.

- **Gerenciabilidade**  
  Escala automaticamente a implantação de recursos com base na necessidade.  
  **Exemplos:** Pelo portal Web; Usando interface de linha de comando; Usando APIs; Usando PowerShell.
