# Enhancing Maritime Safety

GitHub Pages microsite for EPSRC project EP/X035778/1.

The site is intentionally high level while project outputs are in preparation. Unpublished source notes are excluded from publication by `.gitignore` and Jekyll configuration.

## Project Outputs
Project output pages are markdown files in `_outputs/`. Add a new output by creating a new `.md` file with front matter for `title`, `output_title`, `lead`, `status`, `image`, `order`, and `description`.

The landing page reads from the `outputs` collection, so output cards and output detail pages stay in sync.

## Local Preview
This site uses Jekyll layouts and includes so shared navigation and page chrome are defined once.
Use a current Ruby installation rather than macOS system Ruby.

```bash
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000
```

Then open `http://localhost:4000`.

If there is no GitHub `origin` remote configured locally, GitHub Pages metadata may ask for a repository name. In that case, prefix the serve command:

```bash
PAGES_REPO_NWO=<owner>/<repo> bundle exec jekyll serve --host 127.0.0.1 --port 4000
```

GitHub Pages reads `_config.yml`, including the Cayman remote theme setting.
