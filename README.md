# AddressableAssetTool

Easy for Setup Asset Address & Build.

# Setup

## Add Package

install Addressables:

[Window] > [Package Manager] > [Addressables] > [1.7.5] > [Install]

[Download](https://github.com/kou-yeung/AddressableAssetTool/releases) and import AddressableAssetTool.unitypackage

## Setup

[AAS] > [Setup]

this step to

1.Create "AddressableAssetSettings"

2.Create "Remote" group for remote download

3.Set RemoteLoadPath to "BASE_URL/[BuildTarget]"

4.Create "AddressableAssetTool"

## How to use

1.Select "AddressableAssetTool"

2.Add "Build Rule"

・Drag&Drop a folder to "path"

・Set "assetType" : Include(include in app) Preload(Load from Remote)

・recursive : recursive file from folder

・extensions : set file extension to pack.(Separately ';') e.g. ＊.png;＊.prefab

3.Build!!

4.[Use it!!](https://gist.github.com/kou-yeung/cee45275121f4b515510de486ea1c67a)

# System requirements

Unity 2019.3.6f1

Addressables Version.1.7.5
