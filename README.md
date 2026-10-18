# job-queue

Deterministic job queue with retry, exponential backoff and dead-letter state.

Python 3.11+; no third-party dependencies.

## Run tests

From the repository root:

```sh
python -m unittest discover -s . -p 'test_core.py' -v
```

## Contents

- `core.py`: implementation
- `test_core.py`: unit tests and usage examples
- `.github/workflows/tests.yml`: CI tests on Python 3.11–3.13

## Production limitations

Demonstration uses in-memory queue state. For production add durability, worker leases, distributed coordination and observability.

This is a learning/portfolio reference, not an audited production service.
