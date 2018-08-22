source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "github-pages",
  github: 'UnderpantsGnome/pages-gem',
  branch: "paginate-v2",
  group: :jekyll_plugins
group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-paginate-v2"
  gem "jekyll-feed"
  gem "jemoji"
end
