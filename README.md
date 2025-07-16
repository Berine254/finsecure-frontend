# finsecure-fronte// File: pages/index.js
import Head from "next/head";
import Link from "next/link";

export default function Home() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-900">
      <Head>
        <title>FinSecure AI</title>
      </Head>

      <header className="p-6 bg-blue-900 text-white flex justify-between items-center">
        <h1 className="text-xl font-bold">FinSecure AI</h1>
        <nav className="space-x-4">
          <Link href="/dashboard" className="hover:underline">Dashboard</Link>
          <Link href="/about" className="hover:underline">About</Link>
        </nav>
      </header>

      <main className="p-12 text-center">
        <h2 className="text-3xl font-bold mb-6">Smart Fraud Detection & Credit Scoring for Fintechs</h2>
        <p className="mb-8 max-w-xl mx-auto text-lg">
          FinSecure AI helps fintech companies in Africa detect fraud and score borrowers using real-time AI and alternative data.
        </p>
        <Link href="/dashboard">
          <button className="bg-blue-600 text-white px-6 py-3 rounded-lg shadow-md hover:bg-blue-700 transition">Try the Dashboard</button>
        </Link>
      </main>

      <footer className="text-center p-6 text-sm text-gray-600">
        &copy; 2025 FinSecure AI | Contact: finsecureai@gmail.com | +254740711088
      </footer>
    </div>
  );
}
nd
