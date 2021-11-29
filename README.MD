# demo site

https://test-web-site-a.myshopify.com/

password : demo

# git repository

https://github.com/potatowithbutter1987/shopify_demo

# develop

## theme ID 確認

theme get --list -p={api_key} -s=test-web-site-a.myshopify.com

## theme download

theme get -p={api_key} -s=test-web-site-a.myshopify.com -t={theme_id}

## theme settings download

theme download

## theme wath

theme watch --allow-live
