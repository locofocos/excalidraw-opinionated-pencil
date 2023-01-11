
# Excalidraw opinionated pencil

It's [Excalidraw](https://excalidraw.com), but the pencil tool matches the size of other tools.

![comparison image](comparison.jpg)

Deployed at http://locofocos.com/excalidraw-opinionated-pencil/ or https://locofocos.github.io/excalidraw-opinionated-pencil/ if I forget to renew my domain.

Some folks are trying to solve this problem over at https://github.com/excalidraw/excalidraw/issues/3693 but nobody can make progress. I just want something I can use for drawing.

## Deployment instructions

```
rm -rf docs

yarn build

mv build/ docs/
```
then commit and push
