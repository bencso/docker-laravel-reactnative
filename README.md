# Laravel + React Native Docker Setup 🐳⚙️

> Docker konfiguráció Laravel backend és React Native frontend alkalmazáshoz

## 🎯 Projekt célja

Ez a repository egy kísérleti Docker környezet beállítását tartalmazza Laravel és React Native alkalmazásokhoz. A cél egy konténerizált fejlesztői környezet létrehozása, amely megkönnyíti a lokális fejlesztést és a későbbi deployment folyamatot.

## 📦 Tartalom

A projekt Docker konfigurációkat tartalmaz:
- **Laravel backend** - PHP-alapú backend API
- **React Native frontend** - Modern frontend alkalmazás
- **PostgreSQL** - Adatbázis konfiguráció
- **Nginx** - Webszerver

## 🛠️ Fájlok

- `Dockerfile.laravel` - Laravel konténer konfiguráció
- `Dockerfile.react` - React Native konténer konfiguráció
- `docker-compose.yml` - Szolgáltatások
- `nginx.conf` - Nginx webszerver beállítások
- `postgresql.conf` - PostgreSQL adatbázis konfiguráció
- `.env.example` - Környezeti változók sablon

## 🚀 Használat

```bash
# Projekt klónozása
git clone https://github.com/bencso/laravel-react-docker.git
cd docker-laravel-reactnative

# Környezeti változók beállítása
cp .env.example .env

# Konténerek indítása
docker-compose up -d

# Konténerek leállítása
docker-compose down
```

## 💡 Funkciók

- 🐳 **Docker Compose** - Egyszerű multi-container
- 🔄 **Hot Reload** - Automatikus újratöltés fejlesztés közben
- 🗄️ **PostgreSQL** - Modern relációs adatbázis
- 🌐 **Nginx** - Hatékony webszerver

## 🎓 Tanulási célok

A projekt során gyakoroltam:
- Docker és Docker Compose használatát
- Multi-container alkalmazások konfigurálását
- Nginx beállítását
- Laravel és React Native konténerizálását
- PostgreSQL beállítást

## 📄 Dokumentáció

- `NGINX.md` - Nginx konfiguráció részletesebb leírása

## 📄 Licensz

MIT License - Szabadon használható és módosítható

***

**Státusz:** 🧪 Kísérleti / Tanulási projekt

***

## 💭 Megjegyzések

Ez egy gyakorló projekt, amelyben a Docker konténerizációt és a Laravel + React Native stack összeállítását próbáltam ki. A konfiguráció kiindulási alapként szolgálhat hasonló projektekhez.

***

**⭐ Ha tetszik a projekt, örülök egy csillagnak!**
