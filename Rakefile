# -*- ruby -*-

require 'rubygems'
require 'hoe'

Hoe.plugins.delete :rubyforge
Hoe.plugin :minitest
Hoe.plugin :gemspec # `gem install hoe-gemspec`
Hoe.plugin :git     # `gem install hoe-git`

Hoe.spec 'particular' do
  developer('Aaron Patterson', 'tenderlove@ruby-lang.org')
  self.readme_file   = 'README.md'
  self.history_file  = 'CHANGELOG.md'
  self.extra_rdoc_files  = FileList['*.md']
end

# vim: syntax=ruby
