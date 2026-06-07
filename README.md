# MegaMek

___TableTop BattleTech on your computer___

MegaMek is a Java version of BattleTech that you can play with your friends over the internet.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub org.megamek.MegaMek
flatpak run org.megamek.MegaMek
```

## Building

```bash
git clone git@github.com:flathub/org.megamek.MegaMek.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install org.megamek.MegaMek.yaml
```

### Note for maintainers

Please use the milestone version to comply with Flathub's stable build policy.
