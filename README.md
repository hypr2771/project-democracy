# Please remember this is basically a sample study and in no way a serious project as for now

# Project Democracy

**Project Democracy** is aiming to bring true democracy by bringing back legislative, executive and judiciary power in the hand of its people.

The primary goal of this project is to show it is possible to vote over the Internet, and that doing so should only bring advantages.

## Requirements

What we need to be able to do such a service :
- a client to express your vote (centralized or distributed)
- a service to verify the validity of a National Identity Card
- a service to verify that the holder of the card is the citizen currently voting (through AI KYC-like method)
- an anonymization method when people publish their vote on a public immutable database
- a public immutable database (*aka* public blockchain)

## Why

We, as citizen, express ourselves through this project following *J. J. Rousseau*'s [*Du contrat social*](https://fr.wikipedia.org/wiki/Du_contrat_social) as it shaped human vision of democracy.

You are today a citizen of a supposed democracy, but as we can see, you often feel you have no choice over your future but to choose who is gonna govern and choose in **YOUR** place for each important decision.

You are honestly abandoned by people you elected, at the profit of [lobbying](https://www.hatvp.fr/presse/bilan-des-inscriptions-au-repertoire-des-representants-dinterets/), their own [family](https://www.latribune.fr/economie/france/emplois-fictifs-une-longue-tradition-dans-la-vie-politique-francaise-636270.html) or whatever we do not know yet...

In any way, anyone would agree, a perfect democracy would be giving the people the key to its own future, so that whatever they choose, they accept and are responsible of their own action.

Through the **Project Democracy**, we are hoping to give the people a chance to choose and let emerge honest, implicated citizen, as well as let impersonators, liars sink their credibility on their own.

We are completely aware that there is a very long way to achieve such a curve in the way political is incorporated to our daily lives.

We really want to insist that if **Project Democracy** ever brings a disadvantage to citizen, it should not be released. It should only be an enabler and in no way a disabler or a danger to its citizen.

#### The bad points that will remain :
- Influence from an external source using manipulation techniques, either physical or moral
- Identity theft from a look-a-life person

#### Problems it solves :
- [Enormous costs of election](http://www.senat.fr/rap/r15-123/r15-1232.html)
- Uncomfortability of citizen feeling able to express their civic intelligence only once each 5 years
- The misinformation led by some media and by political figures should disappear and enable independent and proven trusted citizen (through social media analysis of a given proposal for instance)
- The simplicity to vote, which should bring back people into the democratic circuit
- The ability for disabled, hermit and marginal people to express themselves if they want to
- The result is public, trustable and immutable; what is more, it can be available through a public database (*aka* blockchain), so we can chain the result of a vote to the execution of a law, contract, or whatever events you may imagine
- Many others (feel free to contribute to add your point)

#### Problems it brings :
- It could encourage extremist citizen to "kidnap" or force other citizen to vote for a specific choice (suggestions in the **Inscription on the application** section)
- Undeclared dead people could still be impersonated to vote numerous times

## How

A citizen should have only a few steps to be able to vote, and it should be similar to the current process :
<pre>
+------------------------------------+------------------------------------+
|           Traditional              |          Project Democracy         |
+------------------------------------+------------------------------------+
| Inscription on election lists      | Inscription on the application     |
| Presentation on voting office      | KYC-like procedure for ID check    |
| Expressing your vote secretly      | Expressing your vote secretly      |
| Coming back home                   | Closing the app                    |
| Waiting for the results            | Waiting for the results            |
| Waiting for application of results | Application of results             |
+------------------------------------+------------------------------------+
</pre>

We will now describe each step of **Project Democracy** and show it is currently doable.

### Inscription on the application

This step consists in :
- Downloading the application (which is verified by either a GPG signature or a certified entity)
- Present and accept your rights and responsibilities using the app
- Anonymization step (define your own language to avoid forced by violence vote)

### KYC-like procedure for ID check

Each time a citizen will have to express a vote, he will be required to complete this step.
This step consists in :
- Ask a random serial from the app
- Write the serial down on a paper, hold your card and this paper and take a selfie (this procedure may be modified using new methods)
- Validate through AI KYC-like that the person holding the card is the one voting
- Obtain from the government API a number
- Add a salt (when and how to store it ?) to obtain an anonymized ID (which should be the image of the current vote and the ID + salt of the citizen)

### Expressing your vote secretly

Using the anonymized ID, we can credit a "token" to this unique citizen.
Using this token, he can epxress once, and only once, his vote, using button on a terminal (web, app, cli,...)

### Closing the app

Whenever you close the app, you will be requested to do all the KYC step again to protect identity of the user.

### Waiting for the result

Once a vote is submitted, we do not know yet if we should publish it instantly to the public database as it may allow strategic vote. If yes, the current mechanisms of blockchain should allow us to do so and publish blocks of votes.
If not, we need to either make long time blocks, or to sign and reveal votes at the desired time using citizen's signature.

### Revelation & application of the result

When the last block is mined/minted/whatevered, we withdraw every tokens used to vote.

We may or may not verify signed votes in order to reveal their value and then reveal the result.

The result is published on the public database, so each software watching the result may chain their expected behaviour (public a press article, show on TV the result, publish the law,...)