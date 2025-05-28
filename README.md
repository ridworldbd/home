# ridworld
 𝐚 𝐩𝐫𝐞𝐦𝐢𝐮𝐦 𝐝𝐞𝐬𝐭𝐢𝐧𝐚𝐭𝐢𝐨𝐧 𝐟𝐨𝐫 𝐞𝐥𝐞𝐠𝐚𝐧𝐭 𝐦𝐨𝐝𝐞𝐬𝐭 𝐰𝐞𝐚𝐫,🌟💎💎 𝐛𝐞𝐬𝐩𝐨𝐤𝐞 𝐠𝐫𝐚𝐩𝐡𝐢𝐜 𝐝𝐞𝐬𝐢𝐠𝐧, 𝐚𝐧𝐝 𝐜𝐫𝐞𝐚𝐭𝐢𝐯𝐞 𝐚𝐫𝐭 𝐭𝐫𝐚𝐢𝐧𝐢𝐧𝐠. 💻 
import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Facebook, Youtube } from "lucide-react";

export default function HomePage() {
  return (
    <main className="min-h-screen bg-gradient-to-b from-[#e0fff9] to-[#f6f9f7] text-gray-800">
      <header className="p-4 flex items-center justify-between shadow-md bg-white">
        <div className="text-2xl font-bold text-teal-700">RIDWORLD</div>
        <nav className="flex gap-4 text-sm">
          <a href="#about" className="hover:text-teal-600">About</a>
          <a href="#services" className="hover:text-teal-600">Services</a>
          <a href="#contact" className="hover:text-teal-600">Contact</a>
        </nav>
      </header>

      <section className="text-center py-16 px-4">
        <h1 className="text-4xl md:text-5xl font-bold text-teal-800">Welcome to RIDWORLD</h1>
        <p className="mt-4 max-w-xl mx-auto text-lg text-gray-600">
          Luxury in Modest Fashion, Art & Design. Always be Unique 🌟
        </p>
        <div className="flex justify-center mt-6 gap-4">
          <a href="https://facebook.com/ridworld.bd" target="_blank">
            <Facebook className="text-blue-600 w-6 h-6" />
          </a>
          <a href="https://youtube.com/@ridworld.bd" target="_blank">
            <Youtube className="text-red-600 w-6 h-6" />
          </a>
        </div>
      </section>

      <section id="about" className="py-10 px-6 bg-[#fefefe]">
        <h2 className="text-2xl font-bold mb-4 text-teal-700">About RIDWORLD</h2>
        <p className="max-w-3xl text-gray-700">
          RIDWORLD is a premium destination for elegant modest wear, bespoke graphic design, and creative art training.
          We offer high-end burqas, abayas, and hijabs crafted in our own factory, along with exclusive training in drawing,
          handwriting, and graphic design. Visit us at Shahid Market, College Road, Feni.
        </p>
      </section>

      <section id="services" className="py-10 px-6">
        <h2 className="text-2xl font-bold mb-4 text-teal-700">Our Services</h2>
        <div className="grid grid-cols-1 md:grid-cols-3 gap-6">
          <Card>
            <CardContent>
              <h3 className="font-semibold text-lg text-teal-600 mb-2">Modest Fashion</h3>
              <p>Premium Burqas, Abayas, Hijabs, Niqabs, and custom fabrics.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent>
              <h3 className="font-semibold text-lg text-teal-600 mb-2">Graphic Design</h3>
              <p>Logos, Cards, Menus & More. Photoshop & Illustrator Training.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent>
              <h3 className="font-semibold text-lg text-teal-600 mb-2">Creative Training</h3>
              <p>Drawing, Handwriting (Arabic, Bangla, English), Basic Computer Skills.</p>
            </CardContent>
          </Card>
        </div>
      </section>

      <footer id="contact" className="text-center py-6 bg-white shadow-inner mt-10">
        <p className="text-sm text-gray-600">Shop 273, Shahid Market, College Road, Feni 3900</p>
        <p className="text-sm text-gray-600">WhatsApp: +88 01837-968152</p>
      </footer>
    </main>
  );
}
