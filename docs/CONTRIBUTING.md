# How to contribute

I'm really glad you're reading this. See steps below!

---

### Step 1: Branch

Create a branch from `main`. 
Name the branch as `language-XX` where `XX` is the [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) code.

```text
$ git checkout -b language-XX -t origin/main
```

### Step 2: Translate

Use as starting point the English file.
 - Translate only the value from the array.
 - Keep the HTML structure where case.

### Step 3: Commit

Make sure git knows your name and email address:

```text
$ git config --global user.name "Random User"
$ git config --global user.email "random.user@example.com"
```

#### Commit message guidelines

Always write a clear log message for your commits.
One-line messages are fine for small changes, but bigger changes should look like this:

```text
$ git commit -m "add XX language
>
> A paragraph describing what changed and its impact."
```


### Step 4: Push

Push the code on your new branch.

```text
$ git push -u origin language-XX
```

### Step 5: Pull Request
Please create a [GitHub Pull Request](https://github.com/mihaituhari/rescue4x4-language/pulls) for the language you are adding.

#### PR guidelines

 - Set PR title as `Add language: XX`
 - Update the PR description as per template
 - Mark it as `ready-for-review`
 - That's it!

Thanks, @mihaituhari
