# CoffeeShop

## 📹 Video Demo
[![Watch the video](https://img.youtube.com/vi/UcSv7VyaxGg/maxresdefault.jpg)](https://www.youtube.com/watch?v=UcSv7VyaxGg)


## 🌟 Website Features

### For Users:
- Login
- Password recovery

### For Customers:
- All user functionalities
- Registration
- Search for products
- View product details
- Add products to the cart and make payments (via cash on delivery or online payment using VNPay)
- Track order status and cancel orders
- Review products
- Send messages to administrators

### For Administrators:
- All user functionalities
- Manage customer accounts
- Manage products (CRUD products)
- Manage product categories (CRUD categories)
- Manage product brands (CRUD brands)
- Manage orders (update order status, cancel orders)
- View revenue statistics
- Respond to customer messages

---

## 🛠 How to Run the System

### Prerequisites
- **Java**: OpenJDK 17
- **Node.js**: Version v20.13.1
- **Maven**: Version 3.9.6
- **MySQL** (or any other relational database)
- **VNPay Account** (for payment integration)

### Backend (Spring Boot)
1. Open the backend folder in **IntelliJ IDEA**
2. Update the `application.properties` file in `src/main/resources` with your database configuration:
   ```properties
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```
3. Update the `application.properties` file with your VNPay configuration:
   ```properties
   vnp.tmnCode=your_tmnCode
   vnp.hashSecret=your_hashSecret
   vnp.returnUrl=http://localhost:8080/api/v1/payment/vnpay/ipn
   ```
4. Run the `CoffeeShopApplication` class
5. The backend will be accessible at **http://localhost:8080**

### Frontend (ReactJS)
1. Open the frontend folder in **Visual Studio Code**
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend:
   ```sh
   npm start
   ```
4. The frontend will be accessible at **http://localhost:3000**

### 🛑 Administrator Login Credentials
- **Username**: `admin@gmail.com`
- **Password**: `12345678@`

---

## 🎉 Special Thanks
We would like to extend our deepest gratitude to **Ms. Trịnh Thị Vân Anh** for her guidance and support throughout this project. This work was successfully completed by **Group 3**, which includes the following members:

### 👥 Group Members:
- **Nguyễn Phú Tâm** (It's me) 🎉
- **Cao Quang Thức**
- **Nguyễn Đắc Trường**

