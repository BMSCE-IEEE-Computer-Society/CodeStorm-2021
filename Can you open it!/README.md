# Can you open it?

> Phil was just drinking coffee in a cafe, when he saw someone in a blazer, walk in with a suitcase. This man seemed to be a business man waiting impatiently for his clients. He sat there and ordered some coffee.

> Then after a few moments, someone strange walked in and sat with the business man with a grave but suspicious face. It seemed that something important was going on. All this seemed normal until a police siren started to blow.

> Right then, the strange man abruptly got up, rushed out ignoring everything in his path. And the business man, who was calm until then, started walking out, while fumbling a pendrive into his pocket. He seemed to be too frightened to notice that his pendrive that had fallen out of his pocket and walked out in haste.

> Phil, suspicious, got up, picked up the pendrive and connected it to his laptop to see that it had only one file. But he could not open it. What could be in it? Can you get  inside it?


# Solution

Download the .docx on to your system and try opening it. But you can't.

![Error Message on Libre Office](open1.png?raw=true "error")

There is a hint in the question that something is `inside` the file.

So change the file extension to `.zip` and extract it. You will see that there are a few folders and `.xml` files.

Now we have to check all these folders and files for the flag.

In the `word` folder we have these files:

![`word` Folder Directory structure](open2.png?raw=true "word")

On running the `file` command to see if the files are corrupt, we find that one file is a `PNG` image but has been renamed with the `.xml` extension.

![file command output](open3.png?raw=true "file")

On renaming the file and opening it, we get our flag:

![flag](open4.png?raw=true "flag")

# Flag

`ctf{this_was_clever}`
