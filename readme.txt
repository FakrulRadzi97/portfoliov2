
-- cloning repository to our local
git clone https://github.com/FakrulRadzi97/portfoliov2.git

-- create new feature branch
git checkout -b feature/our-branch-name 
for example : git checkout -b feature/update-about-section

-- check we are at what branch
git branch

-- to add whatever file/image before commit
git add .

-- to commit (give a name)
git commit -m "Add resume PDF and profile image"

-- push feature to our github
git push origin feature/update-about-section

* after push , we need to go our repository in github website
1. click on compare and pull request
2. review and merge

-- to checkout main branch back
git checkout main

-- pull main branch code
git pull origin main

-- to create new feature after pull main branch
git checkout -b feature/our-branch-name

-- to check again which branch
git branch