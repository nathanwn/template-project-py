PIP_COMPILE_FLAGS:=--generate-hashes --resolver=backtracking --allow-unsafe --strip-extras

all: requirements.txt requirements-dev.txt
.PHONY: all

requirements.txt: pyproject.toml
	pip-compile ${PIP_COMPILE_FLAGS} --output-file=$@ $<

requirements-dev.txt: pyproject.toml
	pip-compile --extra dev ${PIP_COMPILE_FLAGS} --output-file=$@ $<
