# vishalsharma_12223245
cd vishalsharma_12223245
pwd
git init
echo "Initial Content" > vishalsharma
git commit -m "Initial commit in Master branch"
git checkout -b Details
git add vishalsharma
git commit -m "Add new content in Details branch"
git checkout master
echo "Changes in Master branch" >> vishalsharma
git add vishalsharma
git commit -m "Update in Master branch"
git checkout Details
echo "Additional content for Details branch" >> vishalsharma
git add vishalsharma
git commit -m "More updates in Details branch"
git checkout Details
git merge master
git add vishalsharma
git commit -m "Resolve merge conflict"


