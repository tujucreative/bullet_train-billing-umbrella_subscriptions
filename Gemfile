source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Specify your gem's dependencies in bullet_train-billing-umbrella_subscriptions.gemspec.
gemspec

git "https://github.com/tujucreative/bullet_train-core.git", branch: "main" do
  gem "bullet_train"
  gem "bullet_train-api"
end

gem "bullet_train-billing", github: "tujucreative/bullet_train-billing", branch: "main"
gem "bullet_train-billing-usage", github: "tujucreative/bullet_train-billing-usage", branch: "main"

gem "sqlite3"

gem "sprockets-rails"

# Start debugger with binding.b [https://github.com/ruby/debug]
# gem "debug", ">= 1.0.0"

# Not a direct dependency of this repo; the starter provides it.
gem "minitest-mock"

gem "standardrb", "~> 1.0"
