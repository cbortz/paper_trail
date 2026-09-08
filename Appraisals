# frozen_string_literal: true

# Specify here only version constraints that differ from
# `paper_trail.gemspec`.
#
# > The dependencies in your Appraisals file are combined with dependencies in
# > your Gemfile, so you don't need to repeat anything that's the same for each
# > appraisal. If something is specified in both the Gemfile and an appraisal,
# > the version from the appraisal takes precedence.
# > https://github.com/thoughtbot/appraisal
#
# The json pins: Active Support <= 8.0 passes `quirks_mode:` to
# `JSON.generate`, and every version through 8.1 passes a positional options
# hash to `JSON.parse`. The json gem dropped both in 3.0. Drop each pin if/when
# support for json >= 3 is added.

appraise "rails-7.1" do
  gem "rails", "~> 7.1.0"
  gem "json", "< 3"
end

appraise "rails-7.2" do
  gem "rails", "~> 7.2.0"
  gem "json", "< 3"
end

appraise "rails-8.0" do
  gem "rails", "~> 8.0.0"
  gem "sqlite3", ">= 2.1"
  gem "json", "< 3"
end

appraise "rails-8.1" do
  gem "rails", "~> 8.1.0"
  gem "sqlite3", ">= 2.1"
  gem "json", "< 3"
end
