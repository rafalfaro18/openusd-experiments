# openusd-experiments
Experiments with OpenUSD

## Get correct diffs for usd files
In your ~/.gitconfig file (C:\Users\XXXXX\.gitconfig)
```toml
[diff "usd"]
    textconv = usdcat
```

Before doing that make sure usdcat is available in your command line.
