# Converting from Word to Markdown using Pandoc

This section will guide you through the steps of converting a word file into Markdown using Pandoc

## Steps

1. Open the terminal (or Command Prompt on Windows)
2. Change your working directory to the folder containing your word file
    1. Find the path to your folder
    2. Type cd (path/to/folder) into the terminal
    3. Press enter to execute the command
3. Use the Pandoc command to convert your file
    1. Type Pandoc
    2. Type -o followed by your word file name (i.e. wordfile.docx)
    3. Type -s followed by your desired Markdown file name (i.e. markdown.md)  
        **NOTE:** you must use .md at the end of your Markdown filename or it will not be made into a Markdown file
    4. Press enter to execute the command
    <figure>
    <img src="pandoccmd.png" alt="Pandoc command with directory before and after">
    <figcaption>Figure 1: Running the Pandoc command</figcaption>
    </figure>
4. Open the new Markdown file using your preffered editor (I reccomend VS Code)
5. Clean up the syntax in the Markdown file

You should now have a Markdown file with the same contents as your word document.
