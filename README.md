# Set_Github_Ubuntu
Установить git
```
sudo apt install git
```
Установить GitHub CLI
```
sudo apt install gh
```
Авторизация GitHub CLI
```
gh auth login
```
Обновить статус
```
gh auth status
```
Добавить права на добавление релизов
```
gh auth refresh -s repo
```
Клонирование существующего репозитория
```
git clone https://github.com/[user]/[repository].git
```
Переходим в папку репозитория
```
cd [repository]
```
```
? What account do you want to log into? GitHub.com
? What is your preferred protocol for Git operations on this host? HTTPS
? Authenticate Git with your GitHub credentials? Yes
? How would you like to authenticate GitHub CLI? Paste an authentication token
Tip: you can generate a Personal Access Token here https://github.com/settings/tokens
The minimum required scopes are 'repo', 'read:org', 'workflow'.
? Paste your authentication token: *********************************************************************************************
- gh config set -h github.com git_protocol https
✓ Configured git protocol
! Authentication credentials saved in plain text
✓ Logged in as stimandrew
```
