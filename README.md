Customer data - ['customer_id', 'customer_unique_id', 'customer_zip_code_prefix', 'customer_city', 'customer_state']

Geolocation data - ['geolocation_zip_code_prefix', 'geolocation_lat', 'geolocation_lng', 'geolocation_city', 'geolocation_state']

Order Items - ['order_id', 'order_item_id', 'product_id', 'seller_id', 'shipping_limit_date', 'price', 'freight_value']

Order Payments - ['order_id', 'payment_sequential', 'payment_type', 'payment_installments', 'payment_value']

Order Reviews - ['review_id', 'order_id', 'review_score', 'review_comment_title', 'review_comment_message', 'review_creation_date', 'review_answer_timestamp']

Orders - ['order_id', 'customer_id', 'order_status', 'order_purchase_timestamp', 'order_approved_at', 'order_delivered_carrier_date', 'order_delivered_customer_date', 'order_estimated_delivery_date']

Products - ['product_id', 'product_category_name', 'product_name_lenght', 'product_description_lenght', 'product_photos_qty', 'product_weight_g', 'product_length_cm', 'product_height_cm', 'product_width_cm']

Sellers - ['seller_id', 'seller_zip_code_prefix', 'seller_city', 'seller_state']


1. First join customer and geolocation data and then check if the city, state are compatible.
2. Join orders by order id
3. To that join product, customer and seller data
4. Analyze zip, city, state 

Predict the customer review after the end of receiving the product

Predict the customer review after the end of the user journey

Predict the customer review while customer is still in the user journey


