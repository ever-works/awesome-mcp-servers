## Tools
- `validate`: Checks if a dataset exists and is accessible.
- `get_info`: Retrieves detailed information about a dataset.
- `get_rows`: Gets paginated contents of a dataset.
- `get_first_rows`: Retrieves first few rows from a dataset split.
- `get_statistics`: Gets statistics about a dataset split.
- `search_dataset`: Searches for text within a dataset.
- `filter`: Filters rows using SQL-like conditions.
- `get_parquet`: Downloads entire dataset in Parquet format.

## External APIs and technologies
- Hugging Face Dataset Viewer API
- httpx: HTTP client
- Python 3.12+

## Configuration requirements
- `HUGGINGFACE_TOKEN` (optional): For private datasets.