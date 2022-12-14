Auction System

How to use:

1.Python 2.7
2.Run the unit tests coverage run -m unittest discover test or the full scenario python test.py

-The system supports the following operations:
1. An object that can be auctioned is added by the auctioneer. An object has a specific name and a set price.
2. An object is put up for auction by the auctioneer.
3. Participants place bids in an auction; a new bid must be more than the previous highest bid in order to consider.
4. When the auctioneer decides on her own that no new higher bids will be submitted, the auction is considered closed. The auction is viewed as a success if the current highest bid exceeds the item's reserve price; otherwise, it is labelled as a failure. The item should no longer be up for sale in the future.
5. Participant/Auctioneer queries the latest action of an item by item name. The library should return the status of the auction if there is any, if the item is sold, it should return the information regarding the price sold and to whom it was sold to.
