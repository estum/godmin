source "https://rubygems.org"

# Declare your gem's dependencies in godmin.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# The dummy app loads whatever is specified in this gemfile, therefore
# we add the admin engine used by the dummy app here
gem "admin", path: "test/dummy/admin", group: [:test, :development]
