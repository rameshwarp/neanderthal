16.08.2017  

sudo apt-get not update 
Error in `appstreamcli': double free or corruption (fasttop): 0x00000000024695b0 ***

```sh
sudo apt-get purge libappstream3
``

Error sudo apt-get not update 


```sh
python3 -V
python3 apt-remove-duplicate-source-entries.py 
sudo python3 apt-remove-duplicate-source-entries.py
```

Installing as an rbenv plugin (recommended)

https://gorails.com/setup/ubuntu/16.04
https://github.com/rbenv/ruby-build

```sh
rbenv install 2.3.4
rbenv global 2.3.4
ruby --version
```
Setting Up PostgreSQL

```sh
sudo sh -c "echo 'deb http://apt.postgresql.org/pub/repos/apt/ xenial-pgdg main' > /etc/apt/sources.list.d/pgdg.list"
wget --quiet -O - http://apt.postgresql.org/pub/repos/apt/ACCC4CF8.asc | sudo apt-key add -
sudo apt-get update
sudo apt-get install postgresql-common
sudo apt-get install postgresql-9.5 libpq-dev
```

Installing Rails

```sh
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
gem --version
gem install rails -v 5.1.1
```


