source "https://rubygems.org"

# Specify your gem's dependencies in vagrant-orchestrate.gemspec
gemspec

group :development do
  gem "vagrant", git: "https://github.com/mitchellh/vagrant.git", ref: "v1.7.2"
  gem "vagrant-spec", git: "https://github.com/mitchellh/vagrant-spec.git"
end

group :plugins do
  gem "vagrant-orchestrate", path: "."
  gem "vagrant-managed-servers"
  gem "vagrant-librarian-puppet"
  gem "vagrant-winrm-s"
end
