## Sensu-Plugins-disk-checks

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-kannel.svg?branch=master)][1]
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-kannel.svg)][2]
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-kannel/badges/gpa.svg)][3]
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-kannel/badges/coverage.svg)][4]
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-kannel.svg)][5]

## Functionality

## Files
 *
 *
 *
 *

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-kannel -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-kannel`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-kannel' do
  options('--prerelease')
  version '0.0.1.alpha.4'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-kannel' do
  options('--prerelease')
  version '0.0.1.alpha.4'
end
```

## Notes

[1]:[https://travis-ci.org/sensu-plugins/sensu-plugins-kannel]
[2]:[http://badge.fury.io/rb/sensu-plugins-kannel]
[3]:[https://codeclimate.com/github/sensu-plugins/sensu-plugins-kannel]
[4]:[https://codeclimate.com/github/sensu-plugins/sensu-plugins-kannel]
[5]:[https://gemnasium.com/sensu-plugins/sensu-plugins-kannel]