# Chilean unrest dataset

This repository contains a collection of Spanish messages collected during the 2019 [Chilean unrest movement](https://en.wikipedia.org/wiki/2019%E2%80%932022_Chilean_protests). The collection includes data published between October 19 and November 30 in 2019. 

The data folder contains the following files:

- **20191019-20191201_retweets_network_ids.csv**: this file contains the user retweet network that is described by the columns `source` and `target`. Both variables represent who retweeted a message and who published the original message, respectively.
- **20191019-20191201_tweets_ids.csv**: this file contains the original tweets published during the event. The dataset only contains the `tweet` and `user` ids. If you need to retrieve the full metadata, please consider using the [twarc library](https://github.com/DocNow/twarc).

Furthermore, our repository contains the complete visualization and results in the *results* folder.


## References
<a id="1">[1]</a> 
H. Sarmiento,  F. Bravo-Marquez, E. Graells-Garrido, B. Poblete (2022). 
**Identifying and Characterizing new Expressions of Community Framing during Polarization**. 
In Proceedings of the 16th The International AAAI Conference on Web and Social Media (ICWSM), Atlanta, Georgia, USA.
