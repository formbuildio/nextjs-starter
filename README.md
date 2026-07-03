# Next.js Formbuild Starter

A beautiful, copy-paste ready Next.js 14 (App Router) starter template featuring a fully functional contact form wired directly to [formbuild.io](https://formbuild.io).

## 🚀 Quickstart

1. **Clone the repository**
   ```bash
   git clone https://github.com/formbuildio/nextjs-starter.git
   cd nextjs-starter
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set your Form ID**
   Open `src/app/page.tsx` and replace `YOUR_FORM_ID_HERE` with your actual form ID from your formbuild.io dashboard.

   ```tsx
   // src/app/page.tsx
   const FORM_ID = "f_123abc"; 
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🛠 Tech Stack
- **Next.js 14** (App Router)
- **Tailwind CSS** (Styling)
- **@formbuild/react** (Official React SDK for instant backend connection)
- **Lucide React** (Beautiful Icons)
