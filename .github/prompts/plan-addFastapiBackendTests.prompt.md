## Plan: Add FastAPI Backend Tests

Create comprehensive tests for the Mergington High School API backend in a separate tests directory.

**Steps**
1. Create tests/ directory structure
2. Add tests/__init__.py package marker
3. Create tests/test_app.py with TestClient-based tests
4. Test all endpoints: GET /activities, POST signup, DELETE unregister
5. Include error cases and edge conditions
6. Update requirements.txt if additional test dependencies needed

**Relevant files**
- `tests/test_app.py` — Main test file with comprehensive endpoint coverage
- `tests/__init__.py` — Package marker
- `pytest.ini` — Already configured for pythonpath

**Verification**
1. Run `pytest tests/` to execute all tests
2. Verify test coverage includes success and error cases
3. Ensure tests pass with current implementation
