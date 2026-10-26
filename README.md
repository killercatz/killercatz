- 👋 Hi, I’m @killercatz
- 👀 I’m interested in coding
- 🌱 I’m currently learning java, python and C+
- 💞️ I’m not looking to collaborate on
mkdir -p storage/logs storage/state storage/uploads storage/results storage/databases
sudo chown -R 57439:57439 storage

docker compose run --rm \
  -v "$PWD/workflow/scripts/install_databases.sh:/app/workflow/scripts/install_databases.sh:ro" \
  --entrypoint /app/workflow/scripts/install_databases.sh \
  database-init \
  amrfinderplus busco-bacteria mobsuite plasmidfinder vfdb bakta-light
<!---
killercatz/killercatz is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
