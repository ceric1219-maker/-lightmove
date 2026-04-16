# 다운로드한 lightmove-src.zip 압축 해제
unzip lightmove-src.zip

# 폴더로 이동
cd lightmove

# Git 초기화
git init
git add .
git commit -m "Initial commit: Light Move app"

# GitHub 저장소와 연결 (YOUR_USERNAME과 YOUR_TOKEN 입력)
git remote add origin https://github.com/YOUR_USERNAME/lightmove.git
git branch -M main
git push -u origin main
