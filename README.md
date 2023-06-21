# Cowsay Demon appearing from the terminal

<!-- ## Travis CI badges and github actions
# Logo: Framework, tool, base of the project not all  -->

<!-- Markdown link & img dfn's -->

<!-- [npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/escummy/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/escummy/node-datadog-metrics
[wiki]: https://github.com/escummy/yourproject/wiki -->

> Run the script to check 'Cowsay Demon' prompt drawed with characters by console.

<br>

<!-- ## Snapshots -->

<p align="center">
  <img src="https://github.com/escummy/cowsay-demon/assets/90976678/ebce7702-d83c-4e46-b461-036331379790" width="95%" title="Python demon cowsay screenshot" alt="accessibility text">
</p>

<br>

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy on a live system and clone the repository.

<br>

- (Option 1): Clone the repository with link "https"

```bash
  git clone https://github.com/escummy/cowsay-demon.git
```

- (Option 2): Clone the repository with link "SSH"

```bash
  git clone git@github.com:escummy/cowsay-demon.git
```

- (Option 3): Download the file.zip to your desktop

<br>

### # Prerequisites

To continue, you need to have installed: `Python 3.11.0`

<br>

(Check in your terminal bash)

```
python --version
```

<br>

Else, Install python from the official Santander "Install now" app in the desktop, check versions availables to compare with the available 'version LTS' in ther official documentation.
 
> [English] - https://www.python.org/downloads/ (or) [Spanish] - https://docs.python.org/es/3/tutorial/
 
<br>

## Setup a virtual environment for working locally

```bash
  $ python -m venv venv
```

<br>

## Activate virtual environment before install

- For linux/macOS

```bash
  $ source venv\bin\activate
```

- For windows

```bash
  $ .\venv\Scripts\activate
```

<br>
 
## Installing dependencies
 
Upgrade pip in case of deprecated version to avoid intallation issues.
 
```bash
$ pip install --upgrade pip
```
<br>
 
> Dependencies are defined in `requirements.txt` and can be installed manually.
 
```bash
$ pip install -r requirements.txt
```

<br>

## Run python project

The application can be run locally for testing purposes leveraging the source folder to find exactly the `main.py` application as follows:

```shell script
$ python src/main.py
```

<br>

## Executing automated tests

Tests are run with [**pytest**](https://docs.pytest.org/) leveraging the dependencies defined in `requirements-dev.txt` including unit-test and global-test, applying documentation from continuous integration with github actions if required.

> Break down into end to end tests in development

```bash
$ pip install -r requirements-dev.txt
```

<br>

## Running tests

Explain what these tests test and why

```
$ pytest
```

<!-- The application **DOES NOT** bundle the Django settings file required for running the application.
Please refer to the [official documentation](https://docs.djangoproject.com/en/2.1/topics/settings/)
for more information regarding how the Django may be configured.
In the same manner, the application **DOES NOT** bundle any additional configuration that may be required
for running the application within an WSGI HTTP Server such as [Gunicorn](https://gunicorn.org/),
the solution used by the _Python Gunicorn Runner_.

Please refer to the product's documentation for more information regarding how
the server may be configured and integrated with a Django-based WSGI application.

<br>
 
## Learn More
 
To learn Python for beguiners, check out the [Python official documentation](https://wiki.python.org/moin/BeginnersGuide).

> Recomendations:
>> - Check this visual studio code [settings.json](https://github.com/escummy/vscode-settings-json)
>> - To install the necessary extensions, add 'missing extensions' to your vscode
 
<br>
 
<!-- Change link path for each repository (automate actions CI/gist)-->
 
Repositories use [SemVer](http://semver.org/) for versioning, three-digit numbering technique based patter of Major, Minor and Patch fixes, see the [release tags](https://github.com/escummy/cowsay-demon/tags) for more details about version available.
 
<br>

## Contributing

Contributions are always welcome.

See [CONTRIBUTING](.github/CONTRIBUTING.md) for ways to get started, you can colaborate addings features to improve the repository, you can feel free to suggest anything or help solving issues via pull request.

<!-- Please read [CONTRIBUTING.md](https://gist.github.com/escummy/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests. -->

Please adhere to this project [CODE_OF_CONDUCT](.github/CODE_OF_CONDUCT.md), examples of behavior that contributes to a positive environment for our community and adapted from the Contributor Covenant, version 2.0, available at https://www.contributor-covenant.org/version/2/0/code_of_conduct.html

> **[Author]**: Gonzalo Cugiani (Amsterdam, North Holland, Netherlands)
>
> - [www.github.com/github.com/escummy](https://github.com/escummy)
> - [www.linkedin.com/in/gonzalocugiani](https://linkedin.com/in/gonzalocugiani)
> - [www.stackoverflow.com/gonzalocugiani](https://stackoverflow.com/users/20149906/gonzalo-cugiani)

<br>

## About Licenses

A licensor may grant a license under intellectual property laws to authorize a use (such as copying software or using a patented invention) to a licensee, sparing the licensee from a claim of infringement brought by the licensor.

<!-- Change link path for each repository (automate actions CI/gist)-->

License used for this repository <a href="https://github.com/escummy/cowsay-demon/blob/main/LICENSE">`[`MIT License`]`</a>

<!-- #### Hashtags

#webpack #starter #initialfiles #developmentmode #productionmode #packagejson #webpackconfig #babelconfig #dev #prod #npmstart #yarnstart #build #builddev #buildprod #github #badges -->

<br><br>

---

<p align="center">. . .</p>

<p align="center">This <i>README</i> file was updated</br>Last refresh: Wednesday, 19 Jan, 11:28 CET<br/></p>

<br><br><br>
