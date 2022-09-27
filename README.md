# hm4
```bash
docker-compose
mkdir db_data
dir db_data/
chown -R pavel:pavel *
usermod -aG docker pavel
docker-compose -f compose.yml up -d
docker-compose -f compose.yml down
```