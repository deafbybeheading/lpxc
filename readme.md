#lpxc

A reference implementation of a ruby library that sends log data to Heroku's Logplex. Lpxc is not designed to be production software.

## Usage

```ruby
require 'lpxc'
Lpxc.start
Lpxc.puts(logplex_token, "hello world")
```

## Test

Grab a logplex token from an Add-on provision request and pass it to test.rb

```bash
$ ruby test.rb t.abc123
```
