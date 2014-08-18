guard 'sass', :output => 'public/css' do
  watch(%r{public/sass/(.+\.scss)$})
end

guard 'livereload', :grace_period => 0.5 do
  watch(%r{^app\.rb})
  watch(%r{views/.+\.(erb|haml|slim)$})
  watch(%r{public/.+\.(css|js|html)})
end