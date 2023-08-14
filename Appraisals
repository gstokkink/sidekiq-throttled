# frozen_string_literal: true

customize_gemfiles do
  {
    single_quotes: true,
    heading: <<~HEADING
      frozen_string_literal: true

      This file was generated by Appraisal
    HEADING
  }
end

appraise "sidekiq-6.5.x" do
  group :test do
    gem "sidekiq", "~> 6.5.0"
  end
end

appraise "sidekiq-7.0.x" do
  group :test do
    gem "sidekiq", "~> 7.0.0"
  end
end

appraise "sidekiq-7.1.x" do
  group :test do
    gem "sidekiq", "~> 7.1.0"
  end
end

appraise "sidekiq-pro-5.5.x" do
  group :test do
    gem "sidekiq", "~> 6.5.0"
    gem "sidekiq-pro", "~> 5.5.0"
  end
end

appraise "sidekiq-pro-7.0.x" do
  group :test do
    gem "sidekiq", "~> 7.0.0"
    gem "sidekiq-pro", "~> 7.0.0"
  end
end

appraise "sidekiq-pro-7.1.x" do
  group :test do
    gem "sidekiq", "~> 7.1.0"
    gem "sidekiq-pro", "~> 7.1.0"
  end
end
