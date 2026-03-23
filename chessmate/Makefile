.PHONY: lint format typecheck test pre-commit install-hooks

lint:
	uv run ruff check .

format:
	uv run ruff format .

typecheck:
	uv run mypy src

test:
	uv run pytest tests

pre-commit:
	uv run pre-commit run --all-files

install-hooks:
	uv run pre-commit install
