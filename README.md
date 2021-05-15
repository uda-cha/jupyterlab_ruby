# jupyterlab_ruby

## Setup

```sh
$ sudo apt-get install libzmq3-dev libffi-dev
$ pipenv sync
$ bundle install --path .bundle
$ bundle exec iruby register 
```

## Start

```sh
$ bundle exec pipenv run jupyter-lab --no-browser
```
