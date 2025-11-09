---

## ⚙️ Installation Guide

Getting started is super simple! Follow the steps below:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/themeselection/sneat-bootstrap-laravel-livewire-starter-kit.git
   cd sneat-bootstrap-laravel-livewire-starter-kit
   ```

2. **Install Composer Dependencies**
   ```bash
   composer install
   ```

3. **Copy `.env` & Generate App Key**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Configure Database**
   - Open `.env` file and update your DB credentials.

5. **Run Migrations**
   ```bash
   php artisan migrate
   ```

6. **Install Node Modules**
   ```bash
   npm install
   # OR
   yarn
   ```

7. **Build Frontend Assets**
   ```bash
   npm run dev
   # OR
   yarn dev
   ```

8. **Serve the Application**
   ```bash
   php artisan serve
   ```

🚀 Open `http://127.0.0.1:8000` in your browser, and you’re good to go!

---

## 🧑‍💻 Available Commands

**Development Mode (Hot Reload):**

```bash
npm run dev
# OR
yarn dev
```

**Production Build:**

```bash
npm run build
# OR
yarn build
```



---

## 🔥 Looking for More?

Check out other awesome starter kits and templates at [Website](https://themeselection.com/).
