# General HoloFair Metaverse Template
This is a "Get Started Unity3D project" to create, configure, build and deploy HoloFair compatible metaverses.

Instructions and guides are available on our [gitbook](https://docs.holofair.app). The next step after creating a repo from this is to [configure the addressables](https://outreal-xr.gitbook.io/holofair-sdk-v4/development/initial-setup/setup-addressables).

## Requirements
- Unity3D 2021.3.1f1 (only)
- Windows and WebGL build support (iOS and Android are up to you)
- Complete knowledge of Addressables 1.19.18 (how to add, build, optimize and update addressables and create or manage/configure Addressables Groups)
- CDN of your choice (Bunny CDN, Cloudfare CDN, AWS CloudFront etc.)
- Make sure you have name for Layer 6, because that is the layer HoloFair uses as ground or Walkable layer, otherwise Players will be stuck inside geometry
- Make sure to use Tag 1 for anything that a user should be able to click on

## Important Notes
Feel free to change Addressables Profiles to any end point of your CDN. As long as it has [BuildTarget] in the URL (e.g https://cdn.holofair.app/addressables/[BuildTarget]).
At the same time, it is not reccomended to change any Player or Graphics settings as well as Packages and their versions. In Player Settings it is okay to change Company Name and Product Name and version if you wish so. In case if you want to suggest an alternative setup or an addition, please, post on a issue with your idea, which we will read and try our best to make it work with HoloFair. Otherwise, if any changes made to the settings, then we can't gurantee that Addressables will load correctly or look the same as on your machine.

If you wish to learn more about the SDK itself, feel free to clone this package on your machine: https://outreal-xr.gitbook.io/holofair-sdk-v4/
