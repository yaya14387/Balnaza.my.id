# Clone repository
git clone https://github.com/yaya14387/Balnaza.my.id.git
cd Balnaza.my.id

# Tambahkan file
touch .nojekyll
echo "balnaza.my.id" > CNAME

# Commit dan push
git add index.html CNAME .nojekyll
git commit -m "Initial setup with custom domain"
git push origin main
