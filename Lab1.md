# Lab 1 : GitHub

## Create a Repository
1 以下にアクセスし"New"を押下する  
https://github.com/dashboard  
2 以下を入力する  
- Repository name : unicorn-web-project  
- "Private"を選択  

3 "Create repository"を押下する  
4 Repository URLをコピーする  
```
https://github.com/<アカウント名>/unicorn-web-project.git
```
5 Access Token取得  
以下にアクセス  
https://github.com/settings/apps  
Personal access tolens → Tokens → Generate new token (classic) 

6 以下を入力する  
Note : cicd-workshop  
Expiration : 7days  
Select scopes : repo

7 "Generate token"を押下

8 personal access tokenをコピーする

9 トークンの保存設定
```
# git config --global credential.helper cache
```

参考:
https://dev.classmethod.jp/articles/github-personal-access-tokens/