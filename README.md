# Montagem e Configuração de Ambiente Virtual Educacional🧑‍💻

### Desenvolver um ambiente virtual educacional para a execução de softwares como MySQL, Node.js e Python, com foco em ensino e desenvolvimento.

 ### O projeto envolve a escolha e montagem de um computador físico com orçamento de até R$ 5.000,00, a criação de uma máquina virtual utilizando o VirtualBox e a instalação de um sistema operacional Linux. O objetivo é fornecer uma plataforma estável para testes e aprendizagem, além de produzir uma documentação detalhada com o processo de instalação e configuração do ambiente.

# Levantamento de Requisitos🧑‍💼

## Requisitos para o Computador Físico:
- **Processador (CPU):** 4 núcleos ou mais, com velocidade mínima de 3.0 GHz.
- **Memória RAM:** 16 GB para suportar múltiplos softwares simultaneamente.
- **Armazenamento:** SSD de 512 GB ou mais para maior velocidade e espaço.
- **Placa-mãe:** Compatível com o processador e com suporte para expansão.
- **Fonte de Alimentação:** 500W ou mais, adequada para os componentes.
- **Teclado e Mouse:** Equipamentos básicos e confortáveis.
- **Monitor:** 21 polegadas, resolução Full HD (1920x1080).



# Orçamento dos Componentes para o Computador Físico📈

| **Componente**        | **Produto**                                  | **Link**                                                      | **Justificativa**                                                                 |
|-----------------------|----------------------------------------------|--------------------------------------------------------------|----------------------------------------------------------------------------------|
| **Processador (CPU)**  | - Processador AMD Ryzen 5                                      | [Link](https://www.kabum.com.br/produto/320799/processador) | Boa performance para multitarefa, custo-benefício equilibrado.                    |
| **Memória RAM**       | - Memória RAM Kingston                                       | [Link](https://www.kabum.com.br/produto/172365/memoria-ram-kingston) | Alta velocidade e capacidade para suportar multitarefas e desenvolvimento.       |
| **Armazenamento (SSD)**| - SSD Kingston A400                                          | [Link](https://www.kabum.com.br/produto/85198/ssd-kingston-a400-480gb)  | SSD rápido com boa capacidade para armazenar sistema e projetos.                 |
| **Placa-mãe**         | - Placa-Mãe ASRock                                           | [Link](https://www.kabum.com.br/produto/111107/placa-mae-)  | Boa relação custo-benefício, com suporte para processadores Ryzen.              |
| **Fonte de Alimentação**| -  Fonte MSI MAG                                         | [Link](https://www.kabum.com.br/produto/369658/fonte-msi-mag-a650bn-650w-80-plus-bronze)  | Fonte de boa qualidade com potência suficiente para o setup.                     |
| **Teclado**           | - Teclado Gamer                                         | [Link](https://www.kabum.com.br/produto/416202/teclado-gamer)  | Teclado confortável e funcional, com bom custo para uso educacional.         
| **Mouse**             | -  Mouse sem fio                                         | [Link](https://www.amazon.com.br/dp/B01K92Z3OQ?) | Mouse básico e ergonômico, ideal para uso diário.                                |
| **Monitor**           | -  Monitor PCFort 21,5"                                         | [Link](https://www.kabum.com.br/produto/645007/monitor-pcfort)  | Monitor Full HD com boa qualidade e preço acessível para desenvolvimento.        |
### **Total Estimado:** R$ 2775,77

## Requisitos para a Máquina Virtual:
- **Memória:** 8 GB de RAM alocada para a VM.
- **CPU:** 2 núcleos dedicados para a máquina virtual.
- **Armazenamento:** 50 GB ou mais de disco rígido virtual.
- **Conectividade:** Rede configurada em modo NAT ou Bridge para acesso à internet.

# Escolha do Sistema Operacional: Justificativa e Comparação🤖

**Distribuições Pesquisadas:**

- **Ubuntu:** Facilidade de uso, grande comunidade, e fácil instalação. Suporte completo para MySQL, Node.js e Python. Ideal para iniciantes.
- **Debian:** Muito estável e seguro, mas menos amigável para iniciantes e configuração mais complexa.
- **Fedora:** Oferece pacotes mais recentes, mas consome mais recursos e pode ser menos estável.

**Justificativa da Escolha:**
O **Ubuntu** foi escolhido por sua facilidade de uso, compatibilidade com as ferramentas (MySQL, Node.js, Python), grande suporte da comunidade e ampla documentação, sendo a melhor opção para fins educacionais e iniciantes, porem as três citadas foram testadas
# Guia Rápido de Instalação do Ubuntu🌐

1. **Instale o VirtualBox** e baixe a ISO do Ubuntu.
2. **Crie uma Máquina Virtual** no VirtualBox com 4 GB de RAM e 40 GB de disco.
3. **Configure a Rede** para "NAT" para acesso à internet (escolha nossa).
4. **Inicie a Máquina Virtual**, selecione a ISO do Ubuntu e siga o assistente de instalação.
5. **Finalize a Instalação**, reinicie e remova a ISO.
6. **Verifique a instalação** com os comandos no terminal:
   ```bash
   mysql --version
   node -v
   python3 --version
   # Considerações Finais
# Considerações Finais👨‍🏫

## Lições Aprendidas🧑‍💼
- **Planejamento de Requisitos:** A definição dos requisitos foi essencial para garantir um bom desempenho do ambiente virtual.
- **Configuração da VM:** O VirtualBox facilitou a criação, mas ajustes detalhados são necessários para otimizar o desempenho.
- **Escolha do Ubuntu:** O Ubuntu foi a melhor opção devido à sua facilidade de uso e suporte aos softwares necessários.

## Sugestões de Melhoria🤓☝️
- **Otimização:** Usar versões mais leves do Ubuntu pode ajudar em máquinas com hardware limitado.
- **Automatização:** Criar scripts para instalar os softwares necessários pode agilizar o processo.
- **Documentação:** Adicionar vídeos ou tutoriais interativos pode melhorar a compreensão.

O projeto foi uma ótima oportunidade para aprender sobre virtualização e configurar um ambiente educacional eficaz!.
