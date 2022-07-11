# discord-rickroll

when you send the usual rickroll link "https://www.youtube.com/watch?v=dQw4w9WgXcQ" discord crawls it and gets the text inside of the meta tags (the title, description and image ones) and the meta tags on that page make it extremely obvious that its a rickroll.

## however
you can make your own page with your own meta tags that make it appear as if the webpage serves another purpose.
for example the file "fbi.html" has meta tags that make it appear as if it were a site offering secret fbi information when in reality its a rickroll so when you send a link to that file thats hosted on a webserver it appears as 

![preview](https://cdn.discordapp.com/attachments/956721423949385828/995839242464919642/Screenshot_2022-07-10_19-48-12.png)

rather than the obvious

![preview2](https://cdn.discordapp.com/attachments/956721423949385828/995839946508214332/Screenshot_2022-07-10_19-48-12.png)


## another method
is the file "fbi.php" where discord sees different content than the user will see when they click on it.
when discord makes a request to the file, the program detects that its discords user agent and shows different html.
when a user makes a request to the file, the program detects that its not discords user agent and shows the rickroll.
