# run_r1_locally

Make sure you run Ollama locally:
```
brew install ollama
brew services start ollama # alternatively "brew services restart ollama" or "brew services stop ollama"
ollama list
```

Go see the model with varying parameter sizes you'd like to use (be aware of the size — the bigger is slower): https://ollama.com/library/deepseek-r1

Now you can run in CLI:
```
ollama run deepseek-r1
```

Web UI instructions ... coming soon.
