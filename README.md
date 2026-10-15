# github-student15

Mini CI/CD: Python + pytest + Docker + GitHub Actions.

## Uruchomienie lokalne
    pip install -r requirements.txt
    pytest

## Uruchomienie w Dockerze
    docker build -t github-student:local .
    docker run --rm github-student:local
