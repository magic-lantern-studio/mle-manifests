# mle-manifests

Google 'repo' manifest files for Magic Lantern host development environment.

## Getting Started

These instructions can be used to retreive a copy of the Magic Lantern git repositories for building an image on your local machine for development and testing purposes.
n
### Prerequisites

The Magic Lantern git repositories are retrieved using the Google 'repo' command. Use the following commands to install 'repo':

```
$ mkdir $HOME/.bin/
$ export PATH=$PATH:$HOME/.bin/repo >> $HOME/.profile
$ curl https://storage.googleapis.com/git-repo-downloads/repo > $HOME/.bin/repo
$ chmod a+x $HOME/.bin/repo
```

### Installing

This section provides a step-by-step series of instructions that tell you how to get a host development environment running. 

Initialize the repositories using the default manifest located on Githyb.

```
$ repo init -u git@bitbucket.org:tchwb2/alticast-manifests
```

Synchronize the repositories, retreiving the source and binary artifacts required for creating the Magic Lantern artifacts (i.e. libraries, executables, etc.).

```
$ repo sync
```

## Running the smoke tests

Explain how to run the smoke tests for this system.

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system.

## Built With

## Contributing

## Versioning

## Authors

Mark Millard, Wizzer Works (msm@wizzerworks.com)

## Licenses

The MIT License (see https://opensource.org/licenses/MIT)

## Acknowledgments
