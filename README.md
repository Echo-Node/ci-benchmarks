# ci-benchmarks

A Polymath-style benchmark site built with MkDocs and deployed on GitHub Pages.

## Prerequisites

- **Python** ≥ 3.7  
- **Git**  
- A GitHub account with a repo named `ci-benchmarks` under your username or organization.

## Local Setup & Preview

1. **Clone the repo**  
	```bash
	git clone https://github.com/Echo-Node/ci-benchmarks.git
	cd ci-benchmarks
	```

2. **Create & activate a virtual environment**
	```bash
	python3 -m venv .venv
	source .venv/bin/activate
	```

3. **Install dependencies**
	```bash
	pip install mkdocs-material pymdown-extensions
	```

4. **Serve locally**
	```bash
	mkdocs serve
	```

## Deploy to GitHub Pages

1. **Commit any changes**
	```bash
	git add .
	git commit -m "Ready for deploy"
	```

2. **Deploy with MkDocs**
	```bash
	mkdocs gh-deploy
	```
If you get a non-fast-forward error, force an overwrite with:
	```bash
	mkdocs gh-deploy --force
	```


