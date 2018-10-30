# In code we trust

If crypto bills could have slogans this would be it. This is not news in cryptoverse. Even 
[New York Times](https://www.nytimes.com/2015/05/03/magazine/in-code-we-trust.html) saw this a long time ago.
There is another dimantion to this slogan though. I've been following cryptoverse for a while. I've read numerous
news articles. I've followed excellent explanations of main concepts. I've even read very technical colored papers.
Still I must admit my ignorance. A very crucial part is missing. Even though I'm a software developer, I have not written
a single blockchain related line of code. Therefore I don't really understand it and I don't really trust it.

## Why bother with code?

Code is the brain of any cryptocurrency, obviously. It's also a door to understanding it. Reading about blockchain concepts is nice but
it's not enough. If you didn't implement those concepts in code, you don't really know them. Reading articles about cryptos
becomes reading about magic in Harry Potter. It's interesting but fundamentally you can't predict what works and
what doesn't.  

## Why do it on Steemit?

If things are somewhat clear on 'code' in 'In code we trust', who are those 'we' that do the trusting? It's the best kept
well known secret (everybody knows it but no one talks about it). Money needs community of people that believe in it.
Otherwise it's just code (or shiny things, paper, cigarettes).
We get value in exchanging things, time, ideas, etc. Money is just a medium that the community trusts. 

I have something to offer: a perspective on how to learn cryptos, selected links to tutorials, step-by-step guide, code. 
All that will be even more valuable if someone else offers an opinion, another perspective, or anything else they have to offer. 
This suspiciously sounds like open source. You give me some code and I'll give you some code back. What if we added an exchange medium to the mix?
Steemit sounds perfect for the job. Also there is some kind of cool circular feel to it: 'Learn blockchain on blockchain!'

## Sounds fancy but who cares?

My first interractin on Steemit gave me hope that my learn crypto project might be useful for someone else.
To be honest I didn't plan it like this. I thought I'll write code on Github and that will be it. Recently I wrote
intro post on Steemit. Among informative, welcoming, and encouraging comments there was one other very useful kind from
@eccles who politely inquired why I haven't written my next post yet. Being held accountable is very rare and precious
because not caring is the normal state of the Universe. Mean bosses don't count. They really don't care what you do.
They just worry they will not get paid if you don't do something. I started wondering if I should split my plan into
smaller more presentable chunks. True, quality must not be sacrificed but good old 'publish or parish' is too old now.
The reality now is 'publish fast or parish fast'. Inspired by that and lots of useful info from people and bots in my
intro post, I decided to make series of post on Steemit cauppled with code on Github. I was also surprised by bot
comments. At least I think they were bots but I can't be sure.
I wonder if calling an entity a bot will soon be politically incorrect. Maybe we'll call them autobeings.


## How are gonna go about it?
The general plan is to split concepts into biteable chunks, pick a concept, implement it in code, 
write Steemit post about it, listen to what people and autobeings have to say, make corrections
or improvements, and repeat all the steps building on already implemented code. The approach is no different from
writing any other complicated software. It's not possible to grasp all blockchain complexity at once but it's possible
to do it in series of software patches and small blog posts.

## Where should we start?
Nothing is new under the sun. This statement might not be true in general but it holds in our specific case.
Let's not waste all that good work.

## So much bla-bla-bla, where is the code?

Okay, okay my imaginary impatient friend. 

First there is a 
[project](https://github.com/dvf/blockchain)
with simple 
[blockchain](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46)
implementation and accompanying blog post
[explanation](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46).
This is a nice and simple step by step tutorial. It uses Python Flask to build endpoints that add new transactions to
a block, mine new block, and return full blockckain.

The second
[project](https://github.com/adilmoujahid/blockchain-python-tutorial)
with related
[blog post](http://adilmoujahid.com/posts/2018/03/intro-blockchain-bitcoin-python/)
also uses Python Flask but implements more complicated version and introduces blockchain client. I like how author uses
gifs to show how things suppose to work.

The third
[tutorial](https://github.com/satwikkansal/python_blockchain_app)
adds a little twist and builds a very simple website that stores content on the blockchain. There is no separate blog
post but there is an
[awesome explanation](https://github.com/satwikkansal/python_blockchain_app/blob/master/step_by_step_tutorial.md)
page on the Github project itself (which is even better).

The forth
[project](https://github.com/jackschultz/jbc)
is a strong proponent of 'read the source code' movement. There are some instructions in README.md file and the code
seems to be well organized with comments.

The fifth
[project](https://github.com/cosme12/SimpleCoin)
is more coin orient interpretation of blockchain. It has separate miner and wallet modules.

Let's take a brake and actually read Satoshi's paper. I like the
[paper in MD](https://github.com/bitcoinbook/shatoshi-paper/blob/master/markdown/bitcoin.md) format but there is also
[official pdf](https://bitcoin.org/bitcoin.pdf) 
if you prefer pdfs. The paper is surprisingly short.

The last project is an implementation of
[bitcoin blockchain parser](https://github.com/alecalve/python-bitcoin-blockchain-parser). It's interesting to see the
code that actually interacts with the real working blockchain.

For desert there is
[bitcoinbook](https://github.com/bitcoinbook/bitcoinbook)
Github project. It has some code examples as well.

## What's next?

My plan is to work through links above and implement my own simple version of blockchain. I will not rewrite existing
explanations. Instead I'll focus on things that weren't mentioned or interesting twists. I'll focus on a single concept
per post to keep things short and keep posts as frequent as possible.