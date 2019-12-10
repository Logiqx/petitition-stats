# petition-stats

These reports are created from the [JSON](https://petition.parliament.uk/petitions.json) data available on the [UK Government and Parliament](https://petition.parliament.uk/petitions) petitions website.

The URL for the latest reports is [https://logiqx.github.io/petition-stats-www/](https://logiqx.github.io/petition-stats-www/)

Technical notes:

- A simple [IPython](https://ipython.org/) Notebook is converted to a regular [Python](https://www.python.org/) script and packaged in a [Docker](https://www.docker.com/) image

- An hourly [Jenkins](https://jenkins.io/) job runs in [AWS](https://aws.amazon.com/) and the latest reports are pushed to [GitHub](https://github.com/) / [GitHub Pages](https://pages.github.com/)
