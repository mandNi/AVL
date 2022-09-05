# AVL

AVL Tree migration from Roassal 3

## How to install it

To install `AVL`, go to the Playground (Ctrl+OW) in your [Pharo](https://pharo.org/) image and execute the following Metacello script (select it and press Do-it button or Ctrl+D):

```st
Metacello new
  baseline: 'AVLTree';
  repository: 'github://pharo-containers/AVL:main';
  load
```

## How to depend on it

If you want to add a dependency on `linear-models` to your project, include the following lines into your baseline method:

```st
spec
  baseline: 'AVL'
  with: [ spec repository: 'github://pharo-containers/AVL' ].
```

