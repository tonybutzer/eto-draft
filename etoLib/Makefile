PIP=pip install --user -e .
PIPR=pip install .
build:
	${PIP}

build-root:
	${PIPR}

git:
	(cd ..; make)

list:
	python list_modules_package_etoLib.py


example:
	python3 example.py
