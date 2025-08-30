# Fix 2 - Missing Parameter
Issue: Event fires but no item_name appears.
Cause: dataLayer.push missing "item_name".
Solution: Add {item_name: "Demo Product"} to dataLayer push.
