[![GCP Python 3.7](https://github.com/brunomariz/duke-ccf-gcp-cd/actions/workflows/main.yml/badge.svg)](https://github.com/brunomariz/duke-ccf-gcp-cd/actions/workflows/main.yml)

# Duke - Cloud Computing Foundations - GCP CD

Demo repo for GCP CD assignment of Cloud Computing Foundations course.

Video script: [video_script.md](video_script.md)

Demo Video created as assignment for Cloud Computing Foundations course by Duke University on Coursera:

[![Video thumbnail consisting of Google Cloud Build and GitHub Actions logos](https://img.youtube.com/vi/GznERAg7AsY/0.jpg)](https://www.youtube.com/watch?v=GznERAg7AsY)


## Video notes

### Steps:

1. Create git repository
2. Create Google Cloud project
3. Open Cloud Console
4. Create ssh key and add to GitHub

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

5. Clone repo
6. Open editor and create project files
8. Create venv and install dependencies

```bash
$ python -m venv ~/.venv_name
$ source ~/.venv_name/bin/activate
$ make install
```

9. Test code

```bash
$ make lint
$ make format
$ make test
```

10. Enable Cloud Build
11. Create trigger
12. Configure Cloud Build Settings
    1. App Engine
    2. Service Accounts
13. Push files to GitHub
14. Setup GitHub Actions
15. Create cloudbuild.yaml
16. Test everything
