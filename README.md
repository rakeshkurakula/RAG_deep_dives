## Exploring deep dives in ML and DL systems


- VectorDb : Qdrant
- Running qudrant in local
```python
docker run -p 6333:6333 -p 6334:6334 \
    -v $(pwd)/qdrant_storage:/qdrant/storage:z \
    qdrant/qdrant
```