# Automating Setting Dark Mode in Chrome using Ubuntu

I faced a problem with dark mode in Linux Ubuntu 22, specially when using Chrome. I had to manually set dark mode in Chrome using [this tutorial](https://dev.to/ankitbrijwasi/enable-dark-mode-in-chrome-on-ubuntu-20na), but every time I updated Ubuntu, Chrome was set to light mode again and I had to manually make the process all over again.

Then, I had an idea 💡

### What if I use Shell Script to make it for me?

I developed a simple shell script code to set Chrome to dark mode. It is available in this repository, the file is named "chromedarkmode.sh".

To make the process even more simple, I created an alias in `.zshrc` named "chromedarkmode" pointing to the path of the "chromedarkmode.sh" file and, now, every time I update my system, I just had to type the command "chromedarkmode" in terminal and that's it.

In the command, I used sed, but you can use perl as well. Go ahead :)
