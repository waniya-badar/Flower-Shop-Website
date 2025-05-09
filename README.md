# Flower-Shop-Website
Flower Shop Website - A full-stack web application for online flower shopping, built with PHP, MySQL, HTML/CSS, and JavaScript. Designed for both customers and administrators with secure authentication, product management, and order processing.

### Features
#### User-Facing
- **User Authentication**: Registration, login, and profile management
- **Product Catalog**: Browse/search flowers with filters
- **Shopping Cart**: Add/remove items, quantity adjustment
- **Wishlist**: Save favorite products
- **Order Management**: Checkout and order history
- **Contact Form**: Message submission to admin

#### Admin-Facing
- **Product CRUD**: Add/edit/delete products
- **Order Processing**: Update order statuses
- **User Management**: View registered users
- **Message Dashboard**: Handle customer inquiries

### 🏗 System Architecture
#### 3-Tier Structure
| Layer              | Technologies               |
|--------------------|----------------------------|
| **Presentation**   | HTML5, CSS3, JavaScript    |
| **Business Logic** | PHP (MVC Pattern)          |
| **Data Access**    | MySQL (XAMPP)              |

### Database Design

#### Key Tables
| Table       | Description                          |
|-------------|--------------------------------------|
| `users`     | Customer/admin accounts              |
| `products`  | Flower inventory                     |
| `orders`    | Order transactions                   |
| `cart`      | Temporary cart items                 |
| `wishlist`  | User-saved favorites                 |
| `messages`  | Customer contact submissions         |

#### Risk Management
| Risk ID | Description               | Mitigation Strategy                          |
|---------|---------------------------|----------------------------------------------|
| R001    | Database connection fails | Implement retry logic + fallback connections |
| R002    | Server downtime           | Schedule deployments during off-peak hours   |
| R003    | Data privacy breach       | HTTPS + input sanitization + encryption      |
| R005    | Traffic overload          | Auto-scaling + caching mechanisms            |

#### Installation
##### Prerequisites
- XAMPP (Apache + MySQL)
- PHP
- Modern web browser
