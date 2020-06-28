# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

* to run this app making develpment environment

- references 

https://qiita.com/snoguchi/items/d12f0407075d7978925c
https://dev.classmethod.jp/articles/ruby-on-rails-carrierwave-ffmpeg/


sudo yum -y install epel-release

sudo rpm --import http://li.nux.ro/download/nux/RPM-GPG-KEY-nux.ro

sudo rpm -Uvh http://li.nux.ro/download/nux/dextop/el7/x86_64/nux-dextop-release-0-1.el7.nux.noarch.rpm

sudo yum -y install ffmpeg ffmpeg-devel

- to check ffmpeg installed
ffmpeg -h

- add to gemfile
gem 'carrierwave'
gem 'streamio-ffmpeg'
