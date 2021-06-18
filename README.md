# Tales from the Crypto (Homework)
![Spare a Crypto ](Images/crypto.png)
## Background
This is a summary of the NLP Homework at the Columbia Fintech Bootcamp Summer 2021. Sections are:
1. [Sentiment Analysis](#1---Sentiment-Analysis)
2. [Natural Language Processing](#2---Natural-Language-Processing)
3. [Named Entity Recognition](#3---Named-Entity-Recognition)

#### Author's Note: The code hangs on:<br>
*print(btc_doc.ents)*<br>
and<br>
*displacy.serve(eth_doc, style="ent")*<br>
stopping the code and re running from that point works.

### 1 - Sentiment Analysis
Q: Which coin had the highest mean positive score?

    A: Etherium has a higher mean positive score of 0.0642 vs 0.0432

Q: Which coin had the highest negative score?

    A: Bitcoin has highest negative score 0.213 vs 0.139

Q. Which coin had the highest positive score?

    A: Bitcoin has the highest postive score at 0.282 vs 0.166

### 2 - Natural Language Processing
Top 10 words for each coin<br>
**Bitcoin:**<br>
[('char', 99),
 ('bitcoin', 80),
 ('cryptocurrency', 32),
 ('reuters', 27),
 ('world', 19),
 ('currency', 19),
 ('tesla', 18),
 ('ha', 17),
 ('week', 17),
 ('elon', 17)]
 
**Eth:**<br>
 [('char', 19),
 ('cryptocurrencies', 6),
 ('market', 6),
 ('cryptocurrency', 6),
 ('ha', 5),
 ('backyardproduction', 4),
 ('istockcomcryptocurrencies', 4),
 ('skyrocketed', 4),
 ('popularity', 4),
 ('recently', 4)]
 
**Here is the Word Cloud for bitcoin**<br>
![Bitcoin Word Cloud](Images/btc_cloud1.png)

**Here is the Word Cloud for ethereum**<br>
![Eth Word Cloud](Images/eth_word_cloud1.jpg)

### 3 - Named Entity Recognition
##### Here are the entities for each corpora:

**BTC:**<br>
[('american', 'NORP'),
 ('first', 'ORDINAL'),
 ('wednesday', 'DATE'),
 ('morning', 'TIME'),
 ('bin', 'PERSON'),
 ('past month first', 'DATE'),
 ('billion', 'CARDINAL'),
 ('couple day', 'DATE'),
 ('tuesday night', 'TIME'),
 ('wednesday morning', 'TIME'),
 ('hundred billion', 'CARDINAL'),
 ('morning', 'TIME'),
 ('first', 'ORDINAL'),
 ('last weekend', 'DATE'),
 ('week reviewlast week', 'DATE'),
 ('wednesday', 'DATE'),
 ('week reviewlast week', 'DATE'),
 ('week', 'DATE'),
 ('monday', 'DATE'),
 ('weekend', 'DATE'),
 ('threemonth', 'DATE'),
 ('monday', 'DATE'),
 ('threemonth', 'DATE'),
 ('monday', 'DATE'),
 ('weekend', 'DATE'),
 ('monday', 'DATE'),
 ('weekend', 'DATE'),
 ('sunday', 'DATE'),
 ('one quarter', 'DATE'),
 ('late last week', 'DATE'),
 ('first', 'ORDINAL'),
 ('monday', 'DATE'),
 ('morning', 'TIME'),
 ('today', 'DATE'),
 ('offabout quarter', 'DATE'),
 ('week', 'DATE'),
 ('wednesday', 'DATE'),
 ('wednesday', 'DATE'),
 ('saturday', 'DATE'),
 ('third', 'ORDINAL'),
 ('sunday', 'DATE'),
 ('sunday', 'DATE'),
 ('sunday', 'DATE'),
 ('sunday', 'DATE'),
 ('sunday', 'DATE'),
 ('friday', 'DATE'),
 ('sunday', 'DATE'),
 ('sunday', 'DATE'),
 ('thursday', 'DATE'),
 ('monday', 'DATE'),
 ('monday', 'DATE'),
 ('monday', 'DATE'),
 ('sunday', 'DATE'),
 ('california', 'GPE'),
 ('morning', 'TIME'),
 ('two', 'CARDINAL'),
 ('overnight', 'TIME'),
 ('half million', 'CARDINAL'),
 ('friday', 'DATE'),
 ('wednesday', 'DATE'),
 ('first', 'ORDINAL'),
 ('six month', 'DATE'),
 ('one', 'CARDINAL'),
 ('first', 'ORDINAL'),
 ('july', 'DATE'),
 ('million', 'CARDINAL'),
 ('friday lowest week', 'DATE'),
 ('friday lowest week', 'DATE'),
 ('saturday', 'DATE'),
 ('next week', 'DATE'),
 ('wednesday', 'DATE'),
 ('first', 'ORDINAL'),
 ('april', 'DATE'),
 ('monday', 'DATE'),
 ('week', 'DATE'),
 ('april', 'DATE'),
 ('first time week', 'DATE'),
 ('first', 'ORDINAL'),
 ('sunday', 'DATE'),
 ('friday', 'DATE'),
 ('weekly', 'DATE'),
 ('month', 'DATE'),
 ('wednesday', 'DATE'),
 ('past day', 'DATE'),
 ('two week', 'DATE'),
 ('second', 'ORDINAL'),
 ('eth', 'CARDINAL'),
 ('sunday', 'DATE'),
 ('wednesday', 'DATE'),
 ('tuesday', 'DATE'),
 ('one dollar', 'MONEY'),
 ('tuesday', 'DATE'),
 ('april', 'DATE'),
 ('wednesday', 'DATE')]
 
**ETH:**<br>
[('one', 'CARDINAL'),
 ('today', 'DATE'),
 ('first', 'ORDINAL'),
 ('first', 'ORDINAL'),
 ('three', 'CARDINAL'),
 ('wednesdays', 'DATE'),
 ('late last week', 'DATE'),
 ('thursday', 'DATE'),
 ('immensely past year', 'DATE'),
 ('summer', 'DATE'),
 ('yesterday', 'DATE')]
