# llama.cpp

This is a repo for llama.cpp with EdgePLM model arch.

## How to run

Clone the repo

```bash
git clone https://github.com/Si1w/EdgeLLM-llama.cpp.git
```

Build the project

```bash
cd EdgeLLM-llama.cpp
cmake -B build
cmake --build build --config Release
```

### llama-cli

```bash
./build/llama-cli -m model.gguf -p "prompt" -n 128
```

### llama-bench

```bash
./build/llama-bench -m model1.gguf -m model2.gguf 
```

### Model list for test(fp16)

[Fox-1.6B](https://huggingface.co/mradermacher/Fox-1-1.6B-Instruct-v0.1-GGUF)

[Nemotron-4B](https://huggingface.co/bartowski/Nemotron-Mini-4B-Instruct-GGUF)

[Index-1.9B](https://huggingface.co/IndexTeam/Index-1.9B-Character-GGUF/tree/main)

[qwen2-1.5B](https://huggingface.co/Qwen/Qwen2-1.5B-Instruct-GGUF)

Other details can be found in the [llama.cpp](https://github.com/ggerganov/llama.cpp)

