guard 'minitest' do
  # watch /lib/ files
  watch(%r{^lib/(.+).rb$}) do |m|
    # "test/#{m[1]}_test.rb"  # Run corresponding test
    "test/test_helper.rb"   # Run all the tests
  end

# watch /test/ files
  watch(%r{^test/(.+).rb$}) do |m|
    # "test/#{m[1]}.rb"       # Run changed test
    "test/test_helper.rb"   # Run all the tests
  end
end
