# How to run AI LLM locally (Mac OS) in simple steps

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
```
pip3 install open-webui
pip3 show open-webui | grep Location
```
Now, the output will be something like this:
`Location: /Users/username/.asdf/installs/python/3.11.0/lib/python3.11/site-packages`
replace this `/lib/` with `/bin/`, ignore the rest after `/lib/`, then add it to your path (you can also add it to your .zshrc
```
export PATH=$PATH:/Users/username/.asdf/installs/python/3.11.0/bin/
```

Now you should be able to run Open WebUI:
```
open-webui serve
```

Wait a bit, and you should be able to access it here: (http://localhost:8080/)[http://localhost:8080/]
