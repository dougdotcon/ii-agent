# IntelligentAgentFramework

[![GitHub stars](https://img.shields.io/github/stars/Intelligent-Internet/ii-agent?style=social)](https://github.com/Intelligent-Internet/ii-agent/stargazers)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Blog](https://img.shields.io/badge/Blog-II--Agent-blue)](https://ii.inc/web/blog/post/ii-agent)
[![GAIA Benchmark](https://img.shields.io/badge/GAIA-Benchmark-green)](https://ii-agent-gaia.ii.inc/)

O **IntelligentAgentFramework** é uma plataforma de código aberto projetada para agilizar e aprimorar o desenvolvimento de agentes de IA inteligentes. Ele representa um avanço significativo na forma como interagimos com a tecnologia—mudando de ferramentas passivas para sistemas inteligentes capazes de executar tarefas complexas e multi-etapas de forma independente.

## Visão Geral

O IntelligentAgentFramework é arquitetado para fornecer uma interface de agente robusta para Modelos de Linguagem (LLMs) de ponta, aproveitando especificamente os modelos Claude da Anthropic. Ele foi construído para oferecer alta flexibilidade e poder através de múltiplas opções de interface:

*   **Interface de CLI**: Uma ferramenta de linha de comando poderosa para interação direta, criação de scripts e automação.
*   **Servidor WebSocket**: Um backend em tempo real que impulsiona aplicações frontend modernas (baseadas em React).
*   **Integração com Nuvem**: Integração perfeita com o Vertex AI do Google Cloud para acesso escalável e confiável às APIs de LLMs.

## Capacidades Principais

O IntelligentAgentFramework é um assistente versátil construído para elevar a produtividade em diversos domínios:

| Domínio | Capacidades |
|--------|----------------------|
| **Pesquisa & Verificação de Fatos** | Busca web multi-etapas, triangulação de fontes, anotações estruturadas, resumo rápido. |
| **Geração de Conteúdo** | Rascunhos de blogs e artigos, planos de aula, escrita criativa, documentação técnica e criação automatizada de websites. |
| **Análise & Visualização de Dados** | Limpeza de dados, análise estatística, detecção de tendências, criação de gráficos e geração automatizada de relatórios. |
| **Desenvolvimento de Software** | Síntese de código, refatoração, depuração, geração de testes e tutoriais passo a passo em múltiplas linguagens. |
| **Automação de Fluxos de Trabalho** | Geração de scripts, automação de navegador, gerenciamento de arquivos e otimização de processos. |
| **Resolução de Problemas** | Decomposição de problemas complexos, exploração de caminhos alternativos, orientação passo a passo e solução de problemas. |

## Arquitetura & Métodos

O framework é construído sobre uma metodologia sofisticada que garante confiabilidade e adaptabilidade:

### 1. Arquitetura do Agente Principal & Interação com LLM
*   **Gerenciamento de Contexto Dinâmico**: Prompting de sistema com contexto adaptado e gerenciamento completo de histórico para lidar efetivamente com as limitações de tokens.
*   **Invocação Inteligente**: Chamadas sistemáticas à API do LLM e seleção de capacidades baseada na tarefa.
*   **Refinamento Iterativo**: Melhoria contínua através de ciclos de execução e loops de feedback.

### 2. Planejamento & Reflexão
*   **Raciocínio Estruturado**: Uma estrutura robusta para resolução de problemas complexos.
*   **Decomposição**: Quebra grandes problemas em etapas gerenciáveis e sequenciais.
*   **Tomada de Decisão Transparente**: Registra e explica o processo de raciocínio do agente.

### 3. Capacidades de Execução
*   **Operações de Sistema de Arquivos**: Edição inteligente de código e manipulação de arquivos.
*   **Execução Segura de Comandos**: Executa código e comandos em um ambiente sandboxed.
*   **Interação Web Avançada**: Uma suíte poderosa de automação de navegador para navegação, extração de dados e interação.

## Começando

Para configurar o projeto localmente para desenvolvimento ou testes:

1.  **Clone o repositório:**
    bash
    git clone https://github.com/Intelligent-Internet/ii-agent.git
    cd ii-agent
    

2.  **Instale as dependências:**
    É recomendado usar um ambiente virtual.
    bash
    pip install -r requirements.txt
    

3.  **Configure as Chaves de API:**
    Defina as variáveis de ambiente necessárias para o Google Cloud e a Anthropic.
    bash
    export GOOGLE_APPLICATION_CREDENTIALS="/caminho/para/suas/credenciais.json"
    export ANTHROPIC_API_KEY="sua_chave_anthropic"
    

4.  **Execute a CLI:**
    bash
    python main.py
    

## Documentação

Para uso detalhado, referência da API e exemplos, consulte nosso [blog oficial e documentação](https://ii.inc/web/blog/post/ii-agent).

## Licença

Este projeto está licenciado sob a Licença Apache 2.0. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
