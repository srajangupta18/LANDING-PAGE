# LANDING-PAGE
import React from "react";

export default function Home() {
  return (
    <div className="flex flex-col items-center justify-center min-h-screen bg-gray-100 text-center p-6">
      <header className="w-full max-w-4xl p-6">
        <h1 className="text-4xl font-bold text-gray-900">Welcome to My Startup</h1>
        <p className="mt-4 text-lg text-gray-600">Empowering your ideas with cutting-edge technology.</p>
      </header>
      <main className="w-full max-w-4xl p-6 bg-white shadow-md rounded-lg mt-6">
        <h2 className="text-2xl font-semibold text-gray-800">Why Choose Us?</h2>
        <p className="mt-2 text-gray-600">We provide the best solutions for your business growth.</p>
      </main>
      <footer className="mt-10 text-gray-500">
        &copy; 2025 My Startup. All rights reserved.
      </footer>
    </div>
  );
}
