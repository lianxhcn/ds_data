
## 淘宝用户消费数据

- Source: <https://tianchi.aliyun.com/dataset/221264>  
- Raw Data: **淘宝用户消费数据汇总.zip**, 2026-03-05, 1.08MB
- 描述：淘宝用户消费数据汇总，包括 用户基本信息 商品信息 用户行为数据 订单数据 用户特征(随机森林用) 商品特征 
- 注：
  - 用户行为数据：浏览、点击、收藏、加购四种行为 
  - 订单状态：模拟了完整的订单生命周期（待付款→已付款→已发货→已收货→已完成）
  - 复购标签：repurchase_indicator 可直接作为随机森林分类目标变量 
  - 购买意向：purchase_intent 可作为回归目标进行预测

## 数据清单：
  - `orders.csv`
    - order_id,user_id,product_id,quantity,order_date,order_status,payment_method,unit_price,total_amount,discount,actual_payment,delivery_date,receive_date,review_score,review_content
  - `users.csv`
    - user_id,age,gender,province,city,registration_date,member_level,account_balance,credit_score
  - `user_features.csv`
    - user_id,total_spent,order_count,completed_orders,avg_order_amount,browse_count,click_count,favorite_count,cart_count,days_since_last_order,order_frequency,repurchase_indicator,purchase_intent,consumption_level,member_level_score
  - `user_behaviors.csv`
    - behavior_id,user_id,product_id,behavior_type,behavior_time,duration_seconds
  - `products.csv`
    - product_id,product_name,category,brand,price,sales_count
  - `product_features.csv`
    - product_id,total_revenue,total_sales,completed_count,cancel_count,加购_count,收藏_count,浏览_count,点击_count,conversion_rate,avg_review_score,popularity_score

### 数据关系

::: {.callout-tip}
### 提示词

:::





