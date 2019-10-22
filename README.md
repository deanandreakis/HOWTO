# HOWTO
Various notes, tips and tricks

## VIM on Linux

1. To enable system-wide copy/paste install the vim-gtk package

## Ruby development on Linux

1. Use the command 'gem uninstall -aIx' to remove all installed ruby gems that do not come as default with ruby itself.
2. Use rbenv to control your ruby development environment.

### To bootstrsap your Ruby development environment on Linux:

1. Install rbenv (https://github.com/rbenv/rbenv)
2. Install ruby-build (https://github.com/rbenv/ruby-build)
3. Use the 'rbenv install <version>' to install a ruby version
4. Use 'rbenv global <version>' to use the installed ruby version globally
5. Use 'gem install bundler' to upgrade bundler to the latest version. See (https://bundler.io/)

At this point you can create project directories and then use bundler to control the exact gems needed for your project. For example, if it is a Rails project then in your project directory you can specify a Gemfile that includes 'gem rails' and then issue 'bundle install'.

Another thing to note is that you can use rbenv to also specify the version of ruby to use in a project directory instead of using whatever version is defined globally.
