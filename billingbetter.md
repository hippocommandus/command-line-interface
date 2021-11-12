```
cd ~/Repository/billingbetter
nvm use 14.18.1
sudo docker-compose up -d
docker-compose exec billing_better_php_runtime php artisan db:seed --class=SupplierBillsProviderSeeder
```
