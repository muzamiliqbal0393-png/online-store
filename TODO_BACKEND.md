# Backend plan (for Cart/Checkout) — LUXEMART demo

## Step 1: Create backend project
- Create `backend/` folder
- Add Node.js + Express server (or ask if you prefer PHP/Laravel)

## Step 2: Add endpoints needed for UI
- `POST /api/auth/login`
- `POST /api/auth/signup`
- `GET /api/cart`
- `POST /api/cart/items`
- `PATCH /api/cart/items/:id`
- `DELETE /api/cart/items/:id`
- `POST /api/checkout`
- `POST /api/orders`
- `GET /api/orders/:orderId`

## Step 3: Wire frontend
- Update `test.html`, `checkout.html`, `login.html`, `signup.html` to call APIs instead of localStorage.

## Step 4: Run & test
- `npm install`
- `npm run dev`
- Validate flows: signup → login → add to cart → checkout → order tracking.

