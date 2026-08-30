SHELL := /usr/bin/zsh

.PHONY: 

# Default target

run-mcp-lab:
	uv run mcp-lab

run-mcp-lab-inspector:
	npx @modelcontextprotocol/inspector --server-url http://localhost:8000/mcp --transport http

clean:
	@echo "Nothing to clean."