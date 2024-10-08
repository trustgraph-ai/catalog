# Extraction Notes

## Source

- **Source Document**: Synthetic Cosmology (generated document using Claude 3.5 Sonnet)
- **Source Tokens**: ~10,000

## Chunking

- `chunker-recursive`

## Best Extractions per Model

|  Model  |  Graph Edges | Chunk Size |
| ------- | ------------ | ---------- |
| Mixtral8x7B | 3,226 | 500 |
| Gemini 1.5 Flash | 3,084 | 500 |
| Haiku | 2,975 | 500 |
| Sonnet 3.5 | 2,575 | 500 |
| Llama 3.1:8B | 2,439 | 500 |
| Mistral Large | 2,266 | 500 |
| Gemma2:9B | 2,078 | 500 |
| Qwen2:7B | 1,676 | 500 |

## Mistral Extractions

### Mistral 1

- **Model**: `Mistral Large 2407`
- **Chunking**: `2,000`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `1,455`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Mistral 2

- **Model**: `Mistral Large 2407`
- **Chunking**: `1,000`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `1790`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Mistral 3

- **Model**: `Mistral Large 2407`
- **Chunking**: `500`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `2266`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Mistral 4

- **Model**: `Mistral Large 2407`
- **Chunking**: `4000`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `1125`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Mistral 5

- **Model**: `Mistral Large 2407`
- **Chunking**: `8000`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `1114`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

## Sonnet 3.5 Extractions

### Sonnet 1

- **Model**: `Claude 3.5 Sonnet`
- **Chunking**: `8,000`
- **Deployment**: `Anthropic`
- **Extracted Graph Edges**: `1220`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Sonnet 2

- **Model**: `Claude 3.5 Sonnet`
- **Chunking**: `4,000`
- **Deployment**: `Anthropic`
- **Extracted Graph Edges**: `1230`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Sonnet 3

- **Model**: `Claude 3.5 Sonnet`
- **Chunking**: `2,000`
- **Deployment**: `Anthropic`
- **Extracted Graph Edges**: `1555`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Sonnet 4

- **Model**: `Claude 3.5 Sonnet`
- **Chunking**: `1,000`
- **Deployment**: `Anthropic`
- **Extracted Graph Edges**: `2066`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Sonnet 5

- **Model**: `Claude 3.5 Sonnet`
- **Chunking**: `1,000`
- **Deployment**: `Anthropic`
- **Extracted Graph Edges**: `2575`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

## Haiku Extractions

### Haiku 1

- **Model**: `Claude 3 Haiku`
- **Chunking**: `2,000`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `1,710`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Haiku 2

- **Model**: `Claude 3 Haiku`
- **Chunking**: `1,500`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `1,728`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Haiku 3

- **Model**: `Claude 3 Haiku`
- **Chunking**: `4,000`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `1,344`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)


### Haiku 4

- **Model**: `Claude 3 Haiku`
- **Chunking**: `8,000`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `1,352`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Haiku 5

- **Model**: `Claude 3 Haiku`
- **Chunking**: `1,000`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `2,153`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Haiku 6

- **Model**: `Claude 3 Haiku`
- **Chunking**: `500`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `2,975`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

## Llama 3.1:8B Extractions

### Llama 1

- **Model**: `Llama3.1:8B`
- **Chunking**: `1,500`
- **Deployment**: `Ollama`
- **Extracted Graph Edges**: `1,543`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Llama 2

- **Model**: `Llama3.1:8B`
- **Chunking**: `500`
- **Deployment**: `Ollama`
- **Extracted Graph Edges**: `2439`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Llama 3

- **Model**: `Llama3.1:8B`
- **Version**: `0.7.10`
- **Chunking**: `1000`
- **Chunking Method**: `Recursive`
- **Deployment**: `Ollama`
- **Extracted Graph Edges**: `1918`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Llama 4

- **Model**: `Llama3.1:8B`
- **Version**: `0.7.10`
- **Chunking**: `2000`
- **Chunking Method**: `Recursive`
- **Deployment**: `Ollama`
- **Extracted Graph Edges**: `1509`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Llama 5

- **Model**: `Llama3.1:8B`
- **Version**: `0.7.10`
- **Chunking**: `4000`
- **Chunking Method**: `Recursive`
- **Deployment**: `Ollama`
- **Extracted Graph Edges**: `1121`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

## Gemma2:9B Extractions

### Gemma 1

- **Model**: `Gemma2:9B`
- **Chunking**: `1,500`
- **Deployment**: `Ollama`
- **Extracted Graph Edges**: `1,459`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Gemma 2

- **Model**: `Gemma2:9B`
- **Chunking**: `500`
- **Deployment**: `Ollama`
- **Extracted Graph Edges**: `2078`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

## Qwen2 Extractions

### Qwen2 1

- **Model**: `Qwen2:7B`
- **Chunking**: `500`
- **Deployment**: `Ollama`
- **Extracted Graph Edges**: `1676`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

## Gemini Extractions

### Gemini 1

- **Model**: `Gemini 1.5 Flash`
- **Chunking**: `500`
- **Deployment**: `VertexAI`
- **Extracted Graph Edges**: `3084`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Gemini 2

- **Model**: `Gemini 1.5 Flash`
- **Chunking**: `1000`
- **Deployment**: `VertexAI`
- **Extracted Graph Edges**: `2399`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Gemini 3

- **Model**: `Gemini 1.5 Flash`
- **Chunking**: `2000`
- **Deployment**: `VertexAI`
- **Extracted Graph Edges**: `1855`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Gemini 4

- **Model**: `Gemini 1.5 Flash`
- **Chunking**: `4000`
- **Deployment**: `VertexAI`
- **Extracted Graph Edges**: `1388`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Gemini 5

- **Model**: `Gemini 1.5 Flash`
- **Chunking**: `8000`
- **Deployment**: `VertexAI`
- **Extracted Graph Edges**: `1355`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Gemini 6

- **Model**: `Gemini 1.5 Flash`
- **Chunking**: `20000`
- **Deployment**: `VertexAI`
- **Extracted Graph Edges**: `1834`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

## Mixtral Extractions

### Mixtral 1

- **Model**: `Mixtral8x7B`
- **Chunking**: `500`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `3226`
- **Graph Store**: `Neo4j`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Mixtral 2

- **Model**: `Mixtral8x7B`
- **Version**: `0.7.10`
- **Chunking**: `1000`
- **Chunking Method**: `Recursive`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `1944`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Mixtral 3

- **Model**: `Mixtral8x7B`
- **Version**: `0.7.10`
- **Chunking**: `2000`
- **Chunking Method**: `Recursive`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `995`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)

### Mixtral 4

- **Model**: `Mixtral8x7B`
- **Version**: `0.7.10`
- **Chunking**: `4000`
- **Chunking Method**: `Recursive`
- **Deployment**: `AWS Bedrock`
- **Extracted Graph Edges**: `432`
- **Graph Store**: `Cassandra`
- **Extracted By:** [JackColquitt](https://github.com/JackColquitt)
