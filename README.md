# Simulador de Memória Virtual

Este repositório possui fins **exclusivamente acadêmicos**, sendo utilizado como material de apoio e práticas para a disciplina **Elementos de Sistemas Computacionais**.

## 📌 Sobre o Projeto

Este projeto consiste em um simulador de memória virtual que modela a gestão de memória e o funcionamento de diversos algoritmos de substituição de páginas utilizados por sistemas operacionais. 

### Recursos e Funcionalidades:
- **Algoritmos de Substituição de Páginas:**
  - FIFO (*First-In-First-Out*)
  - Random (Aleatório)
  - Clock
  - ESC (*Enhanced Second Chance*)
  - Aging (Envelhecimento)
  - Working Set
- Suporte a múltiplos processos com tabelas de páginas individuais.
- Simulação de operações de acesso à memória (leitura e escrita).
- Simulação de *context switch* (troca de contexto) entre processos.
- Exibição de estatísticas detalhadas das operações de memória e *page faults*.



## 🚀 Execução do Simulador

- No terminal, navegue até um diretório de sua preferência e clone o repositório:
  ```bash
  git clone https://github.com/mmaria-alves/simulador-memoria-virtual.git
  ```

- Acesse a pasta do simulador:
  ```bash
  cd simulador-memoria-virtual/simulador
  ```

- Pelo terminal, execute o arquivo:
  ```bash
  start vm_visual.html
  ```
  *Obs.: O arquivo também pode ser executado dando dois cliques nele no Explorador de Arquivos.*


## 💳 Créditos

Este repositório é uma adaptação baseada no projeto original desenvolvido por **Fatih Özyurt**.

- **Repositório Original:** [ozyurtf/virtual-memory](https://github.com/ozyurtf/virtual-memory/tree/main)
- **Demonstração em Vídeo Original:** [Virtual Memory Simulator Demo (YouTube)](https://www.youtube.com/watch?v=NNNUpGNWaA8)