git checkout -b feature-branch
echo "Feature work" > feature.txt
git add feature.txt
git commit -m "Added feature file"
git checkout main
git merge feature-branch
