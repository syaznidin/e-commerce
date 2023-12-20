## RUNNING
1. Install Jetstream by running:
   <br>`php artisan jetstream:install livewire`<br>
2. Next run:
   <br>`npm install`<br>
3. Start the development server:
   <br>`npm run dev`<br>

4. Add these lines into database/migrations/<DATE>_000000_create_users_table.php at line 18
   <br>`$table->string('usertype')->default(0);`
   <br>`$table->string('phone')->nullable();`<br>
   `$table->string('address')->nullable();
   `<br>
5. Migrate the database by running:
   <br>`php artisan migrate`<br>

6. Run the server by running:<br>
   `php artisan serve`
