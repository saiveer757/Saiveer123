# Saiveer123
cd downloads/

git clone https://github.com/saiveer757/Saiveer123

sfdx auth:web:login --setalias saiveer-org --setdefaultdevhubusername

cci project init

cci service connect devhub --project

cci flow run dev_org --org dev

cci org browser dev

git add -A

git commit -m "Git Changes"

git checkout -b develop

git push origin develop

git checkout -b master
