# Dockerized rails application development

[![GuardRails badge](https://badges.production.guardrails.io/shtakai/dockerized-rails-example.svg)](https://www.guardrails.io)

## Usage

```
# Build images
$ make build

# Setup
$ make setup

# Run services
$ make up

# run rails console
$ bin/spring rails c

# run rake task
$ bin/spring rake db:migrate
```

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
