# Backend Aplikasi WasteApp
Backend merupakan bagian pembuatan API dari aplikasi mobile WasteApp
## API Documentation
#### Register Pengguna Aplikasi Baru

```http
  POST https://backend-banksampah-api.vercel.app/auth/register
```

| Parameter | Type     | 
| :-------- | :------- | 
| `email` | `string` | 
| `password` | `string` | 
| `confirmPassword` | `string` | 
| `username` | `string` | 


#### Login Pengguna

```http
  POST https://backend-banksampah-api.vercel.app/auth/login
```

| Parameter | Type     | 
| :-------- | :------- | 
| `username` | `string` | 
| `password` | `string` | 


#### Mendaftarkan Nasabah Baru

```http
  POST https://backend-banksampah-api.vercel.app/customers
```

| Parameter | Type     | 
| :-------- | :------- | 
| `name` | `string` | 
| `phoneNumber` | `string` | 
| `address` | `string` | 


#### Mendapatkan nama nasabah dari Daftar Nasabah

```http
  GET https://backend-banksampah-api.vercel.app/customers/names
```


#### Input data menabung atau menabung sampah

```http
  POST https://backend-banksampah-api.vercel.app/transactions/deposit
```

| Parameter | Type     | 
| :-------- | :------- | 
| `name` | `string` | 
| `date` | `string` | 
| `deposit` `wateTypeId` | `string` | 



