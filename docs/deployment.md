# Deployment

## App

Run locally with `uvicorn src.app.main:app --reload` or build the container with `docker build -t edtech-learning-path-recommender .`.

## Landing page

This repository includes a static 3D landing page in `docs/`. It is designed for GitHub Pages publishing at:

`https://r-behera.github.io/edtech-learning-path-recommender/`

## CI

A lightweight GitHub Actions workflow checks Python setup and smoke-test structure.
