
# DataView Examples

## Example 1 --> Get a list of information based on a single note
%%
'''dataview
TABLE WITHOUT ID
    link(file.name) as "Day",
    feeling AS ":thought_balloon:",
    panic AS ":zap:",
    working-on AS ":pencil2:",
    money-spent AS ":money_with_wings:",
    martial-arts AS ":boxing_glove:",
    weather AS ":sunny:",
    prayer AS ":kaaba:"
FROM "01 Personal/01.01 Periodic Notes"
WHERE week = "2022 Week 09"
SORT file.name ASC
'''
%%
## Example 2 --> Get a list of all the files that have a tag 
%%
'''dataview
TABLE WITHOUT ID
	link(file.link, file.aliases[0]) as "Subject"
	FROM # Contact/Person and !"0A_Templates"
SORT file.name ASC
'''
%%

## Example 3 --> Automatically place file alias in a section
The value inside the `[]` represents what aliases will be used, in case you have more than one change the value to the corresponding number. 
**Count start always at 0**
%% ` =this.file.aliases[0] ` %%

## Example 4 --> All files that are linked to current document
%%
'''dataview
TABLE WITHOUT ID
    link(file.name) as "Day",
    feeling AS ":thought_balloon:",
    panic AS ":zap:",
    working-on AS ":pencil2:",
    money-spent AS ":money_with_wings:",
    martial-arts AS ":boxing_glove:",
    weather AS ":sunny:",
    prayer AS ":kaaba:"
`WHERE contains(this.file.inlinks, file.link)`
SORT file.name ASC
'''
%%