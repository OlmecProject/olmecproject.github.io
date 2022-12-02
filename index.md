---
layout: default
---

# Tepe

Tepe introduces a powerful new paradigm in the evolution of web3: **end-to-end token-gating of content**. The Tepe project is a proof-of-concept working example, and is the only existing method that allows you to control access to content completely within a smart contract. *Please, point us to another example if you can.*

## End-to-end token-gating

[End-to-end](https://en.wikipedia.org/wiki/End-to-end_principle) token-gated content is the next big step in web3.

Most content in web2 is gated, from Netflix and YouTube to Amazon's ebooks and Instagram. As a creator, *you* are uploading *your* content to the server owned by a company. As a consumer, *you* are only buying temporary access to view the content or are paying by spending your time to watch ads.

That will all change in web3. As a creator, *you* can own your own content and distribute them directly to your consumers. As a consumer, *you* can buy directly from creators. You can also resell into a market, lend to friends, or collect them.

Remember when you could lend out a book to friends? You can't do that with ebooks on Amazon. Or resell a vinyl records to a store? You can't do that with a Spotify subscription. That's all coming back digitally.

NFTs are the way we get from here to there. But now, NFTs hold no secrets: they display metadata for the world to see. With private NFTs, an NFT can unlock content if you own it. No middleman exists: if you own the NFT, you can access the content.  That's the beauty of end-to-end token-gating.

## App

We built an app as a proof-of-concept for end-to-end token-gating. 

At a high level, your content gets encrypted and can then be posted anywhere and everywhere.  The key to decrpyting the content is then stored within the contents of a smart contract, and the key is only handed out if you own an NFT corresponding to the content.  Nowhere is trust necessary: once the contract has been created, the token-gating is all handled according to the contract.  If you don't have the right NFT, you don't get access.

It uses the [Secret](http://scrt.network) blockchain to handle the private tokens and [ipfs](https://ipfs.tech) to store encrypted files. The app lets you encrypt and upload your content to ipfs and hides the password to the content in the Secret token. You can send your tokens to your friends, who can only unencrypt the file if they own the token.

A unique feature of this tech stack is that you don't need our app to use the stack. The essential component is the smart contract, [which we have also uploaded](https://github.com/TepeProject/tepe-contract); the app just handles all the contract interactions and adds some convenience functionality. You could also use third-party software or command line tools to do all the same things.  

To build and run the app, see our app [repository](https://github.com/TepeProject/tepe-app).

## Contribute

The project is open for contribution. We are also looking for feedback. Join our [Discord](https://discord.gg/Hfu9hhcqv9) to chat.

## About

We are two postdoctoral researchers who built this as a side project. [Kieran Murphy](http://kieranamurphy.com) is a postdoc at UPenn developing machine learning tools to study complexity. [Harang Ju](http://harangju.com) is a postdoc at MIT Sloan studying the economic and social impacts of web3.

## "Tepe"

Tepe is a Turkish word for "hill". We were inspired by [Göbekli Tepe](https://en.wikipedia.org/wiki/G%C3%B6bekli_Tepe), a Neolithic archeogical site in Turkey. It is the oldest known megalith, dated to 9500 and 8000 BC, and it rewrites human history.

Further, Göbekli Tepe was deliberately covered by dirt. Some speculate it was covered as a time capsule to send a message to the future. So not only is Göbekli Tepe inspiring from a historical lens, the speculation about sending covered messages is an analogy for end-to-end token-gating on Tepe.
