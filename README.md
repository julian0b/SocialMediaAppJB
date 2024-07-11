
```
php artisan setup
```
or
```
php artisan migrate --seed
```

- Install all dependencies via `npm` or `yarn` and Compile all assets based on your deployment environment. 

#### Yarn (recommended)
```bash
#Install all dependencies
yarn

#Development
yarn dev

#Production
yarn prod
```

#### Npm
```bash
#Install all dependencies
npm install

#Development
npm dev

#Production
npm prod
```

- Create symbolic link 
```
php artisan storage:link
```

- Start the local server using the command
```
php artisan serve
```

### Current Admin Credentials

You may use these credentials to log into your website. you can change these credentials shortly after logging in.

**Email** : admin@gmail.com<br>
**Password** : password


## Generating Dummy Data

Creates dummy data using faker library.
```
php artisan setup:dummy
```
or 
```
php artisan db:seed --class="DummyDataSeeder"
```

## Clear Temporary Files
All files uploaded from Create Post form is stored on storage/app/livewire-tmp folder. The following command cleana all Temporary Files from server.
```
php artisan clean:temp
```

## Tests

```bash
php artisan test
```
## Credits

- [@albinvar](https://github.com/albinvar)

## License

[MIT](LICENSE) © Albin Varghese
