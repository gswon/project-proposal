# Signalfolio

## What and Why?

Portfolio News Intelligence is a mobile-friendly web application that helps users understand which financial news is actually relevant to the assets they own or follow.

There is already a huge amount of financial information available through news websites, social media, and investing apps. The problem is that most of it is not personalized. Users still have to figure out which events actually matter to their own portfolio.

This costs real time and attention. An investor can scroll through dozens of headlines, spend half an hour doing it, and still miss the one story that affects a position they actually hold — while worrying about companies they do not own at all. The result is not just wasted time, but decisions made late or based on the wrong information.

A user would enter the stocks, ETFs, or cryptocurrencies they own or follow. The system would analyze financial news, identify which assets may be affected, and explain the possible impact in a short and understandable way.

It would also consider indirect effects. For example, a Federal Reserve interest-rate increase could affect technology stocks such as NVDA, cryptocurrencies such as BTC, and banks such as JPM differently, even if those assets are not directly mentioned in the article.

The main idea is simple:

**What matters to my portfolio, and why?**

The goal is not to predict prices or tell users what to trade, but to help them quickly focus on news that is actually relevant to them.

## For Whom?

The main users would be individual investors who manage their own portfolios or watchlists.

Our initial users would include NYU students, classmates, friends, and other people we know who already follow financial markets or invest on their own. Since these are users we can directly reach, we can gather feedback throughout the semester on how useful the personalized news feed is.

## How?

A user would create an account, then build a portfolio or watchlist by adding assets such as NVDA, AAPL, SPY, or BTC, and optionally enter the approximate weight of each asset. Holdings could be added, edited, or removed at any time, and a user could keep more than one list — for example, a real portfolio and a separate watchlist.

The main page would show a personalized news feed ranked by relevance to the user's portfolio.

Each news item would include:

* a short summary
* directly and indirectly affected assets
* Bullish, Bearish, or Neutral potential impact
* Low, Medium, or High impact level
* a confidence score
* a short explanation
* and a portfolio relevance level

For example:

> **NVIDIA announces new data-center partnership**
>
> - **Affected asset:** NVDA
> - **Potential impact:** Bullish
> - **Impact level:** High
> - **Confidence:** 82%
> - **Why:** The partnership may increase future demand for NVIDIA's data-center products.
> - **Portfolio relevance:** High — NVDA represents 22% of your portfolio.

Users could also search and filter news by asset or impact level, and save stories for later.

## Scope

This project is appropriate for a team of 4–6 programmers because it includes several separate components: user accounts, portfolio management, financial news collection, news analysis, asset identification, relevance ranking, search, and the user interface.

To keep the project manageable, the first version would not include brokerage integration, automated trading, stock-price prediction, or full social-media monitoring. Users would enter portfolios manually, and the system would focus on a limited set of reliable news sources.

These limits keep the project realistic for one semester while still leaving enough technical depth for a full team.
