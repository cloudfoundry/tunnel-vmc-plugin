source "http://rubygems.org"

#############
# WARNING: Separate from the Gemspec. Please update both files
#############

gem "cfoundry", :git => "git://github.com/cloudfoundry/vmc-lib.git"
gem "vmc", :git => "git://github.com/cloudfoundry/vmc.git"
gem "tunnel-vmc-plugin", :path => "."

group :development, :test do
  gem "rake"
end

group :development do
  gem "gem-release"
end

group :test do
  gem "rspec", "~> 2.11"
  gem "webmock", "~> 1.9"
  gem "rr", "~> 1.0"
end
