<p align="center"><a href="https://www.deeplearningindaba.com" target="_blank" rel="noopener noreferrer"><img src="https://github.com/deep-learning-indaba/Baobab/raw/develop/baobab_logo_small.png" alt="Baobab Logo"></a></p>

![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
[![Slack Status](https://img.shields.io/badge/slack-join_chat-white.svg?logo=slack&style=social)](https://join.slack.com/t/baobab-space/shared_invite/enQtOTc1MzUzNjAyODY0LTM2YmJiOTRiNWEyZWRjMjY5ZmNlYTNjY2Y3ODA4MjZjNDljZTFkZWU3YjU5OTk1MTI5MDQwYzI4YzQ0YjFiYzQ)
![Slack Status](https://img.shields.io/twitter/follow/DeepIndaba?label=Follow&style=social)
[![deep-learning-indaba](https://circleci.com/gh/deep-learning-indaba/Baobab.svg?style=shield)](https://app.circleci.com/pipelines/github/deep-learning-indaba/Baobab?branch=develop)

## What is Baobab?

Baobab is an end-to-end event management platform that facilitates the application, selection, and registration process for conferences in the ML community. Currently used by the [Deep Learning Indaba](https://deeplearningindaba.com/), [Eastern European Machine Learning Summer School](https://www.eeml.eu/), and [AI4D](https://africa.ai4d.ai/).

## Key Features
 - Fully customisable application and review forms.
 - Automated email notification system for each stage of the .
 - Support for multiple languages.

## Getting started

First build the docker images.
```console
$ docker-compose build
```
Then start up the application
```console
$ docker-compose up
```
The front-end will be available at `localhost:8080` and the backend REST API at `localhost:5000`.

## Technology Stack
**Backend**

Contained in `api/`
* **Language**: [Python](https://www.python.org/)
* **Database**: [PostgreSQL](https://www.postgresql.org/)
* **ORM**: [SQLAlchemy](https://www.sqlalchemy.org/)
* **REST API**: [Flask](http://flask.pocoo.org/)

**Frontend**

Contained in `webapp/`
* **Language**: [Javascript](https://developer.mozilla.org/bm/docs/Web/JavaScript)
* **Components**: [ReactJS](https://reactjs.org/)
* **CSS**: [Bootstrap 4](https://getbootstrap.com/)

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Hall of Fame
[![](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/images/0)](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/links/0)[![](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/images/1)](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/links/1)[![](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/images/2)](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/links/2)[![](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/images/3)](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/links/3)[![](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/images/4)](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/links/4)[![](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/images/5)](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/links/5)[![](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/images/6)](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/links/6)[![](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/images/7)](https://sourcerer.io/fame/avishkar58/deep-learning-indaba/Baobab/links/7)

## License

[Apache License 2.0](LICENSE).
