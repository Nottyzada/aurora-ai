# Modelos de Linguagem da Aurora

Este diretório é destinado a documentar e, eventualmente, conter configurações ou referências para os modelos de linguagem utilizados pela Aurora. Atualmente, a Aurora utiliza a família de modelos **Qwen** da Alibaba Cloud.

## 🧠 Integração do Modelo Qwen

O modelo Qwen não é armazenado diretamente neste repositório devido ao seu tamanho. Em vez disso, o **Hermes Agent** é configurado para interagir com o modelo Qwen através de APIs ou provedores de serviço.

- **Provedor:** `qwen-oauth` (ou outro método de autenticação via API Key, conforme configurado no `config/hermes.yaml`)
- **Modelo Padrão:** `qwen-max` (ou a versão específica definida na configuração)

### Como o Hermes Agent Acessa o Qwen

O Hermes Agent, ao ser inicializado, utiliza as configurações em `config/hermes.yaml` para estabelecer conexão com o provedor do modelo Qwen. Isso pode envolver:

1. **Autenticação OAuth:** Para provedores como `qwen-oauth`, o Hermes gerencia o processo de autenticação para acessar o modelo.
2. **Chaves de API:** Para acesso direto, uma chave de API (e.g., `DASHSCOPE_API_KEY` para Alibaba DashScope) seria configurada no ambiente do Hermes.

## 📂 Estrutura Futura (Opcional)

Em cenários futuros, este diretório poderia conter:
- **Modelos Quantizados:** Versões menores de modelos para execução local.
- **Configurações de Fine-tuning:** Arquivos de configuração para adaptar modelos pré-treinados a tarefas específicas.
- **Scripts de Download:** Scripts para baixar e configurar modelos de repositórios externos.

---
*Documento elaborado por Manus AI, sob a supervisão de Arthur Emanuel Forster (Notty0001).*
