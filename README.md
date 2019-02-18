# SquirrelDeployDemo_Start
Desktop deployment example


Search for squirrel.windows in Nuget Package Manager

install nuget manager from windows store
- edit metadata info
- create 'lib' folder
- inside lib' create 'net45'
- add files of release folder except the .pdb (they are for debugging)
-save

In package Manager Console
- PM> Squirrel --releasify SQLiteDemo.1.0.0.nupkg

Put it in updater folder
