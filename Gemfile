source "https://rubygems.org"

ruby '3.4.1'

# This workaround has already implemented in Bundler 2.0 branch.
# So we can remove this lines after we upgrade Bundler to 2.0.
# ref: https://github.com/bundler/bundler/pull/4109#issuecomment-183765510
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'fiddle'
gem 'logger'
gem 'reline'
gem 'ostruct'
gem 'csv'
gem 'faraday-retry'
gem 'qiita'
gem "rake", "< 14.0.0"
gem "ruboty-bundler"
gem "ruboty-echo"
gem "ruboty-redis", github: "Umekawa/ruboty-redis", branch: 'master'
gem "ruboty-scorekeeper"
gem "ruboty-slack_events"
gem "ruboty-response", github: 'increments/ruboty-response'
gem "ruboty-ruby", ">= 0.0.2"
gem "ruboty-alias", "= 0.0.8"
gem "ruboty-cron", "~> 1.1.0"
gem "ruboty-qiita-github"
gem "ruboty-ruby_persistence", "= 0.2.0"
gem "ruboty-openai_chat", "~> 0.3"
gem "increments-schedule", "~> 0.18.0"
