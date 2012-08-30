source :rubygems
gemspec

# RDF Export
gem 'rdf', '~>0.3'

group :debug do
	gem 'debugger', :platforms => [:mri_19]
end

group :test do
	gem 'minitest'
  gem 'cucumber', ['~>1.0']
end

group :extra do
	gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/i
	gem 'minitest-colorize'
	gem 'guard-minitest'
	gem 'guard-cucumber'
end

group :profile do
	gem 'ruby-prof', ['~>0.10'], :platforms => [:mri_19, :mri_19]
	gem 'gnuplot', ['~>2.4']
	gem 'simplecov'
end

group :development do
  gem 'rake'
  gem 'racc'
end
