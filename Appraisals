appraise "rails23" do
  gem "rails", "~> 2.3.14"
end

appraise "rails30" do
  gem "rails", "~> 3.0.17"
end

appraise "rails31" do
  gem "rails", "~> 3.1.8"
end

appraise "rails32" do
  gem "rails", "~> 3.2.8"
end

appraise "rails40" do
  gem 'rails', :github => 'rails/rails'
  gem 'journey', :github => 'rails/journey'
  gem 'activerecord-deprecated_finders', :require => nil,
      :github => 'rails/activerecord-deprecated_finders'
  # TODO Rails 4.0 (once again) forces us to use ActiveRecord :
  # Java::OrgJrubyRack::RackInitializationException:
  # No such file or directory - [...]/jruby-rack/src/spec/stub/rails40/WEB-INF/config/database.yml
  # NOTE: AR-JDBC stable (nor master) ain't 4.0 ready yet, thus :
  gem 'activerecord-jdbc-adapter', :github => 'kares/activerecord-jdbc-adapter'
  gem 'activerecord-jdbcsqlite3-adapter'
end
