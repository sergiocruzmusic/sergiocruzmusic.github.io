# Developer Guide

This guide outlines the steps to set up the project locally for development.

## Prerequisites

- **Ruby**: Ensure Ruby is installed (version 3.x recommended).
- **Bundler**: Update or install bundler:
  ```bash
  gem install bundler
  ```

## Setup

1. Clone the repository.
2. Install dependencies:
   ```bash
   bundle install
   ```

## Running Locally

To start the local server with live reloading:

```bash
bundle exec jekyll serve
```

Access the site at: [http://localhost:4000](http://localhost:4000)

## Project Structure

- `_data/`: Contains YAML files for dynamic content (Videos, Contact info).
- `_config.yml`: Main Jekyll configuration.
- `index.html`: Homepage layout.
- `assets/`: Static assets (CSS, Images).
