# DealFinder for AutoTempest

## Install in Chrome

1. Extract the **DealFinder-extension.zip** archive to a folder you will keep, or use the supplied **DealFinder-extension** folder directly.
2. Open **chrome://extensions** in Chrome.
3. Turn on **Developer mode** in the upper-right corner.
4. Choose **Load unpacked**, then select the folder that directly contains **manifest.json**.
5. Pin DealFinder from Chrome’s puzzle-piece Extensions menu.

Chrome 116 or newer is required. No account or API key is needed. Unpacked extensions must stay in their extracted folder; moving or deleting it will break the installation.

## Use it

1. Run your search on **autotempest.com**, choosing the sources, distance and beyond-distance option you want.
2. Click DealFinder’s toolbar icon. Its sidebar collects the results, loading additional batches through the page’s normal controls. Keep the source tab open while it collects. Rankings are provisional until collection finishes.
3. Use **Preference fit** to adjust price, mileage and listing-age priorities, or **Relative value** to compare asking prices against similar cars in the search.
4. Expand **Refine results**, the chart, or a car’s score for more detail. Select a chart point to find its card in DealFinder.
5. Compare compact cards with a photo thumbnail, a large score, and the title, price, mileage and listing age grouped together. Scores and the card order update immediately as you move preference sliders.
6. Choose **Show on page** to focus and highlight the original car, or **Open listing** to follow the exact outgoing link AutoTempest provided.
7. Bookmark cars to keep their links and details in **Saved**. Choose the large score’s **Details** control to reveal the seller, location, VIN and score breakdown. Click a VIN to search it on Google, which can help locate the dealer’s own advertisement. A VIN search does not guarantee a dealer result.

The sidebar stays with its analyzed search while you inspect other tabs. Choose **Analyze this tab** to switch searches. **Refresh** rescans the connected source search; if that tab was closed, it opens the saved search and asks you to analyze it once loaded.

## Corrections and saved results

Expand a score, then choose **Correct details** to fix a missing field or parsing mistake. Price, mileage, date, model, body style and VIN corrections are stored separately from captured values. Use **Reset to captured values** to undo them. Hidden cars can be restored using the control above the matches.

Settings, bookmarks and search snapshots stay in this Chrome profile on this device. Search results restored after a browser restart are marked as snapshots until refreshed. Bookmarks retain their saved values; their prices are not automatically monitored. Removing the extension removes its local data. Nothing is synchronized across devices.

## Understanding the rankings

- **Preference fit** is relative to eligible cars collected in the search. Lower price and mileage score higher. Older listings earn age points up to 90 days; unknown age is neutral. This does not predict negotiating success.
- **Relative value** estimates asking prices using year and mileage. At least 12 comparable cars use a robust model; 5–11 use the median of nearby cars. Fewer than five means no estimate. Broader groups, unknown details and larger validation errors lower confidence.
- Known different body styles are kept separate. Known branded-title cars are flagged and excluded from valuation. An unflagged car’s title status is **unknown**, not verified clean.
- Estimates come only from this search, exclude the car being evaluated, and may miss differences in condition, history, generation, options, location and fees. Confirm details on the source listing.
- Sidebar filters do not change the comparison pool. Corrections and hiding a car do change it.
- Auctions are excluded. DealFinder reads AutoTempest’s listing cards; it does not collect from the external “Compare Other Sites” searches or automatically visit dealer sites.

## If collection stalls

Partial results remain available. Resolve any page loading issue, then choose **Refresh**. If you change AutoTempest’s sources, sort, filters or distance, refresh the analysis. If you installed or reloaded DealFinder while a search tab was already open, reload that AutoTempest tab once so the collector can connect.

AutoTempest may change its page layout. Missing data remains marked unavailable and can be corrected manually; a stalled collection is not labeled complete.

## Privacy and permissions

Page access is restricted to AutoTempest. The extension uses Chrome’s side panel, local storage, and active-tab access. Analysis runs locally with bundled code. No telemetry, login, AI service, backend, or external pricing API is used. Collection uses the page’s normal loading controls. Photo thumbnails load from the image URLs already supplied by each listing, with the original photo as a fallback. Missing or expired images show a placeholder. Opening a listing visits its source website; clicking a VIN sends that VIN to Google as a search query.

## Updating

Replace the files in the same extension folder, open **chrome://extensions**, and click DealFinder’s **Reload** button. Then reload any open AutoTempest search tabs. Keep the folder path unchanged to retain the same unpacked extension identity and saved data.

After updating to **1.1.0**, choose **Refresh** in DealFinder to collect photo URLs for an existing search. Old saved searches and bookmarks remain usable; records collected before photos were added show a placeholder until that car is collected again.
