### fluentd by ruby gem and MongDB

#install
gem install bundle
bundle install

#path conf file
./fluentd/fluentd.conf

#config
#apache access_log to mongoDB

#exec
bundle exec fluentd -c ./fluentd/fluentd.conf



