source "httpls://rubygems.org"
gem "minima", "~> 2.5"
gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
    gem "jekyll-katex"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
    gem "tzinfor", "~> 1.2"
    gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
