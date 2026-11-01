# stlk0/homebrew-tap

Homebrew formulae by stlk0.

## rndis-tether

Use an Android phone's USB tethering on a Mac as an ordinary network connection.
See [stlk0/rndis-tether](https://github.com/stlk0/rndis-tether) for details.

```bash
brew install stlk0/tap/rndis-tether
```

```bash
sudo rndis-tether install
```

## rndis-tether-app

RNDIS Tether, a menu bar app for rndis-tether: it installs the service and shows whether the
phone is connected. See [stlk0/rndis-tether-app](https://github.com/stlk0/rndis-tether-app)
for details.

```bash
brew install stlk0/tap/rndis-tether stlk0/tap/rndis-tether-app
```

Then open RNDIS Tether (`open "$(brew --prefix)/opt/rndis-tether-app/RNDIS Tether.app"`) and
click **Install…** in its window.
