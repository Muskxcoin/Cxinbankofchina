# Cxinbankofchina
Modern online banking platform with a red and white theme, multilingual support, secure login system, user dashboard, and transaction features — built for deployment on Vercel with NeonDB backend.
# Clone the repo
git clone https://github.com/YOUR_USERNAME/Cxcoinbankofchina.git

# Install dependencies
cd frontend && npm install
cd ../backend && npm install

# Setup DB (example)
npx prisma migrate dev

# Run frontend and backend
cd frontend && npm run dev
cd backend && node server.js
---

## ⚙️ Environment Variables

Make sure to set these in your Vercel project or `.env` file:

```env
DATABASE_URL=your_neon_connection_url
API_SECRET_KEY=your_custom_api_key
