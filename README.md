# hs-emoji

[![Hackage](https://img.shields.io/hackage/v/emoji.svg)](https://hackage.haskell.org/package/emoji)

## example
```
import Data.Emoji

main = do
  print (unicodeByName "sushi")
  mapM_ putStrLn (unicodeByName "pizza")

```
output
```
Just "\127843"
🍕
```

## build

```
./download.sh
stack build
```

## emoji data
This library gets emoji list file from [here](https://github.com/omnidan/node-emoji)
