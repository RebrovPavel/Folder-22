# Folder-22

* Git init:
    ```
    npm init -y
    git init
    ```
    
* Git clone, remote remove:
    ```
    git clone git@github.com:[ User ]/[ Repository ]
    git remote rm [ remote ]
    ```
    
* Npm install, eslint commands:
    ```
    npm install [ ... ] --save-dev
    npx eslint [ --init / file.js ]
    ```

* Git commit:
    ```
    git add [ ... ]
    git commit -m " ... "
    git remote add origin git@github.com:[ User ]/[ Repository ]
    git push -u origin master
    ```

* How to to 'fix' last local commit without changing commit message?
    ```
    git commit --amend --no-edit
    ```
