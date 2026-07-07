# Retrieval-Augmented Generation

This section contains a sketch of the RAG pipeline.

The diagram covers:

- chunks
- embedding models
- vectors
- vector databases
- semantic search
- retrieval logic
- top-k relevance tradeoffs

## Files

- [`rag.excalidraw`](rag.excalidraw)

## Notes To Refine

- Fix spelling in the diagram: `Emeddings` to `Embeddings`, `RETREIVE` to `RETRIEVE`.
- Clarify the idea behind "retrieval lottery": retrieval can miss useful context when similarity scoring, chunking, metadata, or top-k settings are weak.
- Add a second version showing query, retrieval, reranking, context assembly, and final LLM response.
