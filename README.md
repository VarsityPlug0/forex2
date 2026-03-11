# Forex Trading Education & Community Platform

A professional web application for Forex education, community building, and PAMM trading groups.

## 🎯 Project Overview

This platform provides a complete ecosystem for:
- **Free Forex Education** - Structured learning modules
- **Trading Community** - Forums, discussions, and networking
- **PAMM Investment** - Managed trading groups with performance tracking
- **Market Insights** - SEO-optimized blog with AdSense monetization

## 🏗️ Architecture

### Tech Stack
- **Frontend**: Next.js 14 with React, TypeScript, Tailwind CSS
- **Backend Options**:
  - Node.js/Express with PostgreSQL & Sequelize
  - Python FastAPI with SQLAlchemy & Alembic
- **Database**: PostgreSQL with UUID extension
- **Authentication**: JWT with OAuth 2.0 support
- **Caching**: Redis for performance
- **Deployment**: Docker, Docker Compose, Nginx reverse proxy
- **Charts**: TradingView Lightweight Charts
- **Analytics**: Google Analytics + AdSense ready

## 📁 Project Structure

```
forex-trading-platform/
├── database/           # PostgreSQL schema and migrations
├── backend/
│   ├── nodejs/        # Node.js/Express API
│   └── python/        # Python FastAPI API
├── frontend/          # Next.js application
├── deployment/        # Docker, Nginx configs
└── docs/             # Documentation
```

## 🗄️ Database Schema

Key tables:
- `users` & `user_profiles` - User management
- `courses`, `lessons`, `user_progress` - Learning academy
- `blog_posts`, `blog_categories` - Market insights
- `pamm_groups`, `pamm_performance`, `investments` - PAMM trading
- `daily_trades` - Trade tracking
- `community_channels`, `forum_topics` - Community features
- `ad_placements`, `affiliate_links` - Monetization

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- Node.js 18+ (for Node.js backend)
- Python 3.11+ (for Python backend)

### Development

1. **Clone and setup:**
```bash
git clone <repository-url>
cd forex-trading-platform
```

2. **Start with Docker:**
```bash
cd deployment
docker-compose up -d
```

3. **Access services:**
- Frontend: http://localhost:3000
- Node.js API: http://localhost:3001
- Python API: http://localhost:8000
- Adminer (DB): http://localhost:8080

## 📱 Website Structure

### 1. Home Page
- Hero section with mission statement
- CTA buttons for learning, community, PAMM
- Quick stats dashboard
- Latest trade breakdowns
- Testimonials

### 2. Free Trading Academy
7 structured modules:
1. Market Foundations
2. Supply & Demand
3. Order Flow
4. Market Structure
5. Risk Management
6. Trading Psychology
7. Strategy Development

### 3. Blog / Market Insights
- SEO-focused articles
- Google AdSense placements
- Categories and search
- Comments section

### 4. PAMM Investment Section
- Scalping, Swing, Hedge groups
- Performance statistics
- Historical charts
- Onboarding guide

### 5. Member Dashboard
- Investment tracking
- Daily trading reports
- Profit/Loss analysis
- Private community access

### 6. Community Integration
- Telegram/Discord links
- Live discussion areas
- Forum with categories

### 7. Admin Panel
- Content management
- User management
- Performance updates
- Announcements

## 🔒 Security Features

- JWT authentication with refresh tokens
- Rate limiting and request throttling
- SQL injection prevention
- XSS protection
- CSRF protection
- Secure password hashing (bcrypt)
- HTTPS enforcement
- CORS configuration

## 💰 Monetization

- Google AdSense placements
- Affiliate broker links
- Performance fees (PAMM)
- Premium content (future)
- Sponsored content

## 🎨 Design Principles

- Modern fintech aesthetic
- Dark/light mode support
- Mobile-first responsive design
- Fast loading (<3s)
- Accessibility compliant (WCAG 2.1)
- Professional trading platform feel

## 📈 Scalability Features

- Microservices ready architecture
- Horizontal scaling support
- Database connection pooling
- Redis caching layer
- CDN integration ready
- Load balancer ready
- Monitoring and logging

## 🛠️ Development

### Backend (Node.js)
```bash
cd backend/nodejs
npm install
npm run dev
```

### Backend (Python)
```bash
cd backend/python
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### Frontend
```bash
cd frontend/nextjs
npm install
npm run dev
```

## 📊 Performance Optimization

- Image optimization with Next.js Image
- Code splitting and lazy loading
- Database indexing
- Query optimization
- CDN for static assets
- Service worker for PWA
- Compression (Gzip/Brotli)

## 🔧 Environment Variables

See `.env.example` files in each service directory for required configuration.

## 📄 License

MIT License - see LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please read CONTRIBUTING.md for guidelines.

## 📞 Support

For support, email support@forextradingplatform.com or join our community channels.
