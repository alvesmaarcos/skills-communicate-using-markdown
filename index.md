# Markdown foundations in GitHub Education!
### This file represents the beginning of the "Communicating using Markdown" course, provided by GitHub.
#### In the end of this course, I expect to have full understanding of the Markdown formatting language; such will be used in my next projects, and the result will be cleaner and readable texts, especially in the README files. The result must be an improved communication between the members of enrolled with the projects.
##### The headers used above are h3 and h4. The first line must be bigger than the second one, and it will be bigger than the third one... The objetive of it is to make size constrast in the file, resulting in a cleaner reading.
###### The line above uses the h5 header, while this one uses h6, the smallest header in Markdown.

# Images in Markdown!
###### Under this line, there will be an image of the Yaktocat!

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

# Code lines in Markdown
To type code lines using this language, you need to use "```(language that will be shown)\n code\n```".

## Example in Java
``` Java
public class Shell{
    static Adapter adp = new Adapter();

    public static void main(String[] args) {
        while(true) {
            write("$");
            String line = input();
            args = line.split(" ");
            write(line + "\n");
```

# Task lists in Markdown

### Text format:
```
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```
### Format in markdown:
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
