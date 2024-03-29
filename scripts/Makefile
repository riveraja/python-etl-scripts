nix:
	nix-shell -p python312Full

setup:
	python -m venv .venv
	source .venv/bin/activate
	python -m pip install --upgrade pip

install:
	pip install -r requirements.txt

clean:
	rm -f csvfiles/*.csv

test:
	python -m pytest --nbmake notebooks/scrape-wikipedia-site.ipynb