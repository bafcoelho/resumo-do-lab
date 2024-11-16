# Computação em Nuvem
## _Introdução_

## Tipos de nuvem
- Privada (On premise)
- Publica
- Híbrida

## Capex - Despesa de Capital

- Gasto inicial de dinheiro em infraestrutura física
- Valor reduz com o tempo
    - Ex: custo para construir uma sala de servidores, compra de hack, ar condicionado etc.
    - após um tempo fica despesas de luz

## Opex - Despesa Operacional

- Gasto sob demanda
- Gasto com produtos e serviços conforme necessário, pagamento conforme o uso.
- Seja cobrado imediatamente.

## Modelo baseado em Consumo

- Melhor previsão de custos
- São fornecidos preços para recursos e serviços individuais
- A cobrança é feita com base no seu consumo real (use a [calculadora](https://azure.microsoft.com/pt-br/pricing/calculator/) de preços)

# _Portal Microsoft Azure_
Link para acesso: [https://portal.azure.com](https://portal.azure.com)

### Navegação:
- Todos os serviços
    - Categorias
        - Computação:
            - Área de trabalho Virtual do Azure
            - Chaves SSH
            - Conjuntos de disponibilidade
            - Contas de laboratório
            - Imagens
            - Máquinas Virtuais, Discos, PaaS
            - etc
        - Rede:
            - Bastions: Rede segura para fazer acesso às nossas máquinas (Jump Server: Servidor ponte para conectar com outras máquinas).
            - Endereços IPs
            - DNS
            - Firewall
            - etc
        - Armazenamento:
            - Discos

## _Benefícios da Computação em Nuvem_
- Alta Disponibilidade, Escalabilidade, Elasticidade, Previsibilidade, Confiabilidade, Governança, Gerenciamento e etc.

##### Alta Disponibilidade
Existe um acordo (SLA) de indisponibilidade esperado do contrato. Ex: 99% de disponibilidade.

##### Escalabilidade
Capacidade de ajustar recursos para atender à demanda.
Significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
Não estar pagando além do necessário pelos serviços.

##### Elasticidade
Analogia com Black Friday
Se a aplicação experimentar um salto repentino acentuado de demanda, seus receursos implantados poderiam ser expandidos (automaticamente ou manualmente).
Da mesma forma se houver queda significativa de demanda, os recursos poderão ser reduzidos horizontalmente (automaticamente ou manual)

##### Confiabilidade (Resiliência)
Um sistema que se recupera de falhas e continua funcionando.
Com o design descentralizado, a nuvem:
- Dá suporte a uma infraestrutura confiável e resiliente
- Permite que você tenha recursos implantados em diversas regiões do mundo
- Em situação de catástrofe, outras regiões ainda estarão funcionando (Disaster and Recovery)

##### Previsibilidade (Microsoft Azure Well-Architected Framework)
Permite avançar com confiança, seja no desempenho ou no custo.
Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework

##### Segurança
A nuvem oferece ferramentas, mas a implementação de muitas delas deverá ser realizada pelo cliente (dev/arq cloud team)
A IaaS fornece recursos físicos, e permite que você gerencie remotamente

##### Governança
Como os recursos serão geridos, os padrões que deverão ser seguidos (seguir regulamentações, auditorias)
Recursos que ajudam a sinalizar qualquer recurso que esteja fora de conformidade automaticamente.

##### Gerenciabilidade
Como os recursos serão geridos, os padrões que deverão ser seguidos (seguir regulamentações, auditorias)
Recursos que ajudam a sinalizar qualquer recurso que esteja fora de conformidade automaticamente.
É possivel configurar manualmente ou via programação (APIs, Powershell, JSON etc)
