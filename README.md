# How to add these custom snippets to your workspace
Copy the folder into the root of your project directory (typically where your project's package.json is located)

# How do I add these snippets globally to all my projects?
Copy the content of the custom-snippets.code-snippets file into your global user snippet. To do this: 

1. Hit `CMD + Shift + P` if you're on a Mac or `Ctrl + Shift + P` on a PC to open the command palette
2. Type in `User snippet`
3. Select `Snippets: Configure User snippets`
4. Select either: 
    A. `New Snippets File`
    B. The existing global snippet file if you already have one
5. Paste in the code from the custom-snippet.code-snippets file, making sure your json is valid

# Why use workspace snippets?
When you work in a team, it can be useful to have everyone using the same setup. Snippets are one example of what can be shared but you can also share workspace settings like formatting, extensions etc. Here's a link to the [documentation](https://code.visualstudio.com/docs/getstarted/settings) for more information.