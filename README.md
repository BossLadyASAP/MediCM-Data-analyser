# Flask Configuration
FLASK_ENV=development
FLASK_APP=app.py
SECRET_KEY=your-secret-key-here
DEBUG=True

# JWT Configuration
JWT_SECRET_KEY=your-jwt-secret-key-here

# Database
DATABASE_URL=sqlite:///medicm.db
# For MySQL: mysql+pymysql://user:password@localhost/medicm
# For PostgreSQL: postgresql://user:password@localhost/medicm

# CORS
CORS_ORIGINS=http://localhost:3000,http://localhost:5173,http://localhost:5000

# Server
HOST=0.0.0.0
PORT=5000
