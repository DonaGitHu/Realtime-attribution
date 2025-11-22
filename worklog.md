Day 0:
- Explored GA4 sample dataset in BigQuery.
- Created GitHub repo.
- Sketched initial architecture idea.
  
Day 1:
- Explored GA4 BigQuery dataset and went through different tables 
- Ran initial queries: event count, event_name frequency event parameters
- Understood event_params structure and UNNEST
- Tried various sql queries
- Selected dataset: bigquery-public-data.ga4_obfuscated_sample_ecommerce

Day 2: Event Parameters & Items Exploration (GA4 BigQuery)
-Queried GA4 sample dataset to explore product-level data.
-Learned how to UNNEST the items array to get product attributes.
-Extracted item_name, price, quantity from commerce events.
-Counted view_item events by product.
-Counted add_to_cart events and grouped them by item.
-Compared event_params (key-value pairs) vs items (structured fields).

Queries completed:
-Item-level view events
-Add-to-cart analysis
-Extracting product attributes
-Listing available item fields

Learning:
-event_params = key-value array → requires UNNEST(event_params)
-items[] = structured product array → requires UNNEST(items)
-GA4 events can contain multiple items in a single row
  
