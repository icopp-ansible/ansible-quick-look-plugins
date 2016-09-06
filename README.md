# ansible-quick-look-plugins

Install a set of Quick Look plugins for assorted file types.

This adds support for:

* AppleScript files (via [ScriptQL](https://www.kainjow.com))
* BPG image files (via [qlImageSize](https://github.com/Nyx0uf/qlImageSize))
* CSV files (via [QuickLook CSV](https://github.com/p2/quicklook-csv))
* DDS texture files (via [QLdds](https://github.com/Marginal/QLdds))
* ePub files (via [ePub-quicklook](https://github.com/jaketmp/ePub-quicklook))
* Gradle build files (via [QLGradle](https://github.com/Urucas/QLGradle))
* iOS packaged application files and application bundles (via [ProvisionQL](https://github.com/ealeksandrov/ProvisionQL))
* iOS and macOS application extensions (via [ProvisionQL](https://github.com/ealeksandrov/ProvisionQL))
* iOS and macOS provisioning profiles (via [ProvisionQL](https://github.com/ealeksandrov/ProvisionQL))
* JSON files (via [quick look JSON](http://www.sagtau.com/quicklookjson.html))
* MagicaVoxel files (via [VoxQL](https://github.com/heptal/VoxQL))
* Markdown files (via [QLMarkdown](https://github.com/toland/qlmarkdown))
* non-native audio and video (via [QuickLook Video](https://github.com/Marginal/QLVideo))
* patch files (via [QLPrettyPatch](https://github.com/atnan/QLPrettyPatch))
* Photoshop brush files (via [BrushViewQL](http://brushviewer.sourceforge.net))
* plain text files without extensions (via [QLStephen](https://whomwah.github.io/qlstephen))
* PPM image files (via [qlImageSize](https://github.com/Nyx0uf/qlImageSize))
* ReStructuredText files (via [QLRest](https://github.com/cluther/qlrest
)) (note that `docutils` and `pygments` Python packages must be installed to render)
* source code files, with syntax highlighting (via [QLColorCode](https://github.com/anthonygelibert/QLColorCode))
* Swift code files (via [qlplayground](https://github.com/norio-nomura/qlplayground))
* WebP files (via [WebP Quicklook](https://github.com/dchest/webp-quicklook))
* Xcode playground files (via [qlplayground](https://github.com/norio-nomura/qlplayground))
* zip files, with contents display (via [BetterZip QuickLook](https://macitbetter.com/BetterZip-Quick-Look-Generator/))

## Dependencies

* [icopp.homebrew-cask](https://github.com/icopp/ansible-homebrew-cask)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.quick-look-plugins
```

## License

MIT
