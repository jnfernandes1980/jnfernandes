# João N. Fernandes – personal website

Source for my academic website, published at <https://jnfernandes1980.github.io/jnfernandes/>.

I am an Assistant Researcher at LNEC (National Laboratory for Civil Engineering, Lisbon), invited Assistant Professor at NOVA FCT and co-founder of HydroAI. My work covers hydraulics, hydrology, remote sensing and AI-based water monitoring.

## Structure

| Folder | Content |
| --- | --- |
| `_pages/` | About, CV, Publications, Projects and Teaching pages |
| `_publications/` | One file per journal paper |
| `_projects/` | One file per project |
| `_teaching/` | One file per course |
| `_config.yml` | Site settings and sidebar profile |
| `_data/navigation.yml` | Top menu |

## Running locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

The site is then served at `http://localhost:4000/jnfernandes/`.

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template (MIT License).
