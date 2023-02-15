Coding is a collaborative process with ourselves and others. Collaboration is only possible if there is a shared understanding between people and, more importantly, [over time](https://twitter.com/commitstrip/status/689153602254974976){:target="_blank"}. Never trust your future self to simply remember what you know today, or [you may become your own worst enemy](http://www.threepanelsoul.com/comic/on-perl){:target="_blank"}. To make things easier for [yourself](https://www.meme-arsenal.com/en/create/meme/4734358){:target="_blank"}, **write your code as if it is going to be read by someone who doesn't have any context about it**. There are a million different ways to make code more readable, but here are a few basic ones:

### Style
- *Write short lines.* While different languages have different rules for the ideal script length, almost all style guides recommend not going beyond 80 characters in a line.
- *Write short, modular scripts.* One rule of thumb is to aim at having no more than 200 lines per file. Another one is that if you are loading data, this should be the start of a new script -- and if you are saving data, this should be the end of the current one.
- *Use a [style guide](https://xkcd.com/1513/){:target="_blank"}.* For DIL projects, follow the style guides linked in the buttons below.
- *Use white space and indentation.* Youcanreadandunderstandasentenceevenwithoutspaces. But they sure make it a lot easier. Different languages have different standards for how to use spacing. Check the style guides linked above for recommendations. 

[Modular programming](https://www.tiny.cloud/blog/modular-programming-principle/){: .btn .btn-more }{:target="_blank"}
[DIME's Stata style guide](https://worldbank.github.io/dime-data-handbook/coding.html#the-dime-analytics-stata-style-guide){: .btn .btn-more }{:target="_blank"}
[Tidyverse's R style guide](https://style.tidyverse.org/){: .btn .btn-more }{:target="_blank"}
[PEP8 - Python style guide](https://peps.python.org/pep-0008/){: .btn .btn-more }{:target="_blank"}

### Content
- *Write self-documenting code as much as possible.* Name variables, files, directories, and functions intuitively (e.g., `temp` is a terrible name for both folders and files). We recommend avoiding blank spaces in file and directory names.
- *Make inputs explicit.*
- *Divide scripts into sections with self-explanatory header titles.* Both the Stata do-file editor and RStudio have built-in features for this.
- *Add comments to the code*: self-documentation can only go so far. Comments should explain not only *what* you are doing, but *why* you are doing it.
- *Add metadata on functionality, inputs, and outputs to your code.* The creation of documentation for functions is automated in R and Python, but this type of information is also important when writing data processing and analysis scripts. For the latter, include a header with information on the purpose of your code, what files it uses, and what files it creates.
- *Write a project readme and have a system to keep it updated.* Create the habit of updating the readme when you finish a task, open a pull request, or ask someone to review your code.