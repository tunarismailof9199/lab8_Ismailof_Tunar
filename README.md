# lab8_Ismailof_Tunar
Laboratoriya İşi №8: Funksiyalar (Functions)

Bu layihə Fundamentals of Programming 1 fənni üzrə Eric Matthes-in "Python Crash Course" (Chapter 8) dərslik materialları əsasında hazırlanmış Laboratoriya işi №8 tapşırıqlarını və bonus layihəsini əhatə edir.

📌 Məqsəd və Öyrənmə Nəticələri

Bu laboratoriya işində aşağıdakı konseptlər praktiki olaraq tətbiq edilmişdir:

Mövqeli (positional), açar sözlü (keyword) və default arqumentlərin istifadəsi.

return ifadəsi ilə dəyər qaytarılması və print() ilə fərqinin nümayişi.

Dəyər kimi dictionary qaytaran funksiyalar və onların while dövrü ilə inteqrasiyası.

Listlərin funksiyaya ötürülməsi, orijinal listin dəyişdirilməsi və ya kopyalanaraq qorunması (list[:]).

İxtiyari sayda arqument qəbul edən funksiyalar (*args, **kwargs).

Funksiyaların modullarda (utils.py) saxlanılması və müxtəlif import üsulları.

PEP 8 üslub qaydalarına uyğun kodlaşdırma (docstrings, adı yazılış qaydaları, boş sətirlər).

📁 Qovluq və Fayl Strukturu

Layihənin tam strukturu aşağıdakı kimidir:

lab8_Soyad_Ad/
│
├── utils.py            # Yenidən istifadə edilə bilən əsas funksiyalar modulu (T2, T3, T5, T6)
├── lab8_main.py        # Əsas laboratoriya tapşırıqlarının (T1, T4, T5, T6, T7) icra faylı
├── task8_fixed.py      # Xətaları düzəldilmiş kod (Tapşırıq 8)
├── bonus_journal.py    # Mini layihə: «Tələbə jurnalı v2» (+10 bonus bal)
├── report.md           # Hissə A proqnozları, sualların cavabları və T8 xəta cədvəli
└── README.md           # Layihə haqqında ümumi məlumat faylı


🛠️ Tapşırıqların Xülasəsi

Hissə A: Proqnozlaşdırma və İzahlar

Kodu icra etmədən əvvəl nəticəni təxmin etmək, return vs print() və obyektlərin reference/copy məsələlərini təhlil etmək (report.md faylında əks olunub).

Hissə B: Əsas Tapşırıqlar

Tapşırıq 1 (print_student_card): Mövqeli və açar sözlü arqumentlər, arqument çatışmazlığı xətasının nümayişi.

Tapşırıq 2 (add_vat): Default parametri olan funksiya və ƏDV hesablanması (vat_percent=18).

Tapşırıq 3 (build_username): Seçimli (optional) parametr ilə istifadəçi adının generasiyası.

Tapşırıq 4 (make_student): Dictionary qaytaran funksiyanın while dövrü daxilində istifadəçidən məlumat alaraq listə əlavə edilməsi.

Tapşırıq 5 (add_bonus və with_bonus): Listin inplace (yerində) dəyişdirilməsi və scores[:] kopyası vasitəsilə orijinalın qorunması.

Tapşırıq 6 (average və make_course): *args (ixtiyari sayda ədəd) və **kwargs (ixtiyari açar-dəyər cütləri) tətbiqi.

Tapşırıq 7 (Modul İdxalı): utils.py modulunun 4 müxtəlif import üsulu ilə lab8_main.py faylında çağırılması.

Tapşırıq 8 (task8_fixed.py): Səhvləri olan kodun (sintaksis, parametr sırası, qaytarılan dəyər) tapılıb düzəldilməsi və cədvəlləşdirilməsi.

🌟 Bonus Layihə: «Tələbə jurnalı v2» (bonus_journal.py)

İstifadəçi menyusu (1: Add student, 2: Report, 3: Quit) vasitəsilə tələbələrin idarə olunması, orta balın (average_score) və ən yaxşı tələbənin (top_student) hesablanıb hesabat şəklində çap edilməsi.

🚀 İşə Salma Qaydaları (Execution)

Kodları terminal və ya əmr sətirindən icra etmək üçün lab8_Soyad_Ad qovluğuna keçin:

cd lab8_Soyad_Ad


1. Əsas Laboratoriya Faylını Çalışdırmaq:

python lab8_main.py


2. Düzəldilmiş Tapşırıq 8-i Çalışdırmaq:

python task8_fixed.py


3. Bonus Mini Layihəni Çalışdırmaq:

python bonus_journal.py


📋 Üslub Qaydaları (Style Guidelines)

Koddakı bütün funksiyalar PEP 8 standarta uyğun yazılmışdır:

Funksiya adları snake_case formatındadır (məsələn: build_username).

Hər bir funksiya üçün docstring ("""...""") təyin edilmişdir.

Funksiyalar arasında 2 boş sətir saxlanılmışdır.

Default parametrlərdə bərabərlik işarəsinin ətrafında boşluq qoyulmamışdır (məsələn: vat_percent=18).

👨‍🎓 Tələbə Məlumatları

Tələbə: [Adınız Soyadınız]

Qrup: [Qrupunuz]

Fənn: Fundamentals of Programming 1

Tarix: [Tarix]
