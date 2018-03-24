require 'gist'

desc "Update shields metadata"
task :shields do
  contents = {
    timestamp: Time.now.utc,
    gist_id: ENV["GIST_ID"],
    rnd_int: rand(10e10)
  }

  user_name, repo_name = ENV["TRAVIS_REPO_SLUG"].split("/")

  Gist.gist contents.to_json,
            access_token: ENV["GIST_TOKEN"],
            update: ENV["GIST_ID"],
            filename: "#{repo_name}.json"
end
