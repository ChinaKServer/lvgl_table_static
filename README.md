# lvgl_table_static
LVGL V8.1 lv_table Static text variable support, and fixed lv_table memory leak

## Enable static text variable support
```
#define LV_TABLE_USE_STATICTEXT 1
```
## Call in program
be similar to > lv_label_set_txt_static
```
lv_table_set_cell_value_static(obj, row, col, txt);
```
