# Jenkins Sample Repo
This is a test repo used for Jenkins Git integration

......Testing with webhook..

echo "# Trigger test" >> README.md
git add README.md
git commit -m "Test Jenkins trigger via GitHub push"
git push origin main

