## Safety Check in Online Bid System

### Introduction

In online bidding the major challenge is differentiating between human and machine/bot bidders. To have a fair auction we need to eliminate bot bidders. The goal of this project is to identify bots using the provided data sets about bidding and bidder information. By analyzing and recognizing the patterns between the bids conducted by bots we can identify the false auctions and inform the host.

Dataset used: https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/data


### Attributes
- bidder_id: Unique identity of a bidder.
- payment_account: Account associated with the bidder, to protect privacy this is obfuscated.
- address: Mailing address of a bidder, to protect private this is obfuscated.
- outcome: Label of a bidder indicating whether or not it is a robot. Value 1.0 indicates a robot and 0.0 indicates a human.

### Features
- bids_PerAuction: mean number of user's bids in an auction.
pbots_per_device: Proportion of bots.​
- ipToBids_Ratio: Number of unique IP addresses to the number of bids ratio.​
- ip_entropy: The entropy for how many IPs a bidder used.
auctionUrl_entropy: The entropy for how many URLs a bidder was referred from.
- Timediffs: Meantime for a user’s bid and the user’s previous bid.

### Models Built
1. Logistic Regression - Accuracy achieved: 0.85
2. Random Forest - Accuract achieved: 0.91
3. Gradient Boosting - Accuracy achieved: 0.92

### Contributors
- Saloni Punjabi 
- Tejas Kale 
- Mohit Patil 
- Rajendra Shivaraya 
- Sharat Patangi 



