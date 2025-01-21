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

Other details can be found in the [llama.cpp](https://github.com/ggerganov/llama.cpp)

