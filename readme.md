# ProShop eCommerce Platform (v2)

<img src="./frontend/public/images/screens.png">

### Env Variables

Rename the `.env.example` file to `.env`

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```

# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@email.com (Admin)
123456

john@email.com (Customer)
123456

jane@email.com (Customer)
123456
```

---

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

- Create a PayPal account and obtain your `Client ID` - [PayPal Developer](https://developer.paypal.com/)
