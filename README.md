<!DOCTYPE html>
<html lang="tr">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BorderWay - Your Pathway to a New Home</title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.16/tailwind.min.css">
</head>

<body class="font-sans bg-gradient-to-b from-blue-50 to-blue-100 text-gray-800">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
    <!-- Header -->
    <header class="flex justify-between items-center mb-8">
      <div class="flex items-center">
        <img src="images/Borderwaylogo.png" alt="BorderWay Logo" class="mr-4" style="max-width: 70px; height: auto;">
        <h1 class="text-4xl font-extrabold text-white-600">BorderWay</h1>
      </div>
      <nav>
        <ul class="flex space-x-6 items-center">
          <li><a href="#" class="text-gray-700 hover:text-blue-500">Göçmenlik Rehberi</a></li>
          <li><a href="#" class="text-gray-700 hover:text-blue-500">Hukuki Destek</a></li>
          <li><a href="#" class="text-gray-700 hover:text-blue-500">Haberler</a></li>
          <li class="flex items-center space-x-4">
            <a href="#" class="text-gray-700 hover:text-blue-500">Profil</a>
            <!-- Profile Avatar -->
            <div class="w-10 h-10 rounded-full overflow-hidden border-2 border-gray-300">
              <img src="images/profilavatar.png" alt="Profil Avatarı" class="w-full h-full object-cover">
            </div>
          </li>
        </ul>
      </nav>
    </header>

    <!-- Welcome Section -->
    <main>
      <section class="mb-12 text-center">
        <h2 class="text-3xl font-bold mb-4">Hoşgeldiniz!</h2>
        <p class="text-gray-600 mb-6 max-w-2xl mx-auto">BorderWay, göç etmek isteyen kişilere yol gösteren bir platformdur. Hukuki süreçlerden, gerekli belgelere kadar tüm aşamalarda yanınızdayız.</p>
        <a href="#" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg shadow-lg transition duration-300 ease-in-out">Kayıt Ol</a>
      </section>

      <!-- Country Selection -->
      <div class="bg-white shadow-lg rounded-lg p-8 mb-8">
        <h2 class="text-2xl font-bold mb-4">Ülke Seçimi</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
          <div>
            <label for="from-country" class="block text-gray-700 font-medium mb-2">Vatandaşı Olduğunuz Ülke</label>
            <select id="from-country" class="w-full border border-gray-300 rounded-md py-2 px-3 focus:outline-none focus:ring focus:ring-blue-500">
              <option value="">Ülke Seçin</option>
              <option value="tr">Türkiye</option>
              <option value="us">Amerika Birleşik Devletleri</option>
              <option value="de">Almanya</option>
              <option value="uk">Birleşik Krallık</option>
            </select>
          </div>
          <div>
            <label for="to-country" class="block text-gray-700 font-medium mb-2">Vatandaşı Olmak İstediğiniz Ülke</label>
            <select id="to-country" class="w-full border border-gray-300 rounded-md py-2 px-3 focus:outline-none focus:ring focus:ring-blue-500">
              <option value="">Ülke Seçin</option>
              <option value="tr">Türkiye</option>
              <option value="us">Amerika Birleşik Devletleri</option>
              <option value="de">Almanya</option>
              <option value="uk">Birleşik Krallık</option>
            </select>
          </div>
        </div>
        <button id="viewLegalProcess" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg shadow-lg mt-6 transition duration-300 ease-in-out">
          Hukuki Süreci Görüntüle
        </button>
      </div>

      <!-- Legal Process Recommendation -->
      <div id="legal-process-recommendation" class="bg-white shadow-lg rounded-lg p-8 mb-8">
        <h2 class="text-2xl font-bold mb-4">Hukuki Süreç Tavsiyesi</h2>
        <p class="text-gray-600">Ülke seçimlerinizi yaptıktan sonra, burada size özel hukuki süreç tavsiyeleri gösterilecek.</p>
      </div>

      <!-- Guides Section -->
      <section class="mb-12">
        <h2 class="text-3xl font-bold mb-6 text-center">Göçmenlik Rehberi</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white shadow-lg rounded-lg p-6 hover:shadow-xl transition-shadow duration-300">
 	    <img src="images/vizebasvuru.png" alt="Vize Başvuruları İkonu" class="w-8 h-8 mr-3">
	    <div>
            <h3 class="text-xl font-bold mb-3">Vize Başvuruları</h3>
            <p class="text-gray-600 mb-4">Hangi vize türüne ihtiyacınız var? BorderWay size yardımcı olur.</p>
            <a href="#" class="text-blue-500 hover:text-blue-600 font-medium">Daha Fazla Bilgi <i class="fas fa-arrow-right"></i></a>
          </div>
	  </div>
          <div class="bg-white shadow-lg rounded-lg p-6 hover:shadow-xl transition-shadow duration-300">
 	   <img src="images/belgehazırlıgı.png" alt="Belge Hazırlığı İkonu" class="w-8 h-8 mr-3">
	   <div>
            <h3 class="text-xl font-bold mb-3">Belge Hazırlığı</h3>
            <p class="text-gray-600 mb-4">Gerekli belgeleri toplamada size rehberlik ediyoruz.</p>
            <a href="#" class="text-blue-500 hover:text-blue-600 font-medium">Daha Fazla Bilgi <i class="fas fa-arrow-right"></i></a>
           </div>
	  </div>
          <div class="bg-white shadow-lg rounded-lg p-6 hover:shadow-xl transition-shadow duration-300">
          <img src="images/hukukianaliz.png" alt="Hukuki Riskler İkonu" class="w-8 h-8 mr-3">
          <div>
            <h3 class="text-xl font-bold mb-3">Hukuki Riskler</h3>
            <p class="text-gray-600 mb-4">Hukuki riskleri en aza indirmek için size yardımcı oluyoruz.</p>
            <a href="#" class="text-blue-500 hover:text-blue-600 font-medium">Daha Fazla Bilgi <i class="fas fa-arrow-right"></i></a>
          </div>
        </div>
      </section>

      <!-- Legal Support Section -->
      <section class="mb-12 text-center">
        <h2 class="text-3xl font-bold mb-6">Hukuki Destek</h2>
        <div class="bg-white shadow-lg rounded-lg p-8">
          <h3 class="text-xl font-bold mb-4">Uzman Avukatlarla Çalışın</h3>
          <p class="text-gray-600 mb-6">BorderWay, her ülke için atanmış hukuki ekiplerle iletişim olanağı sunar.</p>
          <a href="#" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg shadow-lg transition duration-300 ease-in-out">Hukuki Destek Alın</a>
        </div>
      </section>

      <!-- News Section -->
      <section class="mb-12">
        <h2 class="text-3xl font-bold mb-6 text-center">Haberler ve Güncellemeler</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white shadow-lg rounded-lg p-6 hover:shadow-xl transition-shadow duration-300">
            <img src="images/Dubai-Gaming-Visa.jpg" alt="Haber Görseli" class="mb-4 rounded">
            <h3 class="text-xl font-bold mb-2">Dubai Gaming Visa ile Dijital Yaratıcılığa Yeni Bir Boyut: 10 Yıl Süreli Oturum İzni</h3>
            <p class="text-gray-600">Dubai, oyun geliştiricileri ve dijital içerik üreticileri için yepyeni bir fırsat sunuyor! Dubai Gaming Visa ile 10 yıl süreyle oturum izni alabilir ve Dubai'nin büyüyen oyun sektörüne katılabilirsiniz. Yaratıcı projelerinizi hayata geçirmek için şimdi tam zamanı!</p>
            <a href="#" class="text-blue-500 hover:text-blue-600 font-medium">Daha Fazla Bilgi <i class="fas fa-arrow-right"></i></a>
          </div>
          <div class="bg-white shadow-lg rounded-lg p-6 hover:shadow-xl transition-shadow duration-300">
            <img src="images/ucakhaber.jpg" alt="Haber Görseli" class="mb-4 rounded">
            <h3 class="text-xl font-bold mb-2">Vatandaşlık Başvurusu Kolaylaştırılıyor: Yeni Düzenlemelerle Süreç Hızlanıyor</h3>
            <p class="text-gray-600">Bazı ülkeler, vatandaşlık başvuru süreçlerini dijitalleştirerek ve işlemleri basitleştirerek önemli değişiklikler yapıyor. Almanya ve Portekiz gibi ülkeler, başvuru sahiplerine daha hızlı ve şeffaf bir süreç sunmak için dijital platformlar geliştirdi. Bu sayede başvurular daha verimli bir şekilde işleniyor ve bürokratik engeller en aza indiriliyor.</p>
            <a href="#" class="text-blue-500 hover:text-blue-600 font-medium">Daha Fazla Bilgi <i class="fas fa-arrow-right"></i></a>
          </div>
          <div class="bg-white shadow-lg rounded-lg p-6 hover:shadow-xl transition-shadow duration-300">
            <img src="images/GoldenVisa.jpg" alt="Haber Görseli" class="mb-4 rounded">
            <h3 class="text-xl font-bold mb-2">Golden Visa Programı ile seyahat artık daha kolay!</h3>
            <p class="text-gray-600">Golden Visa Programı, yatırımcılar ve aileleri için yeni bir dönemi başlatıyor! Yatırım yaparak, uzun süreli oturum izni ve hatta vatandaşlık fırsatı elde etmek isteyenler için önemli bir fırsat sunuluyor. Bu program sayesinde, seyahat ve ikamet işlemleri daha hızlı ve kolay hale gelirken, dünya genelinde yeni fırsatlar ve avantajlar kapılarını aralıyor</p>
            <a href="#" class="text-blue-500 hover:text-blue-600 font-medium">Daha Fazla Bilgi <i class="fas fa-arrow-right"></i></a>
          </div>
        </div>
      </section>
    </main>
  </div>

  <script>
    document.getElementById('viewLegalProcess').addEventListener('click', function() {
      const fromCountry = document.getElementById('from-country').value;
      const toCountry = document.getElementById('to-country').value;
      const recommendationDiv = document.getElementById('legal-process-recommendation');
      
      // Temel kontrol
      if (!fromCountry || !toCountry) {
        alert("Lütfen hem vatandaşı olduğunuz hem de gitmek istediğiniz ülkeyi seçin.");
        return;
      }

      // Örnek bir öneri, gerçek uygulama için burayı dinamik hale getirmelisiniz
      recommendationDiv.innerHTML = <h2 class="text-2xl font-bold mb-4">Hukuki Süreç Tavsiyesi</h2>
                                      <p class="text-gray-600">Seçtiğiniz ülkeler için özel hukuki süreç tavsiyeleri burada yer alacak.</p>;
      recommendationDiv.style.display = "block";
    });
  </script>
