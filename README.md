# Windows Styling

Windows Styling adalah kumpulan alat dan utilitas untuk memodifikasi tampilan dan nuansa Windows Anda, termasuk dock, dynamic wallpaper, efek blur, dan kustomisasi ikon. Proyek ini menyediakan berbagai aplikasi dan skrip untuk meningkatkan pengalaman visual di Windows.

## Struktur Direktori

- `AutoHotkey_2.0.19_setup.exe`  
  Installer AutoHotkey, digunakan untuk menjalankan skrip `.ahk`.

- `transparent.ahk`  
  Skrip AutoHotkey untuk membuat semua aplikasi yang dibuka menjadi transparan dengan shortcut **Ctrl + Alt + klik kanan**.

- `komorebi-0.1.37-x86_64.msi`  
  Installer Komorebi, aplikasi untuk advanced display & layouting apps (dynamic wallpaper dan pengaturan tata letak aplikasi).

- `Exploler Blur/`  
  Folder untuk modul efek blur pada Windows Explorer.  
  Digunakan untuk membuat tampilan background Explorer menjadi blur transparan.

  - `config.ini` — Konfigurasi efek blur.
  - `ExplorerBlurMica.dll` — Library efek blur.
  - `register.cmd` — Skrip registrasi efek blur.
  - `uninstall.cmd` — Skrip uninstall efek blur.

- `Release_x64/`  
  Build untuk Explorer Blur, digunakan untuk display Explorer dengan efek blur transparan.

- `MyDockFinder 2024/`  
  Folder utama aplikasi dock dan finder.  
  Memberikan efek animasi window (close, buka, dsb) seperti macOS, serta dock dengan dukungan tema, ikon, dan widget.

  - `Dock_64.exe`, `dock.exe`, `Mydock.exe` — Eksekusi utama aplikasi dock.
  - `Dockmod*.dll/.exe` — Modul tambahan untuk dock.
  - `config.ini`, `ico.ini`, `keyboard.ini`, dll — Berkas konfigurasi.
  - `padconfig.xml`, `pinyin.ini` — Konfigurasi tambahan.
  - `ScreenRound.exe` — Aplikasi untuk membulatkan sudut layar.
  - `lang/English.ini` — File bahasa Inggris untuk aplikasi.

- `static/`  
  Ui Styling Seelen UI

- `windows_11_cursors_concept_by_jepricreations_densjkc/`  
  Folder tema kursor Windows 11.

## Fitur Utama

- **MyDockFinder**  
  Dock mirip macOS untuk Windows, dengan efek animasi window (close, open, dsb) seperti macOS, serta dukungan tema, ikon, dan widget.
- **Dynamic Wallpaper & Layouting**  
  Menggunakan Komorebi untuk wallpaper dinamis dan advanced display layouting apps.
- **Explorer Blur**  
  Menambahkan efek blur transparan pada Windows Explorer.
- **Screen Rounder**  
  Membulatkan sudut layar untuk tampilan modern.
- **Kustomisasi Ikon & Tema**  
  Dukungan penggantian ikon, tema, dan bahasa.
- **Transparansi Universal**  
  Menggunakan AutoHotkey + transparent.ahk untuk membuat aplikasi apapun menjadi transparan dengan shortcut **Ctrl + Alt + klik kanan**.
- **Custom Cursor**  
  Mengganti kursor dengan tema Windows 11.

## Instalasi

1. **Ekstrak semua file** ke direktori yang diinginkan.
2. **Jalankan installer** yang diperlukan:
   - `AutoHotkey_2.0.19_setup.exe` untuk skrip `.ahk`
   - `komorebi-0.1.37-x86_64.msi` untuk dynamic wallpaper & layouting
3. **Jalankan aplikasi utama** dari folder `MyDockFinder 2024`:
   - `Dock_64.exe` atau `Mydock.exe`
4. **(Opsional) Aktifkan efek blur** dengan menjalankan `register.cmd` di folder `Exploler Blur`.
5. **(Opsional) Jalankan transparent.ahk** untuk mengaktifkan shortcut transparansi universal.
6. **(Opsional) Ganti kursor** melalui pengaturan Windows dengan file dari folder `windows_11_cursors_concept_by_jepricreations_densjkc`.

## Konfigurasi

- **Pengaturan Dock & Finder:**  
  Edit file `config.ini` di folder `MyDockFinder 2024`.
- **Bahasa:**  
  Edit atau tambahkan file di `MyDockFinder 2024/lang/`.
- **Tema & Ikon:**  
  Gunakan menu di aplikasi atau edit file `.ini` terkait.

## Catatan

- Beberapa fitur memerlukan hak administrator.
- Untuk efek visual maksimal, gunakan Windows 10/11.
- Backup konfigurasi sebelum melakukan perubahan besar.

## Lisensi

Proyek ini menggunakan berbagai aplikasi pihak ketiga. Silakan cek lisensi masing-masing aplikasi di folder terkait.

---

**Kontributor:**  
Silakan buat issue atau pull request untuk kontribusi atau pelaporan bug.
