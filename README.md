# zibiga


```
firebase login
```

On MAC, first install
`brew install wget`

< Make changes >
then:
```
rm -rf public/NewGamePortal
mkdir public/NewGamePortal
wget -O temp.zip "https://github.com/yoav-zibin/NewGamePortal/archive/gh-pages.zip"
unzip temp.zip
cp -R NewGamePortal-gh-pages/* public/NewGamePortal/
rm -rf NewGamePortal-gh-pages/
rm temp.zip
firebase deploy
```
