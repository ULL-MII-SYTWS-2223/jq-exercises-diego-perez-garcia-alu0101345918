[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=13144796)
# jq tutorial

[jq][0] is an awesome command-line utility for processing JSON data. It has an
[excellent manual][1] already, but--since there's no substitute for practice--
this tutorial provides an unofficial supplement for new users exploring its syntax
and applications.

### Running tutorial

[Download and install][2] jq, then grab a copy of this tutorial:

    $ npm install -g jq-tutorial
    $ jq-tutorial

Run individual lessons by name:

    $ jq-tutorial pick

#### Running in docker

    $ docker build -t jq-tutorial .
    $ docker run -ti jq-tutorial

### Attribution

  * jq copyright (C) 2012 [Stephen Dolan][3]
  * heavy inspiration from from Rod Vagg's [workshopper][4]

### License

MIT

[0]: http://stedolan.github.io/jq "jq"
[1]: http://stedolan.github.io/jq/manual "jq Manual"
[2]: http://stedolan.github.io/jq/download/ "Download jq"
[3]: https://github.com/stedolan
[4]: https://github.com/rvagg/workshopper "Workshopper"

