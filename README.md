"use client";

import Link from "next/link";

export default function Sidebar() {
  return (
    <aside className="w-64 h-screen bg-white border-r">

      <div className="p-5">
        <h1 className="font-bold text-xl">
          Cantral Envio
        </h1>
      </div>

      <nav className="flex flex-col gap-2 p-4">

        <Link href="/dashboard">
          Dashboard
        </Link>

        <Link href="/enviar">
          Enviar
        </Link>

        <Link href="/historico">
          Histórico
        </Link>

        <Link href="/relatorios">
          Relatórios
        </Link>

        <Link href="/usuarios">
          Usuários
        </Link>

        <Link href="/configuracoes">
          Configurações
        </Link>

      </nav>

    </aside>
  );
}
import Sidebar from "@/components/Sidebar";

export default function Enviar() {
  return (

    <div className="flex">

      <Sidebar />

      <main className="flex-1 p-8">

        <h1 className="text-2xl font-bold mb-6">
          Nova Publicação
        </h1>

        <input
          type="text"
          placeholder="Título"
          className="border p-3 w-full mb-4"
        />

        <textarea
          placeholder="Mensagem"
          className="border p-3 w-full h-48"
        />

        <div className="mt-4">

          <input type="file" />

        </div>

        <div className="mt-6 flex gap-3">

          <button className="bg-green-600 text-white px-4 py-2 rounded">
            WhatsApp
          </button>

          <button className="bg-blue-500 text-white px-4 py-2 rounded">
            Telegram
          </button>

        </div>

      </main>

    </div>

  );
}import Sidebar from "@/components/Sidebar";

export default function Enviar() {
  return (

    <div className="flex">

      <Sidebar />

      <main className="flex-1 p-8">

        <h1 className="text-2xl font-bold mb-6">
          Nova Publicação
        </h1>

        <input
          type="text"
          placeholder="Título"
          className="border p-3 w-full mb-4"
        />

        <textarea
          placeholder="Mensagem"
          className="border p-3 w-full h-48"
        />

        <div className="mt-4">

          <input type="file" />

        </div>

        <div className="mt-6 flex gap-3">

          <button className="bg-green-600 text-white px-4 py-2 rounded">
            WhatsApp
          </button>

          <button className="bg-blue-500 text-white px-4 py-2 rounded">
            Telegram
          </button>

        </div>

      </main>

    </div>

  );
}import Sidebar from "@/components/Sidebar";

export default function Enviar() {
  return (

    <div className="flex">

      <Sidebar />

      <main className="flex-1 p-8">

        <h1 className="text-2xl font-bold mb-6">
          Nova Publicação
        </h1>

        <input
          type="text"
          placeholder="Título"
          className="border p-3 w-full mb-4"
        />

        <textarea
          placeholder="Mensagem"
          className="border p-3 w-full h-48"
        />

        <div className="mt-4">

          <input type="file" />

        </div>

        <div className="mt-6 flex gap-3">

          <button className="bg-green-600 text-white px-4 py-2 rounded">
            WhatsApp
          </button>

          <button className="bg-blue-500 text-white px-4 py-2 rounded">
            Telegram
          </button>

        </div>

      </main>

    </div>

  );
}
