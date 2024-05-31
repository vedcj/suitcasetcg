# Suitcase TCG
## version 0.11.0
## Project started: Feb. 8, 2024

# Features :
- Check prices from the ff. sources:
  - Yuyu-tei
  - Big web
  - TCG Corner
- Price conversion to local price.
- Batch search for card prices.
- Search for English name and display it.
- View Card Info from search results.
- Full card image display.
- Auto-update of App.

# Task List :
- View Card Info from search results.
  - Proper caching of data.
    - Monster race.
  - Display sets on card info dialog.
- Inventory: (ongoing)
  - Display list of card items after clicking folder.
  - Allow editing of Folder info.
    - Name change.
    - Delete folder.
    - Change background image.
  - Add option on Search result items to add to folder.
    - Add button on Search result item.
    - Display all existing folder on selection.
- Option to delete entry on Search result / Inventory.
- Search history cache and load into input box.

# Known Bugs
- TCG Corner does not display search results for products with no stock.
- UI on Search freezes sometimes when using batch search.

# Needs server
- User login.
- Display inventory cards to others for selling/trading.
- Trade calculator.

# Low Prio
- Rulings and FAQs from ``db.ygorganization.com``.
- Price recommendation from Default market.
- Small World resolver.
- Duel companion app (Check LP, Roll dice, Timer, Counters).