<!-- Canlı Destek İkonu -->
<div id="live-chat-icon" class="fixed bottom-8 right-8 w-16 h-16 bg-blue-600 rounded-full flex items-center justify-center shadow-lg cursor-pointer z-50">
  <i class="fas fa-comments text-white text-2xl"></i>
</div>

<!-- Canlı Destek İkonu -->
<div id="live-chat-icon" class="fixed bottom-8 right-8 w-16 h-16 bg-blue-600 rounded-full flex items-center justify-center shadow-lg cursor-pointer z-50">
  <i class="fas fa-comments text-white text-2xl"></i>
</div>

<!-- Canlı Destek Penceresi -->
<div id="live-chat-window" class="fixed bottom-20 right-8 bg-white w-80 h-96 shadow-lg rounded-lg hidden z-50">
  <div class="flex justify-between items-center bg-blue-600 text-white p-4 rounded-t-lg">
    <h3 class="text-lg font-semibold">Canlı Destek</h3>
    <button id="close-chat" class="text-xl">&times;</button>
  </div>
  <div class="p-4 text-gray-700 overflow-y-auto h-[70%]">
    <p>Merhaba! Size nasıl yardımcı olabilirim?</p>
  </div>
  <div class="p-4 border-t">
    <input type="text" placeholder="Mesajınızı yazın..." class="w-full p-2 border rounded-lg focus:outline-none">
  </div>
</div>

<style>
  #live-chat-icon {
    transition: transform 0.3s ease-in-out, background-color 0.3s;
  }
  #live-chat-icon:hover {
    transform: scale(1.1);
    background-color: #2563eb;
  }
  #live-chat-window.hidden {
    display: none;
  }
</style>
</body>

</html>
