<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perpustakaan MTs Unggulan Perwanida</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Poppins', sans-serif; }
    </style>
</head>
<body class="bg-slate-100 min-h-screen flex flex-col justify-between">

    <!-- 1. LANDING PAGE / BERANDA AWAL -->
    <div id="landing-page" class="fixed inset-0 z-50 flex items-center justify-center bg-slate-900 bg-cover bg-center text-white p-4" style="background-image: linear-gradient(rgba(15, 23, 42, 0.75), rgba(15, 23, 42, 0.85)), url('IMG_20260717_190525_609.jpg');">
        <div class="max-w-xl w-full bg-white/10 backdrop-blur-md p-8 sm:p-10 rounded-3xl border border-white/20 text-center shadow-2xl">
            <div class="w-20 h-20 bg-emerald-500 text-white mx-auto rounded-full flex items-center justify-center text-3xl shadow-lg mb-6">
                <i class="fa-solid fa-book-quran"></i>
            </div>
            <h1 class="text-2xl sm:text-3xl font-bold tracking-tight mb-2">Perpustakaan Digital</h1>
            <h2 class="text-lg sm:text-xl font-semibold text-emerald-400 mb-4">MTs Unggulan Perwanida</h2>
            <p class="text-slate-200 text-sm mb-8 leading-relaxed">Selamat datang di sistem pelayanan literasi dan peminjaman buku mandiri. Silakan masuk untuk melakukan presensi, transaksi buku, atau mengecek katalog.</p>
            
            <button onclick="enterLibrary()" class="w-full py-3.5 px-6 bg-emerald-500 hover:bg-emerald-600 text-white font-bold text-base rounded-xl shadow-lg hover:shadow-emerald-500/50 transition-all duration-300 flex items-center justify-center space-x-2">
                <span>Silahkan Masuk</span>
                <i class="fa-solid fa-arrow-right"></i>
            </button>
        </div>
    </div>

    <!-- 2. SYSTEM HEADER / NAVBAR -->
    <header class="bg-emerald-700 text-white shadow-lg">
        <div class="max-w-6xl mx-auto px-4 py-4 flex flex-wrap justify-between items-center">
            <div class="flex items-center space-x-3 mb-2 sm:mb-0 cursor-pointer" onclick="showLanding()">
                <div class="bg-white p-2 rounded-full text-emerald-700 font-bold text-xl w-10 h-10 flex items-center justify-center shadow">
                    <i class="fa-solid fa-book-quran"></i>
                </div>
                <div>
                    <h1 class="text-lg font-bold leading-tight">MTs Unggulan Perwanida</h1>
                    <p class="text-xs text-emerald-200">Sistem Pelayanan Perpustakaan</p>
                </div>
            </div>
            
            <div class="flex items-center space-x-2">
                <button onclick="switchTab('visitor')" class="px-3 py-2 rounded-lg bg-emerald-800 hover:bg-emerald-600 text-white text-xs font-semibold transition">
                    <i class="fa-solid fa-user-edit mr-1"></i> Form Pengunjung
                </button>
                <button onclick="switchTab('catalog')" class="px-3 py-2 rounded-lg bg-emerald-800 hover:bg-emerald-600 text-white text-xs font-semibold transition">
                    <i class="fa-solid fa-book mr-1"></i> Katalog
                </button>
                <button onclick="openAdminModal()" class="px-3 py-2 rounded-lg bg-yellow-500 hover:bg-yellow-600 text-slate-900 text-xs font-bold transition">
                    <i class="fa-solid fa-user-shield mr-1"></i> Admin
                </button>
            </div>
        </div>
    </header>

    <!-- 3. MAIN CONTENT -->
    <main class="max-w-6xl mx-auto px-4 py-8 flex-grow w-full">
        <div id="alert-box" class="hidden mb-6 p-4 rounded-lg text-sm font-medium shadow-md"></div>

        <!-- TAB 1: FORM PENGUNJUNG -->
        <section id="tab-visitor" class="max-w-xl mx-auto bg-white p-6 sm:p-8 rounded-2xl shadow-md border border-slate-200">
            <div class="text-center mb-6">
                <h3 class="text-xl font-bold text-slate-800">Buku Tamu & Transaksi Buku</h3>
                <p class="text-xs text-slate-500 mt-1">Lengkapi form di bawah ini sebelum membaca atau meminjam.</p>
            </div>

            <form onsubmit="handleVisitorSubmit(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Nama Lengkap Siswa</label>
                    <input type="text" id="v-name" required placeholder="Masukkan nama..." class="w-full px-4 py-2.5 border border-slate-300 rounded-lg text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                </div>

                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Kelas</label>
                    <select id="v-class" required class="w-full px-4 py-2.5 border border-slate-300 rounded-lg text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                        <option value="">-- Pilih Kelas --</option>
                        <option value="7 Asma">7 Asma</option>
                        <option value="7 Nusaibah">7 Nusaibah</option>
                        <option value="8 Aisyah">8 Aisyah</option>
                        <option value="8 Khadijah">8 Khadijah</option>
                        <option value="9 Fatimah">9 Fatimah</option>
                        <option value="9 Ummu">9 Ummu</option>
                    </select>
                </div>

                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Keperluan</label>
                    <div class="grid grid-cols-3 gap-2">
                        <label class="border border-slate-200 rounded-lg p-2.5 text-center cursor-pointer hover:bg-emerald-50 transition">
                            <input type="radio" name="v-purpose" value="Pinjam Buku" required class="accent-emerald-600 mb-1">
                            <span class="text-xs font-semibold text-slate-700 block">Pinjam</span>
                        </label>
                        <label class="border border-slate-200 rounded-lg p-2.5 text-center cursor-pointer hover:bg-emerald-50 transition">
                            <input type="radio" name="v-purpose" value="Kembalikan Buku" class="accent-emerald-600 mb-1">
                            <span class="text-xs font-semibold text-slate-700 block">Kembalikan</span>
                        </label>
                        <label class="border border-slate-200 rounded-lg p-2.5 text-center cursor-pointer hover:bg-emerald-50 transition">
                            <input type="radio" name="v-purpose" value="Baca Buku" class="accent-emerald-600 mb-1">
                            <span class="text-xs font-semibold text-slate-700 block">Baca Tempat</span>
                        </label>
                    </div>
                </div>

                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Judul Buku</label>
                    <input type="text" id="v-book" list="book-options" placeholder="Ketik atau pilih judul buku..." class="w-full px-4 py-2.5 border border-slate-300 rounded-lg text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                    <datalist id="book-options"></datalist>
                </div>

                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Tanggal Transaksi</label>
                    <input type="date" id="v-date" required class="w-full px-4 py-2.5 border border-slate-300 rounded-lg text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                </div>

                <button type="submit" class="w-full mt-2 bg-emerald-600 hover:bg-emerald-700 text-white font-semibold py-3 rounded-xl shadow transition">
                    Simpan Data Transaksi
                </button>
            </form>
        </section>

        <!-- TAB 2: KATALOG -->
        <section id="tab-catalog" class="hidden">
            <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-200 mb-6 flex flex-col sm:flex-row justify-between items-center gap-4">
                <div>
                    <h3 class="text-lg font-bold text-slate-800">Katalog Buku Perpustakaan</h3>
                    <p class="text-xs text-slate-500">Cari buku favoritmu di bawah ini.</p>
                </div>
                <input type="text" id="catalog-search" oninput="renderCatalog()" placeholder="Cari judul atau pengarang..." class="w-full sm:w-64 px-4 py-2 border border-slate-300 rounded-lg text-sm">
            </div>
            <div id="catalog-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6"></div>
        </section>

        <!-- TAB 3: ADMIN -->
        <section id="tab-admin" class="hidden space-y-6">
            <div class="bg-emerald-900 text-white p-6 rounded-2xl flex justify-between items-center">
                <div>
                    <h3 class="text-xl font-bold">Panel Administrator</h3>
                    <p class="text-xs text-emerald-200">Kelola buku & riwayat transaksi perpustakaan.</p>
                </div>
                <button onclick="logoutAdmin()" class="bg-red-600 hover:bg-red-700 px-3 py-1.5 rounded-lg text-xs font-semibold">Keluar Admin</button>
            </div>

            <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-200">
                <div class="flex justify-between items-center mb-4">
                    <h4 class="font-bold text-slate-800">Daftar Koleksi Buku</h4>
                    <button onclick="openBookModal()" class="bg-emerald-600 text-white text-xs px-3 py-2 rounded-lg font-semibold">+ Tambah Buku</button>
                </div>
                <div class="overflow-x-auto">
                    <table class="w-full text-left text-xs text-slate-600">
                        <thead class="bg-slate-50 text-slate-700 border-b">
                            <tr>
                                <th class="p-2">Kode</th>
                                <th class="p-2">Judul</th>
                                <th class="p-2">Pengarang</th>
                                <th class="p-2">Stok</th>
                                <th class="p-2 text-center">Aksi</th>
                            </tr>
                        </thead>
                        <tbody id="admin-books-table" class="divide-y divide-slate-100"></tbody>
                    </table>
                </div>
            </div>

            <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-200">
                <h4 class="font-bold text-slate-800 mb-4">Riwayat Pengunjung</h4>
                <div class="overflow-x-auto">
                    <table class="w-full text-left text-xs text-slate-600">
                        <thead class="bg-slate-50 text-slate-700 border-b">
                            <tr>
                                <th class="p-2">Tanggal</th>
                                <th class="p-2">Nama</th>
                                <th class="p-2">Kelas</th>
                                <th class="p-2">Keperluan</th>
                                <th class="p-2">Buku</th>
                            </tr>
                        </thead>
                        <tbody id="admin-history-table" class="divide-y divide-slate-100"></tbody>
                    </table>
                </div>
            </div>
        </section>
    </main>

    <!-- MODAL ADMIN LOGIN -->
    <div id="modal-admin-login" class="fixed inset-0 bg-slate-900/60 backdrop-blur-sm hidden items-center justify-center p-4 z-50">
        <div class="bg-white rounded-2xl max-w-xs w-full p-6 shadow-2xl">
            <h3 class="text-base font-bold text-slate-800 mb-2">Login Admin</h3>
            <form onsubmit="handleAdminLogin(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-semibold text-slate-600 mb-1">PIN Admin (admin123)</label>
                    <input type="password" id="admin-pin" required class="w-full px-3 py-2 border border-slate-300 rounded-lg text-sm">
                </div>
                <div class="flex justify-end space-x-2">
                    <button type="button" onclick="closeAdminModal()" class="px-3 py-1.5 text-xs text-slate-600">Batal</button>
                    <button type="submit" class="px-3 py-1.5 bg-emerald-600 text-white text-xs rounded-lg font-semibold">Masuk</button>
                </div>
            </form>
        </div>
    </div>

    <!-- MODAL TAMBAH BUKU -->
    <div id="modal-book" class="fixed inset-0 bg-slate-900/60 backdrop-blur-sm hidden items-center justify-center p-4 z-50">
        <div class="bg-white rounded-2xl max-w-sm w-full p-6 shadow-2xl">
            <h3 class="text-base font-bold text-slate-800 mb-4">Tambah Buku Baru</h3>
            <form onsubmit="saveBook(event)" class="space-y-3">
                <input type="text" id="b-code" placeholder="Kode Buku" required class="w-full px-3 py-2 border border-slate-300 rounded-lg text-xs">
                <input type="text" id="b-title" placeholder="Judul Buku" required class="w-full px-3 py-2 border border-slate-300 rounded-lg text-xs">
                <input type="text" id="b-author" placeholder="Pengarang" required class="w-full px-3 py-2 border border-slate-300 rounded-lg text-xs">
                <input type="number" id="b-stock" placeholder="Jumlah Stok" required class="w-full px-3 py-2 border border-slate-300 rounded-lg text-xs">
                <div class="flex justify-end space-x-2 pt-2">
                    <button type="button" onclick="closeBookModal()" class="px-3 py-1.5 text-xs text-slate-600">Batal</button>
                    <button type="submit" class="px-3 py-1.5 bg-emerald-600 text-white text-xs rounded-lg font-semibold">Simpan</button>
                </div>
            </form>
        </div>
    </div>

    <script>
        const DEFAULT_BOOKS = [
            { id: '1', code: 'PAI-07', title: 'Pendidikan Agama Islam Kelas 7', author: 'Kemenag', stock: 15 },
            { id: '2', code: 'MTK-08', title: 'Matematika SMP/MTs Kelas 8', author: 'Suharno', stock: 20 },
            { id: '3', code: 'AR-09', title: 'Bahasa Arab untuk MTs Kelas 9', author: 'Ahmad M.', stock: 10 }
        ];

        let books = JSON.parse(localStorage.getItem('perwanida_books')) || DEFAULT_BOOKS;
        let historyData = JSON.parse(localStorage.getItem('perwanida_history')) || [];
        let isAdmin = false;

        document.addEventListener('DOMContentLoaded', () => {
            document.getElementById('v-date').value = new Date().toISOString().split('T')[0];
            updateDatalist();
        });

        function enterLibrary() {
            document.getElementById('landing-page').classList.add('hidden');
        }

        function showLanding() {
            document.getElementById('landing-page').classList.remove('hidden');
        }

        function switchTab(tab) {
            document.getElementById('tab-visitor').classList.add('hidden');
            document.getElementById('tab-catalog').classList.add('hidden');
            document.getElementById('tab-admin').classList.add('hidden');

            if (tab === 'visitor') document.getElementById('tab-visitor').classList.remove('hidden');
            if (tab === 'catalog') {
                document.getElementById('tab-catalog').classList.remove('hidden');
                renderCatalog();
            }
            if (tab === 'admin') {
                if (!isAdmin) {
                    openAdminModal();
                    return;
                }
                document.getElementById('tab-admin').classList.remove('hidden');
                renderAdmin();
            }
        }

        function handleVisitorSubmit(e) {
            e.preventDefault();
            const record = {
                id: Date.now().toString(),
                name: document.getElementById('v-name').value,
                class: document.getElementById('v-class').value,
                purpose: document.querySelector('input[name="v-purpose"]:checked').value,
                bookTitle: document.getElementById('v-book').value || '-',
                date: document.getElementById('v-date').value
            };
            historyData.unshift(record);
            localStorage.setItem('perwanida_history', JSON.stringify(historyData));
            
            alert('Data transaksi berhasil disimpan!');
            e.target.reset();
            document.getElementById('v-date').value = new Date().toISOString().split('T')[0];
        }

        function updateDatalist() {
            const list = document.getElementById('book-options');
            list.innerHTML = '';
            books.forEach(b => {
                list.innerHTML += `<option value="${b.title}">`;
            });
        }

        function renderCatalog() {
            const grid = document.getElementById('catalog-grid');
            const search = document.getElementById('catalog-search').value.toLowerCase();
            grid.innerHTML = '';
            
            books.filter(b => b.title.toLowerCase().includes(search)).forEach(b => {
                grid.innerHTML += `
                    <div class="bg-white p-5 rounded-xl shadow-sm border border-slate-200">
                        <span class="text-xs font-bold text-slate-400">${b.code}</span>
                        <h4 class="font-bold text-slate-800 text-sm mt-1">${b.title}</h4>
                        <p class="text-xs text-slate-500 mb-3">${b.author}</p>
                        <span class="text-xs px-2 py-1 bg-emerald-100 text-emerald-700 font-bold rounded">Stok: ${b.stock}</span>
                    </div>
                `;
            });
        }

        function openAdminModal() {
            if (isAdmin) { switchTab('admin'); return; }
            document.getElementById('modal-admin-login').classList.remove('hidden');
            document.getElementById('modal-admin-login').classList.add('flex');
        }

        function closeAdminModal() {
            document.getElementById('modal-admin-login').classList.add('hidden');
            document.getElementById('modal-admin-login').classList.remove('flex');
        }

        function handleAdminLogin(e) {
            e.preventDefault();
            if (document.getElementById('admin-pin').value === 'admin123') {
                isAdmin = true;
                closeAdminModal();
                switchTab('admin');
            } else {
                alert('PIN Admin Salah! Gunakan: admin123');
            }
        }

        function logoutAdmin() {
            isAdmin = false;
            switchTab('visitor');
        }

        function renderAdmin() {
            const bTable = document.getElementById('admin-books-table');
            bTable.innerHTML = '';
            books.forEach(b => {
                bTable.innerHTML += `
                    <tr>
                        <td class="p-2 font-mono">${b.code}</td>
                        <td class="p-2 font-semibold">${b.title}</td>
                        <td class="p-2">${b.author}</td>
                        <td class="p-2 font-bold">${b.stock}</td>
                        <td class="p-2 text-center">
                            <button onclick="deleteBook('${b.id}')" class="text-red-600"><i class="fa-solid fa-trash"></i></button>
                        </td>
                    </tr>
                `;
            });

            const hTable = document.getElementById('admin-history-table');
            hTable.innerHTML = '';
            historyData.forEach(h => {
                hTable.innerHTML += `
                    <tr>
                        <td class="p-2">${h.date}</td>
                        <td class="p-2 font-semibold">${h.name}</td>
                        <td class="p-2">${h.class}</td>
                        <td class="p-2">${h.purpose}</td>
                        <td class="p-2">${h.bookTitle}</td>
                    </tr>
                `;
            });
        }

        function openBookModal() {
            document.getElementById('modal-book').classList.remove('hidden');
            document.getElementById('modal-book').classList.add('flex');
        }

        function closeBookModal() {
            document.getElementById('modal-book').classList.add('hidden');
            document.getElementById('modal-book').classList.remove('flex');
        }

        function saveBook(e) {
            e.preventDefault();
            books.push({
                id: Date.now().toString(),
                code: document.getElementById('b-code').value,
                title: document.getElementById('b-title').value,
                author: document.getElementById('b-author').value,
                stock: document.getElementById('b-stock').value
            });
            localStorage.setItem('perwanida_books', JSON.stringify(books));
            updateDatalist();
            closeBookModal();
            renderAdmin();
        }

        function deleteBook(id) {
            if (confirm('Hapus buku ini?')) {
                books = books.filter(b => b.id !== id);
                localStorage.setItem('perwanida_books', JSON.stringify(books));
                updateDatalist();
                renderAdmin();
            }
        }
    </script>
</body>
</html>
