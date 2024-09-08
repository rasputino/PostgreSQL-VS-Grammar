# PostgreSQL VS Grammar
# Textmate grammar in Visual Studio

This is a project cloned from the Textmate Grammar example of Mads Kristensen that demonstrates how to ship Textmate grammars inside Visual Studio extensions. But modified to support PostgreSQL grammar.

The grammar syntax comes from https://github.com/tkopets/sublime-postgresql-syntax

## Motivation
Currently, `.sql` files are highlighted using MSSQL syntax by default. This can sometimes lead to incorrect syntax highlighting, especially when working with PostgreSQL-specific syntax.

For example:

![Example 1](https://github.com/user-attachments/assets/b4d1d1d8-d326-4eb3-9195-b747ef691857)

![Example 2](https://github.com/user-attachments/assets/cf4a97f8-29a8-4a2c-b095-f55f0122b044)

To avoid this, I often rename my SQL files to use the `.psql` extension. However, doing so causes the syntax highlighting to be lost entirely.

## Solution
And this is why this project exists.

![Example 3](https://github.com/user-attachments/assets/5dfb90ee-e1b5-48d3-ad09-21a152643b63)

![Example 4](https://github.com/user-attachments/assets/a8a0ae60-97d7-4544-bdc7-8402df066437)
