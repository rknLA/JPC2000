# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'haml', output: 'app', input: 'haml' do
  watch %r{^haml/.+(\.html\.haml)}
end

guard 'coffeescript', input: 'coffeescripts', output: 'app'


guard 'compass', output: 'app', input: 'scss', configuration_file: 'compass_config.rb' do
  watch %r{^scss/.+\.s[ac]ss}
end
