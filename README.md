# Awesome Puppet

A curated list of amazingly awesome puppet resources inspired by @bayandin's [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

Your pull requests are very welcome! Let's make this the awesomest resource for Puppet!

- [Integrated Development Enviroments](#integrated-development-enviroments)
- [Documentation](#documentation)
- [Module Management](#module-management)
- [Build Tools](#build-tools)
- [Testing](#testing)
- [Puppet Tools](#puppet-tools)
- [Learning Resources](#learning)
- [Other Awesome Lists](#other-awesome-lists)

## Integrated Development Enviroments

> IDEs and Editors for development

- [Atom](https://github.com/atom/atom) - The hackable editor by GitHub
  - [Puppet plugin](https://github.com/atom/language-puppet) - The Puppet plugin for Atom
- [Sublime](http://www.sublimetext.com/) - Non-FOSS text editor for MacOS X
  - [SublimePuppet](https://github.com/russCloak/SublimePuppet) - Puppet syntax for Sublime
  - [SublimeLinter Puppet](https://github.com/stopdropandrew/SublimeLinter-puppet-lint) - Sublime Linter plugin for Puppet
- [Textmate](https://github.com/textmate/textmate) - FOSS text editor for MacOS X
  - [Puppet Bundle](https://github.com/cburyta/puppet-textmate.tmbundle) - Textmate bundle for Puppet
- [RubyMine](https://www.jetbrains.com/ruby/) - Code editor for Windows/Mac/Linux (not free or FOSS)
  - [Puppet language support plugin](https://plugins.jetbrains.com/plugin/7180-puppet-support) - also compatible with other editors
- [VSCode](https://code.visualstudio.com/download)
  - [Puppet plugin](https://marketplace.visualstudio.com/items?itemName=jpogran.puppet-vscode) - Puppet syntax, code snippets, PDK integration, etc.
- [Vim](https://www.vim.org/) - the ubiquitous text editor
  - [vim-puppet](https://github.com/voxpupuli/vim-puppet) - provides syntax highlighting and other plugins

## Documentation

> Libraries for generating project documentation

- [HereDoc](http://puppet-on-the-edge.blogspot.com/2014/03/heredoc-is-here.html) - HereDoc support for Puppet
- [puppet-strings](https://puppet.com/blog/using-puppet-strings-generate-great-documentation-puppet-modules) - Current generation documentation from Puppet
  - [puppetlabs/ntp](https://github.com/puppetlabs/puppetlabs-ntp) - reference module for Strings support

## Module Management

> Libraries for module management

- [Librarian Puppet](http://librarian-puppet.com/) - Flexible module management for your puppet repository
- [Puppet Blacksmith](https://github.com/voxpupuli/puppet-blacksmith) - Ruby Gem with several Puppet Module utilities used for easily publishing modules to the forge
- [Hiera-Regex](https://github.com/jjulien/hiera-regex/) - Regex backend for Hiera data.
- [Modulesync](https://github.com/voxpupuli/modulesync) - Synchronize consistent settings across modules in a user or organization namespace (not PDK compatible).
  - [modulesync_config reference](https://github.com/rnelson0/puppet-modulesync_config_reference) - Reference modulesync configuration repo.
- [pdksync](https://github.com/puppetlabs/pdksync) - Use PDK to synchronize multiple module repositories.


## Build Tools

> Libraries for building and task running

- [Puppet Lint](https://github.com/rodjek/puppet-lint) Check that your Puppet manifest conform to the style guide
- [puppet-lint-action](https://github.com/marketplace/actions/puppet-lint-action) GitHub Action for interacting with Puppet Lint

## Testing

> Testing frameworks

- [Rspec Puppet](https://github.com/rodjek/rspec-puppet) RSpec tests for your Puppet Manifests
  - [rspec-puppet.com](http://rspec-puppet.com) - Official docs
- [Beaker](https://github.com/puppetlabs/beaker) Puppet acceptance testing harness
- [Kitchen](https://kitchen.ci/)
- [Kitchen Puppet](https://github.com/neillturner/kitchen-puppet)
- [Using kitchen with puppet](http://ehaselwanter.com/en/blog/2014/05/08/using-test-kitchen-with-puppet/)
- [Onceover](https://github.com/dylanratcliffe/onceover) Repository testing

## Puppet Tools

- [Puppet Bolt](https://github.com/puppetlabs/bolt)  A Ruby command-line tool for executing commands, scripts, and tasks on remote systems using SSH and WinRM. Great for 'ad hoc' task execution. Bolt tasks can be written in any scripting/programming language (Also known as puppet tasks).
- [Puppet Development Kit](https://puppet.com/docs/pdk/1.x/pdk.html) A toolkit for puppet module developers
- [puppet-retrospec](https://github.com/nwops/puppet-retrospec) - Generates puppet rspec test code based on the current code inside your module.
- [puppet-ghostbuster](https://github.com/camptocamp/puppet-ghostbuster) - Finds dead code by displaying unused classes, defined resources, template and files. Requires puppetdb 3+.
- [puppet-debugger](https://github.com/nwops/puppet-debugger) - A interactive live debugger and REPL for the puppet language
- [puppet-function-updater](https://github.com/binford2k/puppet-function-updater) - A tool that helps port legacy Puppet functions to the modern Ruby API.

## Control Repositories

> Reference implementations

- [puppetlabs/control-repo](https://github.com/puppetlabs/control-repo) - Official reference architecture from Puppet, based on [Even Besterer Practices](http://garylarizza.com/blog/2015/11/16/workflows-evolved-even-besterer-practices/).
- [PSICK](https://github.com/example42/psick) A reusable Puppet control repository using many of what are considered best practices.
- [puppetlabs-education/classroom-control-vf](https://github.com/puppetlabs-education/classroom-control-vf) - A good reference implementation of the control repository, maintained by Puppet's Education group.
- [puppetinabox/controlrepo](https://github.com/puppetinabox/controlrepo) - Rob Nelson's control repository for his [PuppetInABox project](https://rnelson0.com/2015/01/08/introducing-puppetinabox-bootstrap-a-lab-setup-with-puppet/).

## Learning

> Resources for new puppet users

- [Puppet Learning VM](https://puppet.com/download-learning-vm) A simple VM that gives you a set of challenges to learn puppet by doing.
- [Puppet Cookbook](http://www.puppetcookbook.com/), a collection of task oriented solutions in Puppet.
- [YAML for Puppet users?](http://ask.puppetlabs.com/question/19711/yaml-for-puppet-users/) - A combination YAML primer and Guide to Puppet/YAML idiosyncracies.

## References

> Active code references representing various design patterns and usage

- [puppetlabs/httpd](https://github.com/puppetlabs/puppetlabs-apache/blob/master/.travis.yml) - Beaker tests in Travis.
- [Resource API](https://github.com/puppetlabs/puppet-resource_api) - Examples of Types & Providers.
- [puppetlabs/java's java_version](https://github.com/puppetlabs/puppetlabs-java/blob/master/spec/unit/facter/java_version_spec.rb) - Writing a custom fact in ruby.
- [puppetinabox puppet_role fact](https://github.com/puppetinabox/controlrepo/blob/539b2adb474f9028c59565b40fe340a9a59f57e0/dist/profile/lib/facter/puppet_role.rb) and [test](https://github.com/puppetinabox/controlrepo/blob/539b2adb474f9028c59565b40fe340a9a59f57e0/dist/profile/spec/unit/facter/puppet_role_spec.rb) - Testing of a custom fact.
- [puppetlabs/apache's defined type apache::vhost](https://github.com/puppetlabs/puppetlabs-apache/blob/5d2e65ed3df9d39fb7d99b5948584035f8b662c3/spec/defines/vhost_spec.rb#L4-L6) - Include a dependency (`apache`) during unit testing of another resource (`apache::vhost`).
- [puppetlabs/apache](https://github.com/puppetlabs/puppetlabs-apache/blob/5d2e65ed3df9d39fb7d99b5948584035f8b662c3/spec/classes/apache_spec.rb#L152-L184) - Testing an ERB template's resulting content


## Other Awesome Lists

Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome!
