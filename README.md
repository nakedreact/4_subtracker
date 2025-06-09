# SubTracker

A modern subscription tracker built with [Next.js](https://nextjs.org).  
Easily manage, categorize, and analyze your recurring subscriptions.

## Features

- Add, edit, and delete subscriptions
- Track cost, billing frequency, payment method, and status
- Categorize subscriptions (Entertainment, Music, Software, etc.)
- Notes and start date for each subscription
- Authentication (sign up & login)
- Responsive UI

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/subtracker.git
   cd 4_subtracker
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser:**
   Visit [http://localhost:3000](http://localhost:3000)

## Project Structure

```
4_subtracker/
├── app/
│   ├── page.js
│   ├── layout.js
│   └── ...
├── components/
│   ├── SubscriptionForm.jsx
│   ├── SubscriptionList.jsx
│   ├── Login.jsx
│   └── ...
├── context/
│   └── AuthContext.jsx
├── public/
├── styles/
│   └── globals.css
├── package.json
└── ...
```

## Customization

- **Categories:**  
  Edit the categories in `SubscriptionForm.jsx` to fit your needs.
- **Styling:**  
  Modify `globals.css` or component styles for your preferred look.

## Deployment

Deploy easily on [Vercel](https://vercel.com/) or your favorite Node.js hosting platform.

## License

MIT

---

**Made for learning and personal finance management.**
