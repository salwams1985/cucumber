If you're using bundler, add the `rspec-expectations` gem to your Gemfile. Cucumber will automatically load RSpec's matchers and expectation methods to be available in your step definitions.

e.g.

    Given /^a nice new bike$/ do
      expect(bike).to be_shiny
    end