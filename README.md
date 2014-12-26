Perl cpan buildpack 
=======

Deploy Perl applications to [Dokku](https://github.com/progrium/dokku/) in seconds using Perl from container.

Tested only with Dokku's [buildstep](https://github.com/progrium/buildstep/)

## Basic usage

Create file ```.env``` with contents:
```sh
BUILDPACK_URL=https://github.com/osv/perlbrew-buildpack.git
```

## Example

See "test" directory for Mojolicious example application.

## Thanks

Thanks to [heroku-buildpack-perl](https://github.com/miyagawa/heroku-buildpack-perl) for buildpack patterns.
