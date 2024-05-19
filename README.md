# Sistemas-Distribuidos
Resumo Sistemas Distribuidos
# Arquitetura Cliente-Servidor

## Clientes
- Iniciam solicitações de serviços ou recursos a servidores.
- Consistem em interfaces de usuário ou aplicativos que interagem com usuários finais.
- Enviam solicitações e recebem respostas dos servidores.

## Servidores
- Recebem solicitações dos clientes e fornecem serviços ou recursos.
- Máquinas de alta capacidade projetadas para lidar com múltiplas solicitações eficientemente.
- Fornecem serviços como armazenamento, processamento de dados, hospedagem de sites e conteúdo multimídia.

## Comunicação Cliente-Servidor
- Ocorre via protocolos de rede como HTTP, TCP/IP, UDP.
- Pode ser síncrona ou assíncrona.
- Clientes estabelecem uma conexão, enviam solicitações e aguardam respostas.

## Vantagens
- Escalabilidade
- Desempenho
- Flexibilidade
- Facilidade de manutenção

## Limitações
- Dependência de rede
- Custo de infraestrutura
- Ponto único de falha
- Latência de rede

# Sistemas Peer-to-Peer (P2P)

## Conceito
- Todos os nós têm capacidades e responsabilidades equivalentes.
- Descentralizado, sem servidor central; cada nó pode ser cliente e servidor.

## Autonomia e Descentralização
- Cada nó é independente e pode comunicar-se diretamente com outros.
- Aumenta a robustez e resiliência do sistema.

## Arquitetura P2P
- Pode variar de totalmente descentralizada a híbrida.
- Em redes P2P puras, todos os nós têm a mesma função.

## Distribuição e Compartilhamento de Recursos
- Recursos distribuídos entre os nós.
- Cada nó pode compartilhar e acessar recursos de outros.

## Protocolos de Comunicação
- Protocolos específicos como BitTorrent, Gnutella, Kademlia.

## Aplicações
- Compartilhamento de arquivos
- Comunicação e mensagens
- Redes sociais descentralizadas
- Sistemas de armazenamento e computação distribuída

## Vantagens
- Escalabilidade
- Robustez
- Distribuição de carga

## Limitações
- Gerenciamento de recursos
- Segurança e confiabilidade
- Descoberta de peers

# Sistemas Baseados em Agentes

## Conceito de Agentes
- Entidades computacionais autônomas que percebem o ambiente, tomam decisões e agem para alcançar objetivos.
- Autonomia, reatividade, proatividade e habilidade de aprendizado.

## Autonomia dos Agentes
- Agem independentemente sem intervenção direta.
- Percebem o ambiente, analisam informações e executam ações baseadas em objetivos.

## Comunicação entre Agentes
- Podem comunicar-se via mensagens ou protocolos específicos.
- Comunicação pode ser síncrona ou assíncrona.

## Tipos de Agentes
- Reativos
- Cognitivos
- Sociais

## Aplicações
- Inteligência artificial
- Robótica
- Sistemas de informação
- Automação industrial
- Jogos
- Simulação

# Definição e Importância dos Sistemas Distribuídos

## Definição
- Conjunto de computadores independentes que se comunicam para atingir um objetivo comum, compartilhando recursos e operando como uma única entidade.

## Importância
- Utilizados em computação em nuvem, redes sociais, sistemas de telecomunicações e financeiros.

## Desafios
- Comunicação confiável
- Sincronização de processos
- Consistência de dados
- Tolerância a falhas

# Principais Conceitos e Terminologia

## Processos
- Unidades de execução independentes que interagem por meio de comunicação.

## Recursos Compartilhados
- Recursos acessados e utilizados por múltiplos processos simultaneamente.

## Comunicação Interprocesso
- Troca de mensagens e dados entre processos em diferentes máquinas.

## Coordenação
- Sincronização e cooperação entre processos para realizar tarefas conjuntas.

## Consistência de Dados
- Garantir que todos os nós tenham uma visão consistente dos dados.

## Tolerância a Falhas
- Capacidade de continuar operando de maneira confiável mesmo quando componentes falham.

# Metas e Desafios dos Sistemas Distribuídos

## Metas
- Acesso a recursos
- Transparência de distribuição
- Abertura
- Escalabilidade

## Desafios
- Serviços, dados e algoritmos centralizados enfrentam problemas de escalabilidade com o aumento de usuários e recursos.

# Protocolos

## Definição
- Regras de comunicação que definem como mensagens são construídas, empacotadas, enviadas e recebidas.

## Exemplos
- HTTP, que define estrutura de mensagens com header e body.

# Solução Cliente-Servidor

## Comunicação
- Clientes e servidores se comunicam via HTTP, com requisições e respostas definidas por protocolos.

## Middleware
- Intermediário que facilita a comunicação e conversão de dados entre cliente e servidor.
