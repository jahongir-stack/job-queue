# job-queue

Priority-based retry queue with exponential backoff and dead-letter job state.

## Requirements

- Python 3.11 or newer
- Standard library only

## Run tests

```bash
python -m unittest discover -s . -p 'test_core.py' -v
```

## Repository layout

- `core.py` — implementation
- `test_core.py` — unit tests
- `.github/workflows/tests.yml` — Python 3.11, 3.12 and 3.13 CI matrix

## Notes

Educational/reference implementation, not an audited production deployment. Review security, reliability, persistence, concurrency and operational requirements before production use.
