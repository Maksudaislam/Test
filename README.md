# 🏪 Warehouse E-Commerce Site

A web-based e-commerce platform built using Python-Django with AI-powered chatbot integration.

![Project Preview](screenshots/preview.gif) <!-- Replace with actual screenshots -->

## 👥 Team Member
| Name          | ID      | Role       |
|---------------|---------|------------|
| Maksuda Islam | C231440 | Developer  |

## 🚀 Features
- ✅ **User Authentication** - Secure login/registration system
- ✅ **Product Management** - CRUD operations via Django admin
- ✅ **AI Chatbot** - Real-time product queries with API integration
- ✅ **Dynamic UI** - Owl Carousel product displays
- ✅ **Order Management** - Order placement and tracking
- 🔜 **Secure Payment** - Payment gateway integration (Future)
- 🔍 **Search & Filters** - Advanced product discovery

## 🛠️ Technologies Used
### Backend
- Python-Django
- Django REST Framework

### Frontend
- HTML5/CSS3
- JavaScript (ES6+)
- Owl Carousel 2

### Database
- SQLite (Default)
- PostgreSQL/MySQL (Configurable)

### AI Integration
- Custom chatbot engine
- External API integration

## 📥 Installation
```bash
# Clone repository
git clone https://github.com/your-username/warehouse-ecommerce.git
cd warehouse-ecommerce

# Create virtual environment
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create admin user
python manage.py createsuperuser

# Start server
python manage.py runserver
