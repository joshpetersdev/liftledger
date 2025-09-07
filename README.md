# LiftLedger Backend

This is the backend service for LiftLedger applications.

## 🚀 Features
- Create workouts

## 🗺️ API Routes
| Method | Endpoint | Description
| --- | --- | --- |
| `GET`  | `/health` | Checks the status of the server |
| `GET`  | `/workouts/{id}` | Retrieve a workout by ID |
| `POST` | `/workouts` | Create a workout |

## 🔒 Authentication
🚧 Under construction

## 🧪 Testing
🚧 Under construction

## 🐳 Docker Setup
This project uses Docker Compose to run PostgreSQL databases for both development and testing.
### 📦 Services
- db - Main development database (listens on port 5432)
- test_db - Separate testing database (listens on port 5433)
Default credentials for both:
```bash
username: postgres 
password: postgres
database: postgres
```
### Start the Container
```bash
docker-compose up -d 
```
This will start the `db` and `test_db` in the background.
### Stop the Container
```bash
docker-compose down
```
### Connecting to the databases:
```bash
psql -U postgres -h localhost -p 5432
```

## 📚 Future Improvements
- User authentication (Sign up / Sign in)

## ☁️ AWS Technologies
🚧 Under construction
