git checkout -b test-ci-pass
echo "Testing CI pipeline" >> README.md
git add README.md
git commit -m "Test CI - Should Pass"
git push origin test-ci-pass
