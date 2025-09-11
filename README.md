# 🖼️ Text-to-Image Generator (SaaS App)

A full-stack **Text-to-Image Generator** built with **React (Vite + Tailwind)**, **Node.js (Express)**, **MongoDB (Mongoose)**, and integrated with **ClipDrop API**, **Razorpay**, and **Stripe** for payments.

---

## 🚀 Features
- 🔐 User authentication (Register/Login with JWT & bcrypt)
- 🖌️ AI-powered text-to-image generation (ClipDrop API)
- 💳 Payments via Razorpay & Stripe
- 📦 SaaS-ready boilerplate (separate client & server)
- 🗄️ MongoDB database integration
- 🎨 Styled with TailwindCSS

---


---

## ⚙️ Installation

### 1. Clone the repo
```bash
git clone https://github.com/your-username/text-to-image-generator.git
cd text-to-image-generator
```
### Setup Backend
```bash 
cd server
npm install
```

#### Create a .env file inside server/:
```
PORT=5000
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net 
DB_NAME=ai-image
JWT_SECRET=your_jwt_secret
CLIPDROP_API=your_clipdrop_api_key
STRIPE_SECRET_KEY=your_stripe_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
```
#### Start Backend
```
npm run dev
```

#### Setup Frontend
```
cd ../client
npm install
npm run dev
```
## 🖼️ Usage

### 1. Register / Login
- Create a new account or log in with your existing credentials.

### 2. Enter a Text Prompt
- Type any description (e.g., *"a futuristic city at sunset with flying cars"*).

### 3. Generate AI Images
- Click **Generate** → The app will call the **ClipDrop API** and return an image.

### 4. Payments (Optional for Premium Features)
- Use **Razorpay** or **Stripe** checkout for unlocking premium features such as:
  - Higher resolution images
  - Unlimited generations
  - Priority processing

### 5. View & Download
- Preview generated images in the gallery.
- Download and save locally.

## 🔑 Environment Variables

Create a `.env` file inside the `server/` directory and add the following:

| Variable            | Description                          |
|---------------------|--------------------------------------|
| `PORT`              | Server port (default: 5000)          |
| `MONGODB_URI`       | MongoDB connection string            |
| `DB_NAME`           | MongoDB database name                |
| `JWT_SECRET`        | Secret key for JWT authentication    |
| `CLIPDROP_API`      | API key for ClipDrop                 |
| `STRIPE_SECRET_KEY` | Stripe API secret key                |
| `RAZORPAY_KEY_ID`   | Razorpay public key                  |
| `RAZORPAY_KEY_SECRET` | Razorpay secret key               |


## 🛠️ Tech Stack

**Frontend**
- React (Vite)
- TailwindCSS

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose

**Authentication**
- JWT
- bcrypt.js

**Payments**
- Stripe
- Razorpay

**AI API**
- ClipDrop API







