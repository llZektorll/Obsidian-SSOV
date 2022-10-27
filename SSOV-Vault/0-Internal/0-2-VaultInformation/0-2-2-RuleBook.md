---
created: "2022-09-23 at 10:54"
aliases: "🔴 Vault Rules 🔴"
tags: 
- "Vault/Rules"
022Version: 1.0
---

# 📕 - Vault Rules

## Section 1 - Standards used
1. All documents will have the date and time according to [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html) since is the most used date format.
2. All the information that is not related to the vault information (*Templates, Rules, Examples etc..*) will be inside the same folder "0-Internal"
3. All the templates have a version control in the YAML so it's easier to find end correct files that used older versions. The version in YAML is always defined with the path of the file. This Vault Rule file have a version named *021Version*. The numbers will always indicate the vault structure up to the file location. 

## Section 2 - Templates
1. All the templates a based on my repository in [GitHub](https://github.com/llZektorll/OB_Template) 
2. All of the templates are basic templates so it can be adapted to any user use case, in this template vault since is aimed at any sort of study, i will only include relevant templates. These templates may have some changes from what is published on the [GitHub](https://github.com/llZektorll/OB_Template)

## Section 3 - Folder structure
1. The folders structure should be divided into general groups for example
	1. 1-General-Knowledge
		1. 1-1-Mathematics
		2. 1-2-English
		3. 1-3-Science
	2. 2-Applied-Knowledge
		1. 2-1-Programming
			1. 2-1-1-Python
			2. 2-1-2-Csharp
		2. 2-2-Law
			1. 2-2-1-LaborLaw
			2. 2-2-2-LawAndEconomics
3. This vault is designed to use 2 static folder, with this i mean:
	1. The first folder will be "0-Internal" that will have all the static information (*Templates, Rules, Examples etc..*) this should not have many changes since it's set to be a vault guideline.
	2. The second folder will be the most used folder on the vault "1-Inputs" here is where all the notes start. Before any note is assigned to it's folder, while is written, it may not follow the correct language or the correct structure. These notes will be moved to their final destination once they are revised to ensure all the information there is as clear as possible. **NOTE: This does not mean the note will no be used afterword's. This workflow is set to ensure all notes are revised. This processes also helps memorize and understand the information placed there.**
## Section 4 - Notes and Links
1. Every main folder such as 1-General-Knowledge and the folder inside 1-1-Mathematics should have an index page. This index page will serve as a easy way to connect subjects to the main topic and a specific subject afterword's. This will make search the vault the same way you can read a book index.
2. The note name should have a direct connection to the folder, meaning that if the note is place inside the folder 1-1-Mathematics the first note should be 1-1-1-FirstNote. This will prevent notes with the same name
## Section 5 - Screen Shots, Images and other files
1. With time a vault will get quite big and in most cases, having a single folder for all the files that are added to Obsidian can become a mess. For this case, it's recommended that in note that is placed a file, photo, etc.. a folder named 0-Resoruce should be created. This way if the need to share the file arrives it's easy to find it's location. 
## Section 6 - Tags
In general tags can be under used or over used in most cases. In the first place i recommend a read of [Working with tags](https://help.obsidian.md/How+to/Working+with+tags#:~:text=%23%23%23%20Add%20tags%20Just%20type,your%20notes%2C%20sorted%20by%20frequency.) the rules below are how i use tags, it's not ideal or the best method but it is how i feal more comfortable and how i am able to use tags effectively on my vault
1. All files are required to have at least 1 tag
2. Tags have levels "#tagLevel0/tagLevel1/TagLeve2" this is used for most files having them link to specific sections of the vault.
3. All the index files will only have 1 tag. If the Index file belongs to the root folder "1-General-Knowledge" the tag should be "#Menu/Home", any index file below the root folder will have the tag like this "#Menu/Mathematics"