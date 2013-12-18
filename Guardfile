require 'sprockets'

guard 'haml', :output => 'public' do
  watch(/^.+(\.html\.haml)$/)
end

guard 'compass' do
  watch(/^sass\/(.*)\.s[ac]ss$/)
end

guard 'sprockets', {
    :minify      => true,
    :destination => 'public/assets/js/',
    :asset_paths => 'javascripts'
  } do
  watch(/^javascripts\/(.*)\.(js)$/)
end
