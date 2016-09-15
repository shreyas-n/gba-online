# Online GBA

## What is it

Online GBA is a simply way to play any GBA games in the browser

## Installation

It is a static app meaning you can simply fork the repo with

```
https://github.com/shreyas-n/gba-online.git
```

or download the [zip](https://github.com/shreyas-n/gba-online/archive/master.zip)

#### Deploy with heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

#### Index.php?

The `index.php` file is there to fool [heroku](https://www.heroku.com/) into thinking your app is
a dynamic app. Heroku doesn't allow static html to be hosted so we need something to get free hosting
with heroku

## Binaries

This is built on [IodineGBA](https://github.com/taisel/IodineGBA) and all ROMs should be dropped 
into the `Binaries` folder with a `.gba` extension

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

### Demo

This is being hosted on heroku. [Demo](http://gblive.herokuapp.com/)