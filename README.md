# [knowledger](https://arweave.net/SXaeOyhlqkAPz8ydfwhzU65UA6liZqZhQp2vkQggr_0)
This project set out to provide a mechanism by which submitters of resources/knowledge about blockchain (aka a repository of resources to be cited against in research/development) could record details about a link/source, and then attach a validity bond denominated in AR token - one's AR address would also be attached to the attestation.

# Challenges I faced
I was not able to get the javascript to work - I previously was jusing Firebase to store the db as a "centralized database" that could still be permissioned using the token - this way, the previous, old data that was ported over, with no validity bond, still showed up at the top of the list, for others to verify and validate. Posts with highest AR are "safest", as the database (centralized) is shown in an ascending order from lowest bond (null) to highest.

The concept is that items at the bottom are safe, and the resources at the top are the oldest and need the most vouching for to ensure that they are still up to date. Otherwise, the information could be raw.

I developed a front end side-by-side form & display of the database, but the submit function does not work properly on the app submitted to the Arweave permanent web. I have included the github pages hosted version for comparison. For next steps, I will work on debugging why I'm having javascript issues on this, & how to actually read in the address from one's Arweave extension and then create a prompt to pay in AR token to make the post.

# Next steps

In the future, I also would like to add the function to "top up" and attach multiple bonds to the same news article. Thus, both individuals who are "finders" & are users of the repository can both give credit to a source.

# Feedback

As for using Arweave, the process to upload a file and make sure that there were no missing dependencies was difficult when I had some external js for which I could not verify that everything was included (Semantic UI sucks...). I had to strip down a lot of code to make it under the 2 mb limit to submit to Arweave, but hey, at least my code is more condensed now!
The non-constant blocktimes made it difficult for me to know if something was wrong with my submission or if the network was just taking a random amount of time to mine the next block. Would love to learn more on how I could help mine some Arweave.

[Arweave permaweb link](https://arweave.net/SXaeOyhlqkAPz8ydfwhzU65UA6liZqZhQp2vkQggr_0)

[Github pages link](https://calchulus.github.io/arweave-knowledger/submit.html)
