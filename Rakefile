require 'json'

namespace :maintenance do
  task :on do
    json = { maintenance: true }.to_json
    File.write('./public/index.json', json)
  end

  task :off do
    json = { maintenance: false }.to_json
    File.write('./public/index.json', json)
  end
end
