## Sensu-Plugins-time-to-live

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-time-to-live.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-time-to-live)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-time-to-live.svg)](http://badge.fury.io/rb/sensu-plugins-time-to-live)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-time-to-live/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-time-to-live)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-time-to-live/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-time-to-live)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-time-to-live.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-time-to-live)

## Functionality

## Files
 * bin/extension-ttl

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-time-to-live -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-time-to-live`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-time-to-live' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-time-to-live' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
