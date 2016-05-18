guard :shell do
  watch(%r{^(.+)/lib/(.+)\.rb}) { |m| `ruby #{m[1]}/test/#{m[2]}_test.rb` }
  watch(%r{^(.+)/test/(.+)_test\.rb}) { |m| `ruby #{m[1]}/test/#{m[2]}_test.rb` }
end

# Add files and commands to this file, like the example:
#   watch(%r{file/path}) { `command(s)` }
#
guard :shell do
  watch(/(.*).txt/) {|m| `tail #{m[0]}` }
end
