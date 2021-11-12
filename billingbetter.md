```
cd ~/Repository/billingbetter
cd ~/Repository/Partner-Portal
sudo docker-compose up -d

nvm use 14.18.1

docker-compose exec billing_better_php_runtime php artisan db:seed --class=SupplierBillsProviderSeeder
```
