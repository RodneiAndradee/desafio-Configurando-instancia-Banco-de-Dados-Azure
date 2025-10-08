# 💾 Desafio: Configurando Instância de Banco de Dados no Azure

## 🌐 Visão Geral
Este projeto faz parte de um desafio prático que explora a **configuração de máquinas virtuais e a configuração de uma instância de bancos de dados** na plataforma **Microsoft Azure**.  
O objetivo é entender as opções de criação, personalização e gerenciamento de recursos na nuvem.

---

## ⚙️ Criação de Máquinas Virtuais (VMs)
Durante a criação de uma **máquina virtual**, algumas opções e parâmetros importantes devem ser definidos:

- **Imagem (Image):**  
  Define o sistema operacional base da VM. Cada imagem possui um valor específico de custo.
  
- **Discos adicionais:**  
  É possível adicionar discos extras para armazenamento conforme a necessidade do projeto.

- **Configurações de rede:**  
  Inclui a criação ou seleção de redes virtuais, sub-redes e grupos de segurança.

- **Recursos e escalabilidade:**  
  Permite ajustar o tamanho da VM, número de CPUs, memória e outras opções relacionadas ao desempenho.

---

## 🗄️ Criação de Banco de Dados
Na configuração de um **banco de dados no Azure**, alguns passos essenciais devem ser seguidos:

1. **Criação de um servidor:**  
   Cada banco de dados precisa estar vinculado a um servidor, que possui suas próprias configurações (nome, região, autenticação, etc).

2. **Definição do modelo de redundância:**  
   Escolher o nível de redundância é importante para garantir **alta disponibilidade** e um **SLA (Service Level Agreement)** adequado.

3. **Cálculo do custo mensal:**  
   Ao finalizar a configuração, o Azure exibe uma estimativa do custo mensal com base nas opções selecionadas.

---

## ☁️ Modelos de Serviço na Nuvem
Todo o cenário de gerenciamento e provisionamento de recursos está associado a um dos modelos de serviço em nuvem:

- **IaaS (Infrastructure as a Service):** Infraestrutura gerenciada pelo usuário.  
- **PaaS (Platform as a Service):** Plataforma gerenciada pelo provedor, com foco em desenvolvimento.  
- **SaaS (Software as a Service):** Aplicações prontas para uso, totalmente gerenciadas pelo provedor.

---

## 🚀 Conclusão
Esse desafio mostra como o **Azure** oferece flexibilidade e controle total sobre os recursos em nuvem.  
Com o entendimento dos modelos de serviço e das opções de configuração, é possível criar soluções robustas, escaláveis e otimizadas em custo. 💡

---

> 💬 **Dica:** Explore as opções do **Azure Portal** e teste diferentes configurações para entender o impacto em desempenho e custo.
