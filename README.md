- open **PowerShell** as Adminstrator the type `wsl --install -d debian`
    - message prompts: Installing: Debian GNU/Linux ... The operation complete successfully
- new terminal will open for **Debian**
    - message prompts: 
        - Enter new UNIX username:
        - New password:
        - Retype new password:
    - passwd: password updated successfully, Installation successful (once the details are correct and complete)
- create an repository at **GitHub**
    - type via gitbash:
        - `git add .`
        - `git commit -m "some-message"` / `git commit -m "first commit debian ftp"`
        - `git branch -M main`
        - `git remote add origin git@github.com:<username>/<name_repository>.git`
        - `git push -u origin main`
