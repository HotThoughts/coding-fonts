## How to patch a font to Nerd Font

```bash
docker run -v $PWD/<the path to font directory>:/in -v $PWD/<the path to the nerd font directory>:/out  nerdfonts/patcher -c
```

