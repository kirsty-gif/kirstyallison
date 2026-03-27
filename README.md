import React from "react";

export default function HomePage() {
  return (
    <div className="min-h-screen bg-white text-black font-sans">
      <header className="p-6 border-b">
        <h1 className="text-3xl font-bold">Kirsty Allison</h1>
        <p className="text-sm mt-2">Writer and artist working across systems, culture and media</p>
      </header>

      <main className="p-6 space-y-12 max-w-3xl">
        <section>
          <h2 className="text-xl font-semibold mb-2">About</h2>
          <p>
            Kirsty Allison is a British writer and artist working across literature, performance, film and publishing. Her work explores systems of power, identity and cultural production.
          </p>
        </section>

        <section>
          <h2 className="text-xl font-semibold mb-2">Current Project</h2>
          <p>
            <strong>Sampo</strong> is a novel exploring fiction as dissociation and identity as system. It follows a protagonist through collapse, exile and return, culminating in a journey to Finland and the mythic Sampo.
          </p>
        </section>

        <section>
          <h2 className="text-xl font-semibold mb-2">Selected Work</h2>
          <ul className="list-disc pl-5 space-y-1">
            <li>Psychomachia (Wrecking Ball Press, 2021)</li>
            <li>Now Is Now (Cold Lips Press, 2020)</li>
            <li>Editor, Ambit (2021–2023)</li>
          </ul>
        </section>

        <section>
          <h2 className="text-xl font-semibold mb-2">Contact</h2>
          <p>Email: contact@example.com</p>
        </section>
      </main>

      <footer className="p-6 border-t text-sm">
        © {new Date().getFullYear()} Kirsty Allison
      </footer>
    </div>
  );
}
