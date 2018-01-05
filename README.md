# hs-emoji

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

## emoji data
This library gets emoji list file from [here](https://github.com/omnidan/node-emoji)
