Development site for LibraryVPN.org

To build:
```
git clone https://github.com/LibraryVPN/libraryvpn.org-devel.git

cd libraryvpn.org-devel

git submodule init

git submodule update

```
Setup actions that only need done once:
```
mkdir public

cd public

git init

git remote add origin git@github.com:LibraryVPN/libraryvpn.github.io.git
```
To Deploy:
`./deploy.sh`
