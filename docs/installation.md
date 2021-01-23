# Installation

## Clone repo

```sh
$ git clone URL
$ cd react-native-quickstart
```

## Install system dependencies

Install Node.js and Yarn.

Note that is is best to use Yarn to install `expo-cli` globally. You can skip this as a manual step now - just enter `Y` to accept the prompt later on starting the web server. If you skip the step, the web server will exit.


## Install project dependencies

```sh
$ yarn install
```

If on macOS, install this:

```sh
$ brew install watchman
```

That prevents this error on serving the app:

```
Error: EMFILE: too many open files, watch
```

Based on [blog post](https://flaviocopes.com/react-native-emfile-too-many-open-files/).

> and that fixed the problem, because React Native internally was able to use watchman to watch files changes (used to provide hot reloading in the app to refresh it when a file is changed).
