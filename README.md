# stock-market-volatility-analysis

Why does volatility in the stock market drive the median return down to 0 but keep the average return the same?
The stock market grows on average 10% percent a year. If the stock market grew exactly 10% percent every year for a century, your investment would increase 13781 fold.

But the stock market doesn't go up exactly 10% percent every year. Sometimes it's a little more, sometimes it's a little less (or as with the Coronavirus fallout right now, a lot less).

What happens to the market and to the median investor as this volatility increases?

Let's test out different stock markets based on their volatility. So all the markets will grow a person's money on average 10% every year for a century. But the return for any given individual for any given year will be randomly pooled from a normal distribution centered around 10% and with a standard deviation determined by the volatility of the market. More volatile markets will have a higher standard deviation.

Let's test out every market that has a standard deviation of returns between 0% (you'll get 10% returns every year) to 35% (it'll be wild as shit). We'll put 250000 investors in every maket. Each of them will start with $1 and they will each get a different random return every year for a century based on how volatile their stock market is.

Would the median investor make the same amount of money in the long run across all these markets? Would the stock market as a whole rise the same?

### It seems that the returns of the median investor asymptotically approach 0 as volatility grows while volatile markets as a whole do just as well. My explanation is that in a volatile market, most people encouter a year where they loose their entire principal and can't make it up but some people get stupendously lucky, leaving the average return the same regardless of volatility.
