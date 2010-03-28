begin
  require 'jeweler'
  Jeweler::Tasks.new do |gs|
    gs.name              = 'ubermajestix-gravtastic'
    gs.homepage          = 'http://github.com/ubermajestix/gravtastic'
    gs.description       = 'Add Gravatars to your Rubies/Rails!'
    gs.summary           = 'Ruby/Gravatar'
    gs.email             = 'tyler.a.montgomery@gmail.com'
    gs.author            = 'Tyler Montgomery'
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Install jeweler to build gem"
end

require 'spec/rake/spectask'
Spec::Rake::SpecTask.new('spec') do |t|
  t.spec_opts = ['--color']
  t.spec_files = FileList['spec/*.rb']
end
