# WeatherPWA
- Understanding PWAs
- Working with Manifest
- Working with Service Worker
- Using the CacheStorage API
- Using the Geolocation API
- Using the OpenWeather One Call API
- Create a PWA


### Getting API key from httsp://openweathermap.org

## Benefit of PWA
- Push Notification
- Installation, starting the app from Start menu
- No need to distribute to iOS App
- Can be launched offline

## Need to use HTTPS, need SSL certificate. Great source for SSL certificate is : https://letsencrypt.org

#### Manifest File
#### Service Workers
- A Javascript file working offline for PWA
- It controls how the web browser htndles its network requests and asset caching
- able to caching
- Background syncing
- Push Notification
- It intercepts and mofifies navigation and resource requests
- It has full control of what resouces are cached
- And run in background and run on different thread, no blocking, fully asynchronous
- Has no DOM access

### Service workers life cycle:
- Install: cache the static assets of the website. if successfully then next cycle
- Activate: handle management of the OLD Caches, and delete old ones, then next step
- Fetch: Contrl all the pages fall under its scopes and network request is made from PWA until it is terminated

### Generate sizes of the same image : Imagne Generator tool on PWABuilder at https://www.pwabuilder.com/generate
