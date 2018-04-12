- This project is getting inspired from this repo: https://github.com/mattbrictson/rails-template
- It was configured as an API Rails app with Mongoid + Sidekiq + Capistrano
- How to use:
```
$ rails new <app_name> --api \ 
                        -C \ # Skip Action Cable files
                        -T \ # Skip test files
                        -P \ # Skip Puma related files
                        -O \ # Skip Active Record files
                        -m https://raw.githubusercontent.com/kis25791/rails_api_template/master/template.rb
```
