# Roteiro de Estudo para Implementação de Assistente de Voz Conversacional em Python

Desenvolveremos um aplicativo em Python com inteligência artificial, capaz de compreender comandos de voz e responder de forma contextualizada, com base em cenários previamente configurados. Para isso, este repositório apresenta um plano de estudo detalhado voltado à criação de um protótipo de assistente de voz conversacional, com foco no uso de tecnologias de código aberto e na otimização de recursos.

## Resumo
O projeto combina Processamento de Linguagem Natural e Síntese de Fala para criar personagens interativos destinados a ambientes de jogos, proporcionando uma experiência imersiva e de baixo consumo computacional.

---

## Tecnologias Utilizadas
O sistema baseia-se na integração de três modelos principais:

1. **STT (Speech-to-Text):** **Whisper Large-v3** para reconhecimento de fala.
2. **LLM (Language Model):** **Qwen3.5-0.8B** para geração de linguagem natural e respostas contextuais.
3. **TTS (Text-to-Speech):** **Kokoro-82M** para síntese de fala de alta qualidade.

---

## Metodologia e Etapas de Implementação

### 1. Fundamentação e Ambiente
* Configuração do Python 3.13 e gerenciador de pacotes pip.
* Criação de ambiente virtual e instalação das bibliotecas: `transformers`, `openai-whisper`, `kokoro`, `soundfile` e `espeak-ng`.

### 2. Reconhecimento de Fala (STT)
* Implementação do módulo capaz de converter áudio em texto utilizando o Whisper.
* Realização de testes de transcrição com diferentes amostras de voz.

### 3. Geração de Respostas (LLM)
* Desenvolvimento do módulo de processamento de texto com Qwen.
* Experimentação com prompts e criação de um sistema básico de gerenciamento de contexto.

### 4. Síntese de Voz (TTS)
* Implementação da síntese de fala com o modelo Kokoro.
* Ajustes de voz, entonação e velocidade para garantir uma saída natural.

### 5. Integração dos Módulos
* Criação de um script principal para orquestrar o fluxo: **Entrada de Áudio > Resposta da IA > Saída em Áudio**.
* Otimização de desempenho para garantir baixo consumo de CPU/GPU.

### 6. Definição de Personagens
* Criação de cinco personagens distintos com características e estilos de diálogo próprios através de engenharia de prompt.

---

## Referências
* **Whisper Large-v3:** [https://huggingface.co/openai/whisper-large-v3](https://huggingface.co/openai/whisper-large-v3)
* **Qwen3.5-0.8B:** [https://huggingface.co/Qwen/Qwen3.5-0.8B](https://huggingface.co/Qwen/Qwen3.5-0.8B)
* **Kokoro-82M:** [https://huggingface.co/hexgrad/Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M)

---
**Autor:** Victor Arruda Gonçalves Rodrigues
