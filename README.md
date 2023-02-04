# Wiki Setup
## Tools
### Obsidian
This wiki was created with the tool [Obsidian](https://obsidian.md/). While not necessary, it is very useful in navigation and creation of new notes. To download it directly, [click here](https://github.com/obsidianmd/obsidian-releases/releases/download/v1.0.3/Obsidian.1.0.3.exe) and install once download is complete. There are aspects of this wiki that do use Obsidian plugins, but they are not heavily used and are convenient. 

### Git
This vault is stored in a git repository, so [Git](https://git-scm.com/) is necessary. To download it directly, [click here](https://git-scm.com/download/win) and install once the download is complete

## Configuration
1) Navigate to [Silicon Bayou Repository](https://dev.azure.com/BeyondPlatform/Silicon%20Bayou/_git/Silicon%20Bayou) and clone the repository
2) Open Obsidian and _Open folder as Vault_, navigating to the folder where you placed the repository. You now have access to the base wiki. Further steps add additional functionality with add-ons. 
3) Open Settings (gear in the bottom left)
	1) Select "Core Plugins". Enable the option for "Slash Commands". This allows you to press "\\" and start typing commands, increasing efficiency. 
	2) Select "Files & Links" and deselect "Wikilinks". This changes the formatting of links from [[Homepage]] to [Homepage](Homepage.md), thus allowing links to work outside of Obisidian. 

### Recommended Plugins
It is recommended that you enable plug-ins for your vault so that you get additional functionality. This can be done by clicking the gear in the bottom left of the application. Under "Community Plugins", there is an option called "Restricted Mode". Turn this option off. 

To add the recommended plugins, Open Settings (gear in the bottom left), select "Browse" next to "Community Plugins" and install the following plugins. There is a brief description/example of each plugin after the name. 
- **Admonition**: Allows for side-notes. Without it, these side-notes will look like code blocks
```ad-note
title: Side-Note
collapse: closed
This is an example of a side-note. By changing the collapse attribute between open and closed, we can display different information. 
```
- **Advanced Tables**: Assists in making tables, as tables can be time-consuming in Markdown. 

| Column 1 | Column 2 |
| -------- | -------- |
| PK 1     | Value 1  |

- **Tasks**: Formats "- [ ]" as a check box for tasks that need to be completed
- [ ] This is an example
- **Templater**: Allows for JavaScript in templates to make them more dynamic
- **Obsidian Git**: Use git without leaving Obsidian
- **Execute Code**: This allows code to be executed in Obsidian for examples and quick utility
```run-python
print('Hello World!')
```

Note: **None of these plugins are necessary, but they are _very_ helpful.**

# Organization
_"Organization is often undervalued but rarely unjustified"_ - Unknown

Inside of this wiki, there are 4 sections.  
## Attachments 
A general place for supplemental files to reside so that they can be referenced throughout the wiki

## Product Teams 
This is for all notes regarding the 5 product teams. Here are links to the 5 Product Teams' Homepages
- [Pre-Bind](Product%20Teams/Pre-Bind/_Pre-Bind%20Dashboard.md)
- [Post-Bind](Product%20Teams/Post-Bind/_Post-Bind%20Dashboard.md)
- [Cornerstone](Product%20Teams/Cornerstone/_Cornerstone%20Dashboard.md)
- [Document Management](Product%20Teams/Document%20Management/_Document%20Management%20Dashboard.md)
- [Martech](_Martech%20Dashbaord.md)

If there are any tasks that need to be tracked (like setting standards or filling out the wiki more), but are not on the board for whatever reason, then you can add them to the section of each dashboard that looks like this:
![Outstanding Requirements](Templates/Product%20Dashboard%20Template#Outstanding%20Requirements)

When a new note is created for a product team that does not pertain to code, builds, or deployments; link it under Important Notes > Other Notes 
![Other Notes](Templates/Product%20Dashboard%20Template#Other%20Notes)

Any notes pertaining to code, builds, or deployments should be linked under Software Development Lifecycle
![Software Development Lifecycle](Templates/Product%20Dashboard%20Template#Software%20Development%20Lifecycle)

Finally, under meta data at the bottom of the page, please use any appropriate tags to help in navigation, such as the product's name. Tags can be nested using the "/" such as "#Example/Hello_World". Please check with other tags to see if an applicable tag can be used. 
![MetaData](Templates/Product%20Dashboard%20Template#MetaData)

If you are not using Obsidian to view this page, the examples used above in this section can be  [found here](Product%20Dashboard%20Template.md)

## Templates 
This is where useful templates can be found so that formatting is standardized. If you notice you are using the same formatting (or _want_ to use the same formatting), you can a template or modify one here. 

## Unsorted Notes 
_"Most books simply deliver knowledge, this one expects some in return"_ - Unknown

This is where notes reside that are raw and not properly formatted or organized. Once a note has been organized, mark it as such by moving it to the  "Extracted Notes" folder. 

This can be anything from documents received by other team members to meeting notes. 
