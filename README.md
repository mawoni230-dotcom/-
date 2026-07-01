<!DOCTYPE html>
<html lang="ka">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>კონდიციონერების მონტაჟი და სერვისი</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <!-- ჰედერი -->
    <header class="bg-blue-600 text-white py-6 shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 flex flex-col md:flex-row justify-between items-center gap-4">
            <h1 id="view-title" class="text-2xl font-bold tracking-wide">კონდიციონერების სერვისი</h1>
            <div class="flex items-center gap-2 bg-white text-blue-600 px-4 py-2 rounded-full font-bold shadow shadow-blue-800">
                <i class="fa-solid fa-phone animate-pulse"></i>
                <a id="view-phone-link" href="tel:599000000"><span id="view-phone">599 00 00 00</span></a>
            </div>
        </div>
    </header>

    <!-- მთავარი სექცია (Hero) -->
    <section class="bg-gradient-to-br from-blue-500 to-indigo-600 text-white py-20 px-4 text-center">
        <div class="max-w-3xl mx-auto">
            <h2 id="view-hero-title" class="text-4xl md:text-5xl font-extrabold mb-4 leading-tight">კონდიციონერის მონტაჟი და უსწრაფესი სერვისი</h2>
            <p id="view-hero-sub" class="text-lg md:text-xl text-blue-100 mb-8">ხარისხიანი მუშაობა, გარანტია და სუფთა პროცესი ბინებისსა და ოფისებისთვის.</p>
            <a id="view-cta-link" href="tel:599000000" class="bg-yellow-400 hover:bg-yellow-300 text-gray-900 font-extrabold text-lg px-8 py-4 rounded-xl shadow-lg transition-all inline-flex items-center gap-3">
                <i class="fa-solid fa-phone-volume"></i> დაგვიკავშირდით ახლავე
            </a>
        </div>
    </section>

    <!-- ფასების სექცია -->
    <section class="container mx-auto px-4 py-16 max-w-5xl">
        <h3 class="text-3xl font-bold text-center mb-12 text-gray-900">სერვისები და ფასები</h3>
        
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden border border-gray-100">
            <div class="overflow-x-auto">
                <table class="w-full text-left border-collapse">
                    <thead>
                        <tr class="bg-gray-100 text-gray-700 font-bold border-b border-gray-200">
                            <th class="p-4 md:p-6 text-base md:text-lg">კონდიციონერის ზომა</th>
                            <th class="p-4 md:p-6 text-base md:text-lg text-center">მონტაჟი</th>
                            <th class="p-4 md:p-6 text-base md:text-lg text-center">გაწმენდა</th>
                            <th class="p-4 md:p-6 text-base md:text-lg text-center">ფრეონი</th>
                            <th class="p-4 md:p-6 text-base md:text-lg text-center">რესტავრაცია</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-gray-100 font-medium">
                        <tr class="hover:bg-gray-50 transition-colors">
                            <td class="p-4 md:p-6 font-bold text-blue-600">9,000 - 12,000 BTU</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-9-mont">80</span> ₾</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-9-clean">40</span> ₾</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-9-freon">50</span> ₾</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-9-rest">60</span> ₾</td>
                        </tr>
                        <tr class="hover:bg-gray-50 transition-colors">
                            <td class="p-4 md:p-6 font-bold text-blue-600">18,000 BTU</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-18-mont">100</span> ₾</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-18-clean">50</span> ₾</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-18-freon">70</span> ₾</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-18-rest">80</span> ₾</td>
                        </tr>
                        <tr class="hover:bg-gray-50 transition-colors">
                            <td class="p-4 md:p-6 font-bold text-blue-600">24,000 BTU</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-24-mont">120</span> ₾</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-24-clean">60</span> ₾</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-24-freon">90</span> ₾</td>
                            <td class="p-4 md:p-6 text-center text-gray-900 text-lg"><span id="p-24-rest">100</span> ₾</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </section>

    <!-- უპირატესობები -->
    <section class="bg-white py-16 border-t border-b border-gray-100">
        <div class="container mx-auto px-4 max-w-5xl">
            <h3 class="text-3xl font-bold text-center mb-12">რატომ ჩვენ?</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-6 bg-gray-50 rounded-xl text-center shadow-sm">
                    <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center mx-auto mb-4 text-xl"><i class="fa-solid fa-broom"></i></div>
                    <h4 class="font-bold text-lg mb-2">სუფთა მუშაობა</h4>
                    <p class="text-gray-600 text-sm">ვიყენებთ სპეციალურ ხელსაწყოებს, რათა კედლის გაბურღვისას მტვერი არ დარჩეს.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-xl text-center shadow-sm">
                    <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center mx-auto mb-4 text-xl"><i class="fa-solid fa-shield-halved"></i></div>
                    <h4 class="font-bold text-lg mb-2">გარანტირებული ხარისხი</h4>
                    <p class="text-gray-600 text-sm">ყველა შესრულებულ სამუშაოზე და მასალაზე გაძლევთ სრულ გარანტიას.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-xl text-center shadow-sm">
                    <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center mx-auto mb-4 text-xl"><i class="fa-solid fa-bolt"></i></div>
                    <h4 class="font-bold text-lg mb-2">სწრაფი რეაგირება</h4>
                    <p class="text-gray-600 text-sm">გამოძახებიდან უმოკლეს დროში ვართ თქვენთან, წინასწარ შეთანხმებულ საათებში.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ************************************* -->
    <!-- ადმინ პანელი (მხოლოდ თქვენთვის) -->
    <!-- ************************************* -->
    <section class="bg-gray-900 text-white py-12 px-4 border-t-4 border-yellow-400">
        <div class="container mx-auto max-w-3xl">
            <div class="flex items-center gap-3 mb-6">
                <i class="fa-solid fa-gear text-yellow-400 text-2xl animate-spin-slow"></i>
                <h3 class="text-xl font-bold">საიტის მართვის პანელი (აქედან შეცვალეთ ყველაფერი)</h3>
            </div>
            
            <div class="space-y-6 bg-gray-800 p-6 rounded-xl border border-gray-700 shadow-inner">
                <!-- ძირითადი ინფო -->
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs text-gray-400 font-bold uppercase mb-2">ბიზნესის სახელი</label>
                        <input type="text" id="inp-title" class="w-full bg-gray-700 border border-gray-600 rounded px-3 py-2 text-white focus:outline-none focus:border-blue-500">
                    </div>
                    <div>
                        <label class="block text-xs text-gray-400 font-bold uppercase mb-2">ტელეფონის ნომერი</label>
                        <input type="text" id="inp-phone" class="w-full bg-gray-700 border border-gray-600 rounded px-3 py-2 text-white focus:outline-none focus:border-blue-500">
                    </div>
                </div>

                <!-- სარეკლამო ტექსტები -->
                <div>
                    <label class="block text-xs text-gray-400 font-bold uppercase mb-2">მთავარი სარეკლამო სათაური</label>
                    <input type="text" id="inp-hero-title" class="w-full bg-gray-700 border border-gray-600 rounded px-3 py-2 text-white focus:outline-none focus:border-blue-500">
                </div>
                <div>
                    <label class="block text-xs text-gray-400 font-bold uppercase mb-2">ქვესათაური</label>
                    <input type="text" id="inp-hero-sub" class="w-full bg-gray-700 border border-gray-600 rounded px-3 py-2 text-white focus:outline-none focus:border-blue-500">
                </div>

                <!-- ფასების მართვა -->
                <div>
                    <h4 class="text-sm font-bold text-yellow-400 uppercase mb-3 border-b border-gray-700 pb-1">ფასების რედაქტირება (ლარებში)</h4>
                    
                    <div class="space-y-4">
                        <div class="bg-gray-900 p-3 rounded border border-gray-700">
                            <span class="block text-xs font-bold text-blue-400 mb-2">9,000 - 12,000 BTU</span>
                            <div class="grid grid-cols-4 gap-2">
                                <input type="number" id="inp-9-mont" placeholder="მონტაჟი" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                                <input type="number" id="inp-9-clean" placeholder="გაწმენდა" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                                <input type="number" id="inp-9-freon" placeholder="ფრეონი" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                                <input type="number" id="inp-9-rest" placeholder="რესტავრაცია" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                            </div>
                        </div>

                        <div class="bg-gray-900 p-3 rounded border border-gray-700">
                            <span class="block text-xs font-bold text-blue-400 mb-2">18,000 BTU</span>
                            <div class="grid grid-cols-4 gap-2">
                                <input type="number" id="inp-18-mont" placeholder="მონტაჟი" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                                <input type="number" id="inp-18-clean" placeholder="გაწმენდა" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                                <input type="number" id="inp-18-freon" placeholder="ფრეონი" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                                <input type="number" id="inp-18-rest" placeholder="რესტავრაცია" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                            </div>
                        </div>

                        <div class="bg-gray-900 p-3 rounded border border-gray-700">
                            <span class="block text-xs font-bold text-blue-400 mb-2">24,000 BTU</span>
                            <div class="grid grid-cols-4 gap-2">
                                <input type="number" id="inp-24-mont" placeholder="მონტაჟი" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                                <input type="number" id="inp-24-clean" placeholder="გაწმენდა" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                                <input type="number" id="inp-24-freon" placeholder="ფრეონი" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                                <input type="number" id="inp-24-rest" placeholder="რესტავრაცია" class="w-full bg-gray-700 text-xs rounded p-2 text-center text-white">
                            </div>
                        </div>
                    </div>
                </div>

                <button onclick="saveChanges()" class="w-full bg-green-500 hover:bg-green-600 text-gray-900 font-extrabold py-3 rounded-lg text-lg transition-all shadow-md">
                    <i class="fa-solid fa-floppy-disk"></i> მონაცემების შენახვა და საიტის განახლება
                </button>
            </div>
        </div>
    </section>

    <!-- ლოგიკა მონაცემების შესანახად -->
    <script>
        const fields = [
            'title', 'phone', 'hero-title', 'hero-sub',
            '9-mont', '9-clean', '9-freon', '9-rest',
            '18-mont', '18-clean', '18-freon', '18-rest',
            '24-mont', '24-clean', '24-freon', '24-rest'
        ];

        function loadData() {
            fields.forEach(field => {
                const savedValue = localStorage.getItem('ac_' + field);
                if (savedValue) {
                    // ვანახებთ საიტზე
                    const viewEl = document.getElementById('view-' + field);
                    if (viewEl) viewEl.innerText = savedValue;
                    
                    // ტელეფონის ლინკებისთვის სპეციალური დამუშავება
                    if (field === 'phone') {
                        document.getElementById('view-phone-link').href = 'tel:' + savedValue;
                        document.getElementById('view-cta-link').href = 'tel:' + savedValue;
                    }

                    // ვსვამთ ინპუტებშიც, რომ რედაქტირებისას დაგვხვდეს
                    document.getElementById('inp-' + field).value = savedValue;
                } else {
                    // თუ პირველად შემოვიდა, ინპუტებში საიტზე არსებული საწყისი მნიშვნელობები გადაგვაქვს
                    const viewEl = document.getElementById('view-' + field);
                    if (viewEl) document.getElementById('inp-' + field).value = viewEl.innerText;
                }
            });
        }

        function saveChanges() {
            fields.forEach(field => {
                const value = document.getElementById('inp-' + field).value;
                localStorage.setItem('ac_' + field, value);
            });
            loadData();
            alert('საიტი წარმატებით განახლდა თქვენს ბრაუზერში!');
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        window.onload = loadData;
    </script>
</body>
</html>
