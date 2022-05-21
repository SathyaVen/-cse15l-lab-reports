# Lab report 4
* [Link to my implementation of markdown-parse](https://github.com/SathyaVen/markdown-parser)
* [Link to implementation of markdown-parse I reviewed](https://duckduckgo.com)
* All expected links are according to the commitmarkdown previewer
## Using My implementation
### Snippet #1
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-21-at-1.51.46-PM.png)

### Snippet #2
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-21-at-1.55.27-PM.png)

### Snippet #3
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-21-at-1.58.45-PM.png)

## Using the implementation I reviewed
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-21-at-4.07.24-PM.png)

### Snippet #2
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-21-at-4.08.31-PM.png)

### Snippet #3
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-21-at-4.10.21-PM.png)

## Questions
1. No it appears my implementation of MarkdownParse for snippet 1 failed to add anything to the list. I think this will be a more involved change because I would need to look into why nothing is being added and then account for the cases that use inline code with backticks.
2. Similar to the #1. My implementation of MarkdownParse did not add anything to the list. This will likely result in needing to add more than 10 lines because I again will have to change the method to add links and account for the cases that nest parentheses, brackets, and escaped brackets.
3. I think this will likely require more than 10 lines of changes. Instead of adding the only valid link, my implementation added all of the links as well as some text that was not even part of the link. I think something may fundementally be wrong with my implementation, which will require more intensive changes.
