# CS-GY-6063-SWE1
Course Repository for CS-GY 6063: Software Engineering I

## Project

[Proposal presentation](./bam-proposal-presentation.pdf)

Code Repositoy: [gcivil-nyu-org/INET-Monday-Spring2023-Team-5](https://github.com/gcivil-nyu-org/INET-Monday-Spring2023-Team-5)

[Final presentation](./bam-final-presentation.pdf)

Live demo: [bamnyc.pythonanywhere.com](https://bamnyc.pythonanywhere.com/)

## Personal Assignments

### Django Hello World Developed and Deployed

- Deploy working Simple Django application (https://docs.djangoproject.com/en/4.1/intro/tutorial01/) to individual AWS accounts.
- Parts 1,2,3,4 of the tutorial need to be completed. This will produce a working polls application
- Submit a URL of the working Django Application and a URL of the github repo.

Submission:
- [vchrombie/swe1-app @ f2f88ee](https://github.com/vchrombie/swe1-app/tree/f2f88eeb29d7867a3f3a4e1993f28e785478959d)
- URL of the working Django Application: http://swe1-app-py.eba-2jk4g4an.us-west-2.elasticbeanstalk.com/
- URL of the GitHub Repo: https://github.com/vchrombie/swe1-app

### Travis CI

- Setup CI/CD and test suite for the Django Application
- Configure Travis CI to run your build on push/pull requests to repository and deploy the app to AWS EB upon successful completion of the tests
- Configure code formatting with [black](https://github.com/psf/black) and [flake8](https://flake8.pycqa.org/en/latest/) linter
- Check test suite code coverage with [coverage.py](https://coverage.readthedocs.io/) & [coveralls](https://coveralls.io/) and add a badge to the `README.md`
- Enable `Require status checks to pass before merging` on your repository
- Submit your working Travis Dashboard Url.

Submission:
- [vchrombie/swe1-app @ a99d3c8](https://github.com/vchrombie/swe1-app/tree/a99d3c866cc42b34305ca99a4469691b7a2f4b07)
- [pa2.pdf](./personal-assignment-2.pdf)
- https://github.com/vchrombie/swe1-app/pulls
