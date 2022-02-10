# SailwindModRepository
Central repository for Sailwind mods.


For the Sailwind Mod Manager, please see the following repository:
> https://github.com/MaxWasUnavailable/SailwindModManager


## How to add your mod

Please open a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) to add your mod. You'll want to add it as a new subdirectory in the mods directory, using a unique name.

Please keep in mind to properly fill out your info.json file, since the Mod Manager uses it extensively.

### info.json fields used by the mod manager
> Keep in mind there are other, required fields used by the Unity Mod Manager / Loader. If you do not have these, your mod will not work.

The following keys can be used by the mod manager - most of them are optional, however:

* Id
* DisplayName
* Author
* Version
* ManagerVersion
* GameVersion
* Requirements
* HomePage
* Repository
* Tags
> Tags is recommended since they will show up in the mod browser. I'd recommend at most 2 - 3 tags to keep things readable.
* Incompatible
* ModloaderRequired
* Description
> The description is parsed as HTML, so you can get pretty creative with that one.

You can see the [example mod entry info.json](https://github.com/MaxWasUnavailable/SailwindModRepository/blob/master/mods/example_mod_entry/info.json) as an example.
