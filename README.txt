Wearwise PWA update: multi-day wear tracking + individual item controls

Upload index.html, manifest.json, sw.js, icon-192.png, icon-512.png, and README.txt to the root of your existing GitHub Pages repository, replacing the old versions. The service-worker cache was bumped to v3.

Existing localStorage key is preserved. Keep/export a compact JSON backup before replacing files.

Default wears before washing: underwear/socks 1; tops 1; pants/jeans 3; shorts 2; hoodies/sweaters 4; jackets 5; shoes 7; other 2. Set each item to 1–10 wears in My clothes. These are editable defaults. Mark an item worn individually, or tap I wore this to record all pieces in an outfit. Items only move to laundry at their limit. Mark washed resets the wear count.