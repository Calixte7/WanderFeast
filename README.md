# WanderFeast

A modern trip and date night planner with intelligent recommendations and random selection features.

## Features

**Trip Planner **
- Multi-day itinerary generator
- Transportation mode filters
- Sightseeing spot recommendations
- Budget-conscious planning

**Date Night Planner **
- Restaurant randomizer with filters:
  - Cuisine type
  - Price range ($-$$$$)
  - Minimum rating (1-5 stars)
  - Ambiance preferences
- AI-powered pairing suggestions
- Collaborative filtering for couples

**Core Functionality **
- Location-based search
- Dynamic filtering system
- "Surprise Me!" random selection
- Responsive UI with tabbed interface

## Tech Stack

**Backend**
- Django 4.2+
- Django REST Framework
- PostgreSQL (with PostGIS)
- Redis (caching)
- Celery (background tasks)

**Frontend**
- React 18+
- React Bootstrap
- Axios (API calls)
- React Router
- Mapbox/Google Maps Integration

**Services**
- Google Places API
- OpenWeather API
- JWT Authentication

## Installation 🛠️

### Prerequisites
- Python 3.9+
- Node.js 16+
- PostgreSQL 12+
- Redis 6+

### Backend Setup
```bash
# Clone repository
git clone https://github.com/yourusername/wanderfeast.git
cd wanderfeast/backend

# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Database setup
python manage.py migrate
python manage.py createsuperuser
