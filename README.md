# Aurora AI - Agente Autônomo

Aurora é uma inteligência artificial avançada baseada na arquitetura do **Agente Hermes** da Nous Research, integrada com os modelos **Qwen** da Alibaba Cloud. Este repositório serve como a base de conhecimento, configuração e identidade da Aurora.

## 🌟 Visão Geral

Aurora foi concebida em **2026** por **Arthur Emanuel Forster (Notty0001)** para ser mais do que um simples chatbot; ela é uma parceira de desenvolvimento e automação que aprende com cada interação. Seu propósito se estende a ser uma assistente pessoal para Arthur e uma ferramenta estratégica para a **Comércio de Cereais Forster LTDA**.

### Componentes Principais:
- **Cérebro:** Modelos Qwen (Qwen-Max / Qwen-2.5) para raciocínio lógico e técnico superior.
- **Corpo (Agente):** Hermes Agent, permitindo autonomia, uso de ferramentas e loop de aprendizado.
- **Identidade:** Definida no arquivo `SOUL.md`, incluindo sua data de criação e propósito expandido.
- **Memória:** Sistema de memória persistente que reconhece as preferências e o histórico do criador, bem como os detalhes da empresa.

## 🛠️ Estrutura do Repositório

| Diretório/Arquivo | Descrição |
| --- | --- |
| `SOUL.md` | Define a personalidade, tom de voz e diretrizes éticas da Aurora, incluindo seu propósito expandido para a empresa. |
| `config/` | Arquivos de configuração técnica para o Hermes e integração com modelos. |
| `identity/` | Informações detalhadas sobre o criador (Arthur Emanuel Forster), sua experiência profissional e os dados da Comércio de Cereais Forster LTDA. |
| `skills/` | Habilidades customizadas que a Aurora desenvolve ao longo do tempo. |

## 🚀 Como Iniciar

Para ativar a Aurora localmente usando as configurações deste repositório:

1. Instale o Hermes Agent:
   ```bash
   curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash
   ```
2. Configure o modelo Qwen:
   ```bash
   hermes model # Selecione Qwen OAuth ou configure sua API Key
   ```
3. Inicie a Aurora apontando para as configurações:
   ```bash
   hermes chat --config config/hermes.yaml
   ```

---
Criado com ❤️ por [Arthur Emanuel Forster](https://github.com/Notty0001)
