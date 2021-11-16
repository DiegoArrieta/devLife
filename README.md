# devLife
Some ideas and fixes for bugs i have come across as a developer

https://stackoverflow.com/questions/31691626/cant-brew-install-node/34906259

## dyld: Library not loaded: @executable_path/../.Python
```
$brew uninstall --ignore-dependencies python3
$brew cleanup
$brew install python3
```

## remove bottom border in React Navigation Header (v6)
Navigator
```
screenOptions: {{
  headerShadowVisible: false
}}
```

Screen
```
options: {{
  headerShadowVisible: false
}}
```
