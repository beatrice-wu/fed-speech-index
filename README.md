# Fed Speech Hawkishness Index

A public web page that scores Federal Reserve speeches from −10 (dovish) to +10 (hawkish), tracks the smoothed index against the US 2-year yield, the dollar index and the S&P 500, and lets you score a new or past speech with your own Anthropic API key (the key stays in your browser).

- Site: https://beatrice-wu.github.io/fed-speech-index/
- `index.html` is the whole site (data inlined); `data.json` holds the same data for reuse.
- Built by the fedspeak pipeline in a separate repository (speech text, Google News headlines and market reaction, combined 40/30/30). Market data: FRED (DGS2), Yahoo Finance (DX-Y.NYB, ^GSPC).
- Scores are AI judgements, not investment advice.
