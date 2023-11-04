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
