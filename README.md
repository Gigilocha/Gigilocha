# 👋 Привет, я Gigilocha

**Студент в области ML / LLM Engineering**

Самостоятельно изучаю и реализую полный цикл работы с языковыми моделями — от обучения с нуля до production-ready агентов и RAG-систем.

### 🧠 Чем занимаюсь

Строю **сквозной стек** вокруг open-weights LLM:

- **Своя модель с нуля** — мультиязычная (RU/EN/code) GPT-style модель ~126M параметров
- **Fine-tuning** — шаблон полного / LoRA / QLoRA дообучения с MLflow и LLM-as-a-Judge
- **RAG** — self-hosted сервис на Qwen3 + Qdrant с гибридным поиском
- **Агенты** — модель-агностичный framework поверх LangGraph с ролями, памятью и handoff

### 🚀 Проекты

| Проект | Описание |
|--------|----------|
| **[my_llm](https://github.com/Gigilocha/my_llm)** | GPT-style модель ~126M, обученная с нуля (GQA + RoPE + SwiGLU) |
| **[Fine-tuning](https://github.com/Gigilocha/Fine-tuning)** | Универсальный шаблон дообучения open LLM |
| **[RAG](https://github.com/Gigilocha/RAG)** | Self-hosted RAG на Qwen3 + Qdrant (hybrid search) |
| **[Agent](https://github.com/Gigilocha/Agent)** | Agent-framework на LangGraph с ролями и памятью |

### 🛠 Технологии

`Python` · `PyTorch` · `Transformers` · `LangGraph` · `FastAPI` · `Qdrant` · `MLflow` · `uv` · `Docker`

**Ключевые навыки**  
- Обучение LLM с нуля (tokenizer → pretrain → SFT → DPO)  
- Efficient fine-tuning (LoRA / QLoRA / Unsloth)  
- Гибридный retrieval (dense + sparse + RRF)  
- Агентные системы (Plan-Execute, handoff, memory)  
- Чистая архитектура и воспроизводимые пайплайны

### 📫 Контакты

- Mail: [Gigilocha@yandex.ru](mailto:Gigilocha@yandex.ru)
- Telegram: [t.me/Gigilocha](https://t.me/Gigilocha)
- Канал: [t.me/SkinAI_KSE](https://t.me/SkinAI_KSE)

В канале пишу о ходе работы: к чему пришёл, какие были сложности, какие ошибки допустил и как их решал. Если интересно видеть процесс мышления и принятия решений — заходите.

---

> Разработка ведётся в рамках самостоятельного изучения ML/LLM engineering.  
> Каждый компонент реализую с пониманием «почему именно так», а не копированием готовых решений.