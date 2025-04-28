import { Button } from "@/components/ui/button";

export default function SmartDPPLandingPage() {
  return (
    <div className="min-h-screen flex flex-col bg-gradient-to-b from-white to-slate-100">
      <header className="flex justify-between items-center p-6 shadow-md bg-white">
        <h1 className="text-3xl font-bold text-blue-700">SmartDPP</h1>
        <Button>Załóż konto</Button>
      </header>

      <main className="flex-1 flex flex-col items-center justify-center text-center p-6">
        <h2 className="text-5xl font-bold mb-6">Twórz Cyfrowe Paszporty Produktów</h2>
        <p className="text-lg text-gray-600 max-w-2xl mb-8">
          Prosto, szybko i zgodnie z regulacjami UE. Nasza platforma umożliwi Ci wygenerowanie paszportu produktu w kilka minut!
        </p>
        <Button className="text-lg px-8 py-4">Rozpocznij za darmo</Button>
      </main>

      <section className="grid grid-cols-1 md:grid-cols-3 gap-8 p-12">
        <div className="bg-white rounded-2xl p-6 shadow-md">
          <h3 className="text-2xl font-semibold mb-4">Kreator Paszportu</h3>
          <p className="text-gray-600">Wypełnij prosty formularz i wygeneruj paszport zgodny z wymaganiami UE.</p>
        </div>
        <div className="bg-white rounded-2xl p-6 shadow-md">
          <h3 className="text-2xl font-semibold mb-4">Generuj QR i NFC</h3>
          <p className="text-gray-600">Udostępniaj informacje o produkcie poprzez kod QR lub chip NFC.</p>
        </div>
        <div className="bg-white rounded-2xl p-6 shadow-md">
          <h3 className="text-2xl font-semibold mb-4">Zarządzaj Produktami</h3>
          <p className="text-gray-600">Organizuj i edytuj swoje paszporty produktów z poziomu przejrzystego panelu.</p>
        </div>
      </section>

      <footer className="p-6 text-center text-gray-500">
        &copy; 2025 SmartDPP. Wszystkie prawa zastrzeżone.
      </footer>
    </div>
  );
}
