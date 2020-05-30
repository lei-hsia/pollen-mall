数据库分库分表，并且不使用外键;

### oms:

| 表             |
| --- |
| oms_order                 |
| oms_order_item            |
| oms_order_operate_history |
| oms_order_return_apply    |
| oms_order_return_reason   |
| oms_order_setting         |
| oms_payment_info          |
| oms_refund_info 

### pms:

|  表|
| --- |
| pms_attr                    | 
| pms_attr_attrgroup_relation |
| pms_attr_group              |
| pms_brand                   |
| pms_category                |
| pms_comment_replay          |
| pms_product_attr_value      |
| pms_sku_images              |
| pms_sku_info                |
| pms_sku_sale_attr_value     |
| pms_spu_comment             |
| pms_spu_images              |
| pms_spu_info                |
| pms_spu_info_desc    

### sms: 

s: 营销系统的db; 对应coupon;

| 表                   |
| --- |
| sms_category_bounds              |
| sms_coupon                       |
| sms_coupon_history               |
| sms_coupon_spu_category_relation |
| sms_coupon_spu_relation          |
| sms_home_adv                     |
| sms_home_subject                 |
| sms_home_subject_spu             |
| sms_member_price                 |
| sms_seckill_promotion            |
| sms_seckill_session              |
| sms_seckill_sku_notice           |
| sms_seckill_sku_relation         |
| sms_sku_bounds                   |
| sms_sku_full_reduction           |
| sms_sku_ladder                   |
| sms_spu_bounds                   |

### ums

| Tables_in_ums                  |
| --- |
| ums_growth_change_history      |
| ums_integration_change_history |
| ums_member                     |
| ums_member_collect_spu         |
| ums_member_collect_subject     |
| ums_member_level               |
| ums_member_login_log           |
| ums_member_receive_address     |
| ums_member_statistics_info     |

### wms

| Tables_in_wms              |
| --- |
| wms_purchase               |
| wms_purchase_detail        |
| wms_ware_info              |
| wms_ware_order_task        |
| wms_ware_order_task_detail |
| wms_ware_sku               |
