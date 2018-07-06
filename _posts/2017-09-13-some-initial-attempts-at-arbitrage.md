---
layout: post
title: Arbitrage
permalink: arbitrage
tags: [links]
comments: true
---

[DRAFT]

TL;DR: I spent a week looking for arbitrage in crypto markets, and I have some code for coinmarketcap and etherdelta

So this started with the "China ban bitcoin" FUD - this weekend, Bitcoin was apparently selling for ~$3500 on Chinese exchanges compared to $4100 - $4200 in Western markets, so (since I'm Chinese) I started thinking about buying Bitcoins in China, and then selling it on other exchanges for riskless profit. So when first considering such an opportunity it's important to know what price coins are selling for on which exchanges. <a href = 'https://coinmarketcap.com/'>Coinmarketcap</a> is a great tool for doing this. The first page is a list of all coins with price and market cap -- you can click into each coin, and you can see its price chart. You can click on the Markets tab to see all the exchanges the coin is trading in. The UI is pretty helpful, but when juggling lots of different currencies and exchanges, it's better to scrape the data than to manipulate it.

