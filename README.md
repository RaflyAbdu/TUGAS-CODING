# TUGAS-CODING

# PENJELASAN 1 

    class Main {
        public static void main(String[] args) {
            for(int i = 1 ; i<=100; i++){
                if(i<10){
                    System.out.println(i);
                }
                else{
                    System.out.println("Rafly");
                }
            }
        }
    }

Di dalam loop, ada sebuah pernyataan kondisional if-else yang memeriksa apakah nilai i kurang dari 10 atau tidak. Jika i kurang dari 10, maka program akan mencetak nilai i menggunakan System.out.println(i);. Jika i sama dengan atau lebih besar dari 10, maka program akan mencetak teks "Rafly" menggunakan System.out.println("Rafly");

# Output

    1
    2
    3
    4
    5
    6
    7
    8
    9
    Rafly
    Rafly
    Rafly

# PENJELASAN 2

    public class SOAL2 {
        public static void main(String[] args) {
            int i = 1;
            while (i <= 10) {
                if (i % 2 == 0) {
                    System.out.println(i + " adalah bilangan genap");
                } else {
                    System.out.println(i + " adalah bilangan ganjil");
                }
                i++;
                    }
            }

        }

Kode yang Anda berikan adalah program Java sederhana yang menggunakan perulangan while untuk mencetak pesan apakah sebuah bilangan adalah bilangan genap atau ganjil dari 1 hingga 10
int i = 1;: Ini adalah deklarasi variabel i dengan nilai awal 1. Variabel ini digunakan untuk mengontrol perulangan while.
while (i <= 10) { ... }: Ini adalah perulangan while yang akan terus berjalan selama i kurang dari atau sama dengan 10.
if (i % 2 == 0) { ... }: Ini adalah pernyataan kondisional yang memeriksa apakah nilai i adalah bilangan genap. Pengecekan dilakukan dengan menggunakan operator modulo (%) untuk memeriksa apakah sisa pembagian i dengan 2 adalah 0.
else { ... }: Jika nilai i bukan bilangan genap (yaitu, bilangan ganjil), maka blok else akan dijalankan.
System.out.println(i + " adalah bilangan ganjil");: Dalam blok else, program akan mencetak pesan yang menyatakan bahwa i adalah bilangan ganjil.

# Output
        
        1 adalah bilangan ganjil
        2 adalah bilangan genap
        3 adalah bilangan ganjil
        4 adalah bilangan genap
        5 adalah bilangan ganjil
        6 adalah bilangan genap
        7 adalah bilangan ganjil
        8 adalah bilangan genap
        9 adalah bilangan ganjil
        10 adalah bilangan genap

# PENJELASAN 3

        import java.util.Scanner;
        public class soal3 {
            public static void main(String[] args) {
                Scanner sc = new Scanner(System.in);
                System.out.println("masukkan tanggal lahir anda = ");
                int tanggal = sc.nextInt();
                System.out.println("masukkan bulan lahir anda = ");
                int bulan = sc.nextInt();
        
                String zodiac = "";
        
                switch (bulan){
                    case 1:
                        zodiac = (tanggal<=19) ? "capricorn" : "Aquarius";
                        break;
                    case 2:
                        zodiac = (tanggal <=18) ? "Aquarius" : "Pisces";
                        break;
                    case 3:
                        zodiac = (tanggal <=20) ? "Pisces" : "Aries";
                        break;
                    case 4:
                        zodiac = (tanggal <=19) ? "Aries" : "Taurus";
                        break;
                    case 5:
                        zodiac = (tanggal <=20) ? "Taurus" : "Gemini";
                        break;
                    case 6:
                        zodiac = (tanggal <=20) ? "Gemini" : "Cancer";
                        break;
                    case 7:
                        zodiac = (tanggal <=22) ? "Cancer" : "Leo";
                        break;
                    case 8:
                        zodiac = (tanggal <=22) ? "Leo" : "Virgo";
                        break;
                    case 9:
                        zodiac = (tanggal <=22) ? "Virgo" : "Libra";
                        break;
                    case 10:
                        zodiac = (tanggal <=22) ? "Libra" : "Scorpio";
                        break;
                    case 11:
                        zodiac = (tanggal <=21) ? "Scorpio" : "Sagitarius";
                        break;
                    case 12:
                        zodiac = (tanggal <=21) ? "Sagitarius" : "Capricon";
                        break;
                    default:
                        System.out.println("bulan yang anda sebutkan tidak valid");
                }
                System.out.println("ZODIAC KAMU ADALAH " + zodiac);
        
            }
        }

Scanner sc = new Scanner(System.in);: Ini adalah inisialisasi objek Scanner yang digunakan untuk membaca input dari pengguna melalui System.in.
Mengambil input tanggal lahir dari pengguna:
System.out.println("masukkan tanggal lahir anda = ");: Ini adalah pernyataan untuk meminta pengguna memasukkan tanggal lahir.
int tanggal = sc.nextInt();: Ini adalah pernyataan yang menggunakan Scanner untuk membaca integer yang dimasukkan oleh pengguna dan menyimpannya dalam variabel tanggal.

# Output

        masukkan tanggal lahir anda = 
        4
        masukkan bulan lahir anda = 
        4
        ZODIAC KAMU ADALAH Aries


# PENJELASAN 4

int[] angka = new int[5];: Ini adalah deklarasi dan inisialisasi sebuah array dengan tipe data int yang disebut "angka." Array ini memiliki kapasitas untuk menyimpan 5 elemen. Array tersebut saat ini masih kosong (nilainya adalah 0).

Mengisi array dengan nilai-nilai seperti gambar di bawah

angka[0] = 10;: Elemen pertama dari array (indeks 0) diisi dengan nilai 10.
angka[1] = 20;: Elemen kedua dari array (indeks 1) diisi dengan nilai 20.
angka[2] = 30;: Elemen ketiga dari array (indeks 2) diisi dengan nilai 30.
angka[3] = 40;: Elemen keempat dari array (indeks 3) diisi dengan nilai 40.
angka[4] = 50;: Elemen kelima dari array (indeks 4) diisi dengan nilai 50.

 int[] angka = new int[5]; // Array dengan 5 elemen

        // Mengisi array dengan nilai-nilai
        angka[0] = 10;
        angka[1] = 20;
        angka[2] = 30;
        angka[3] = 40;
        angka[4] = 50;

memasukkan data 

        int total = 0;
        for (int i = 0; i < angka.length; i++) {
            total += angka[i];

            
Program menggunakan loop for untuk mengiterasi melalui semua elemen dalam array. Loop ini berjalan sebanyak elemen yang ada dalam array, yang dapat diakses menggunakan angka.length.
Selama iterasi, nilai dari setiap elemen array ditambahkan ke variabel total.
Hasilnya, total dari semua elemen dalam array dihitung dan dicetak

# Output

        Elemen ke-0: 10
        Elemen ke-1: 20
        Elemen ke-2: 30
        Elemen ke-3: 40
        Elemen ke-4: 50
        Total: 150
