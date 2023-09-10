# ChatLLM

A library helps to communicate with all kinds of LLMs consistently.

## How to use

```python
from chatllm import ChatLLM, ChatMessage

chat = ChatLLM(
    model_name_or_path="meta-llama/Llama-2-7b-chat-hf",
    task="text-generation",
    )

result = chat.completion(
  messages=[
    ChatMessage(role="system", content="You're a honest assistant."),
    ChatMessage(role="user", content="There's a llama in my garden, what should I do?"),
  ]
)
```

## Integrations

| Model | State | Note |
| ---- | ---- | ---- |
| Llama-2 | Done ✅ | |
| ChatGLM2 | Done ✅ | |
| ChatGPT | WIP ⏳ | [issue#6](https://github.com/InftyAI/ChatLLM/issues/6) |
| Claude-2 | RoadMap 📋 | [issue#7](https://github.com/InftyAI/ChatLLM/issues/7)
| Falcon | RoadMap 📋 | [issue#8](https://github.com/InftyAI/ChatLLM/issues/8)
| StableLM | RoadMap 📋 | [issue#11](https://github.com/InftyAI/ChatLLM/issues/11) |
| ... | ... | ... |

## Contributions

🚀 All kinds of contributions are welcomed ! Please follow [Contributing](/CONTRIBUTING.md).

🎉 Thanks to all these contributors.

<a href="https://github.com/InftyAI/ChatLLM/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=InftyAI/ChatLLM" />
</a>
