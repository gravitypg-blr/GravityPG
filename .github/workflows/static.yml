import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { MapPin, Phone, Mail } from "lucide-react";
import { motion } from "framer-motion";

export default function PGServicePage() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-blue-50 to-blue-100 p-6">
      <div className="max-w-4xl mx-auto space-y-8">
        <header className="text-center">
          <h1 className="text-4xl font-bold text-blue-800">Welcome to ComfortStay PG</h1>
          <p className="text-lg text-gray-600 mt-2">Your home away from home in the heart of the city</p>
        </header>

        <section>
          <Card className="shadow-xl">
            <CardContent className="p-6">
              <h2 className="text-2xl font-semibold text-blue-700 mb-4">About Us</h2>
              <p className="text-gray-700">
                ComfortStay PG offers a peaceful and secure living environment with all modern amenities, ideal for working professionals and students. Located centrally with easy access to public transport, shopping centers, and educational institutions.
              </p>
            </CardContent>
          </Card>
        </section>

        <section>
          <Card className="shadow-xl">
            <CardContent className="p-6 grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <h2 className="text-2xl font-semibold text-blue-700 mb-4">Facilities</h2>
                <ul className="list-disc list-inside text-gray-700 space-y-1">
                  <li>Fully furnished rooms</li>
                  <li>Wi-Fi and 24/7 Power Backup</li>
                  <li>Nutritious meals</li>
                  <li>Laundry & Housekeeping</li>
                  <li>Air-conditioned rooms</li>
                  <li>Security with CCTV</li>
                </ul>
              </div>
              <div className="grid grid-cols-2 gap-2">
                <img src="/images/room1.jpg" alt="Room 1" className="rounded-xl shadow" />
                <img src="/images/room2.jpg" alt="Room 2" className="rounded-xl shadow" />
                <img src="/images/dining.jpg" alt="Dining Area" className="rounded-xl shadow" />
                <img src="/images/common.jpg" alt="Common Area" className="rounded-xl shadow" />
              </div>
            </CardContent>
          </Card>
        </section>

        <section>
          <Card className="shadow-xl">
            <CardContent className="p-6 space-y-4">
              <h2 className="text-2xl font-semibold text-blue-700">Contact Us</h2>
              <div className="flex items-center space-x-3 text-gray-700">
                <Phone className="text-blue-500" /> <span>+91 98765 43210</span>
              </div>
              <div className="flex items-center space-x-3 text-gray-700">
                <Mail className="text-blue-500" /> <span>contact@comfortstaypg.com</span>
              </div>
              <div className="flex items-center space-x-3 text-gray-700">
                <MapPin className="text-blue-500" /> <span>123 Main Street, Central City, India</span>
              </div>
              <Button className="mt-4">Send Inquiry</Button>
            </CardContent>
          </Card>
        </section>

        <section>
          <Card className="shadow-xl">
            <CardContent className="p-6">
              <h2 className="text-2xl font-semibold text-blue-700 mb-4">Location</h2>
              <iframe
                className="w-full h-64 rounded-xl shadow"
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3919.243044680662!2d106.69707887504812!3d10.792716389352984!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31752930b69bd2ab%3A0x18a17970b53b64!2sLandmark%2072!5e0!3m2!1sen!2s!4v1616120316602!5m2!1sen!2s"
                allowFullScreen=""
                loading="lazy"
                referrerPolicy="no-referrer-when-downgrade"
              ></iframe>
            </CardContent>
          </Card>
        </section>
      </div>
    </div>
  );
}  
