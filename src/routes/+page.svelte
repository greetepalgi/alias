<script>
    let kaart = "https://i.imgur.com/GZzuIFu.png"

    function jargmineKaart() {
        kaart = "https://i.imgur.com/gQ8g5xk.png"
    }
</script>

<div class="min-h-screen bg-gray-100 p-8">
    <div class="max-w-2xl mx-auto bg-white rounded-lg shadow-lg p-6">
      <h1 class="text-4xl font-bold text-gray-800 mb-6">Aliase mäng</h1>
      
      <div class="mb-6">
        <img src={kaart} alt="Hobene" class="w-full rounded-lg shadow-md">
      </div>
      
      <button onclick={jargmineKaart} class="bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-lg shadow-md transition duration-200 ease-in-out transform hover:scale-105 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50">
        Järka kaart
      </button>
    </div>
  </div>