# hm4
docker-compose
mkdir db_data
dir db_data/
usermod -aG docker pavel
docker-compose -f compose.yml up -d
docker-compose -f compose.yml down