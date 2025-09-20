# Data-layer-setup

## DataLayer to Variable Mapping

| DataLayer Field              | Variable Name                   | Example Usage                         |
|-------------------------------|---------------------------------|---------------------------------------|
| `item_category`              | `capi_cat1` / `capi_cat`        | Use `capi_cat` if you need comma-separated list |
| `item_id`                    | `capi_id`                       | Returns numeric IDs, comma-separated  |
| `sku`                        | `capi_sku`                      | Returns numeric SKUs, comma-separated |
| `stocklevel`                 | `capi_stocklevel`               | Returns stock level values            |
| `stockstatus` (same source)  | `capi_stockstatus`              | Returns stock status values           |
| `google_business_vertical`   | `capi_google_business_vertical` | Returns Google Business Vertical(s)   |
| `value`                      | `capi_value`                    | Returns total value                   |
| `currency`                   | `capi_currency`                 | Returns currency (e.g. `USD`, `BDT`)  |
