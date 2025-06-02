# Clone repository
git clone https://github.com/yaya14387/balnaza.my.id.git
cd balnaza.my.id

# Tambahkan file
touch .nojekyll
echo "balnaza.my.id" > CNAME

# Commit dan push
git add index.html CNAME .nojekyll
git commit -m "Initial setup with custom domain"
git push origin main
