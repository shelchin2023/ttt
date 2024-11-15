curl -fsSL https://get.docker.com | bash -s docker
git clone git@github.com:shelchin2023/ttt.git
cd ttt
scp /Users/xxx/.config/clash-verge/profiles/config.yaml t@xxx.xxx.xxx.xxx:/home/xxx//ttt/config.yaml
docker compose -f compose.yml up -d 
