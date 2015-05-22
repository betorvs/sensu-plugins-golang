## Sensu-Plugins-golang

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-golang.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-golang)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-golang.svg)](http://badge.fury.io/rb/sensu-plugins-golang)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-golang/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-golang)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-golang/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-golang)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-golang.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-golang)
[ ![Codeship Status for sensu-plugins/sensu-plugins-golang](https://codeship.com/projects/cdd081c0-e2d1-0132-77af-0e8782f5ebb8/status?branch=master)](https://codeship.com/projects/81564)

## Functionality

## Files
 * bin/metrics-golang-stats-api

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-golang -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-golang`

#### Bundler

Add *sensu-plugins-golang* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-golang' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-golang' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
