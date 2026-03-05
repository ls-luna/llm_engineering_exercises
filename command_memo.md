# Ollama
## Start the serve
<!-- Usually it's already running in the background -->
ollama serve 
ollama run llama3.2
<!-- gemma3:270m, gpt-oss, -->

## Restart 
pkill ollama

## Others
ollama list

Stop the conversation: Ctrl+D, or type /exit.

## Check if ollama is already running:
lsof -i :11434
kill -9 <PID>
