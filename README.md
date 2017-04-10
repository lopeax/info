# GitHub User Name Change
I've recently renamed this user account to @zeraphie and wanted to have a small explanation as to the reason for the change

## Reasons
I am transgender and I felt that my username was too male and I wanted to update it to better reflect myself as well as it helping having a new start. It was also one of the mental blocks that I had in reference to actually transitioning, and I've been working really hard to remove those mental blocks :)

*Note:* My workplace has been amazing about the whole change and I can't thank them enough, I am a little surprised by how it's all been here, and I was so nervous!

### FAQ
I've had a lot of questions about myself after coming out to everybody, and I've set up a few responses to help some, but I would be more than willing to answer any questions that may be asked, below is a little info :) (this is pretty much copy and pasted from my facebook post! (which I also sent a slightly altered version to my workplace)

1. **My new name:** I have changed my name almost everywhere to Izzy Skye, and I am looking to change my name legally in May

2. **How long have I known:** I've pretty much known about this for my entire life, but I didn't really know that it was possible until I was about 20 years old, and it took 3 more years for me to actually go ahead because I was really worried about how I would end up.. But certain friends of mine have been seriously amazing about it and helpful :)

3. **When is this all happening:** This is a tough one to answer, as transitioning is a long process, but I am starting to live part time as a girl is helping teach me a lot of how to do everything. But in short, I would like my new name to be used as soon as possible (There are almost no references to my old name anymore!)

4. **Pronouns:** For some time I was ok with being called both he and she, but now I would prefer to be called she. I know that this is will be odd for some, which is why I would prefer it, and not demanding it

5. **Moving:** I am planning on moving later on in the year, and when I move I will be living full time as a girl. I know this will be strange for those around me (and myself!) to start off with, but I do ask for some patience with me in this regard. I will also be working from home so that's a huge bonus. So far, a date hasn't been set in stone about this, but I'm thinking around august/september

6. **Sexuality:** I thought for a while that I was bi but... because of a certain event I can say for certain I'm only into girls :)

## The route taken
I'm well aware that it isn't a small change to make, and it has been a bit of a pain for it (such as having to setup a new package in packagist for my [passwordGen](https://github.com/zeraphie/passwordGen) package. However there were a number of steps taken in order to do this, which may be useful for others to know :)

1. **Renaming my GitHub account:** It's relatively simple to rename a github account, it's just in the settings, however, there are a few things that cascade
    - Repos under that username get automatically redirected to the new username
        - Except to something like Packagist! (That's explained below)
    - The old user becomes available again (So I just remade it to make sure noone misuses my old username!)
        - If someone takes the old user, and then releases a repo of the same name, it won't redirect!
2. **Renaming my Packagist account:** Again this isn't too hard to do on it's own, however, it is a little bit of a pain to update packages for the new name
    1. Update the name of the package in your `composer.json`
    2. Update the email and add it to the GitHub user account (this was specific for me as I had a change in email as well!)
    3. Update references in the package itself (like installation instructions in a `README.md` file
    4. Resubmit the package to packagist
    5. Set the old package to abandoned in packagist, then reference the new one in the abandon message
    6. Delete and redo the packagist service (I'm not 100% sure why, but this fixed the auto-update problem)

## Anything else
I will be keeping an eye on the issues for this repo if people have questions :) I'm rather open about it and I promise I don't bite!
