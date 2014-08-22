# CentOS Events

This is the data for CentOS's event website will eventually be at:
http://www.centos.org/events/

The information in this repository is intended to cover CentOS presence
at conferences, tradeshows, and other events — ranging from CentOS 
employees giving talks at a conference to a CentOS specific event 
(sponsored event, Internet hangout, IRC session, etc.) to simply having
a booth or even people representing CentOS at an event in some manner.

--

## Adding and modifying events

To add or modify conference and talk data, please see:
https://github.com/CentOS/CentOS-events/wiki/Adding-and-modifying-events

If you'd like to learn about the formatting of events, with plenty of
examples and explanation, read the document on formatting:
  https://github.com/CentOS/CentOS-events/wiki/Formatting

--

## Validation

To validate events, you must have Ruby and Bundler installed.


### Setting up Ruby and Bundler

On CentOS or Fedora, install both by running:

```sh
sudo yum install ruby rubygem-bundler
```

After dependencies are met, run:

```sh
bundle install
```

### Running the validation script

Once everything's set up, it's easy to validate events.

```sh
./validate.rb
```

The result will either inform you of success or list errors that need to
be fixed.
