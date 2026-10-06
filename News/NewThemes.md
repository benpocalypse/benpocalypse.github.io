# 10/05/2026

## New CSS Themes
I've added 3 new example CSS themes to the  Markerator repo. One of them is a dark variant of the current default theme, another is a Blue theme in both light and dark variants.

These will be detailed in their usage in the upcoming detailed documentation and examples update. The documentation will detail all of the CSS elements that can be themed, and will walk through the current details hopefully.

UPDATE: I had to update the dotnet.yml file to manually add the /css/ folder upon output.

UPDATE 2: It turns out git wasn't adding untracked subfolders and files. I've once again updated the yaml file to include these untracked folders/files.

UPDATE 3: I think the problem was in the search paths that Markerator was looking for on input. I've broadened this and hopefully this will be the final fix for specifying themes on the CLI.

UPDATE 4: It turns out that the `-c` option was being interpretted by MSBuild, and not by Markerator, so I updated the yaml file to pass the parameter to Markerator correctly.