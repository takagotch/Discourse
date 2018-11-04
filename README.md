### Discourse
---
https://github.com/discourse/discourse

```
sudo service postgresql start
redis-server --daemonize yes

cd ~

sudo service postgresql start
redis-server --daemonize yes

chmod +x start-descourse
sudo cp start-discourse /usr/bin/


sudo service postgresql start
redis-server --daemonize yes
bundle exec sidekiq -d -C ./config/sidekiq.yml

```

```
```

```
```
